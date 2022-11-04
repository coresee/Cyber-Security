### Consists of 6 core modules that make up of bulk of the tools.
![[Pasted image 20210703144925.png]] *metaploit framework architecture*

## Modules
- __Exploit__: Holds all of the exploit codes
- __Payload__: Contains various bits of shellcode we send to have executed following exploit. Used hand in hand with exploits.
- __Auxiliary__: Most commanly used in scanning and verification of machines are exploitable.
- __Post__: Used for looting and pivoting
- __Encoder__: Allows us to modify 'appearance' of our exploit such that we may avoid signature detection. Commonly utilized in payload obfuscation.
- __NOP__: Used for buffer overflow and ROP attacks.
- __Envasion__: Designed to help you create payloads that can evade anti-virus (AV) software on the target system