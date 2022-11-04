## Core Commands
-  connect with host (like netcat): `connect`
-  variables
	- set value: `set`, `setg`
	- unset value: `unset`, `usetg`
	- view value: `get`, `getg`
-  set console output to save to file (spool): `spool`
-  store the setting/ active datastores to a setting file: `save`
	-  this can be undone by removing created settings file.

## Module
- search modules: `search`
- use modules: `use`
- view info about an module: `info`

## DB
- `db_status`

## Other Commands
`show options` : 
![[Pasted image 20210709134644.png]]
display all the options needed to set before running the module (eg. IP address, port, URI etc.)

`show payloads` : 
![[Pasted image 20210709134558.png]]
when used **after** selecting your exploit, will show you all the payloads that are compatible with this exploit (note the column heading

`show targets` :
![[Pasted image 20210709134954.png]]
Each exploit has a list of the targets it will work against. By using the "show targets" command, we can get a list of them.

`info` :
![[Pasted image 20210709135229.png]]
If used after selecting  a modules gives key ino about the module, including the options.
![[Pasted image 20210709135350.png]]

`search`
To be more speciic in our search, we can use folloing keywords
- **platform**
	- windows, linux etc.
- **type**
	- **options**: exploit, nops, payloads, post, encoder, envasion and auxilary
- **name**
	- flash, icecast etc.
![[Pasted image 20210709140634.png]]
![[Pasted image 20210709140727.png]]