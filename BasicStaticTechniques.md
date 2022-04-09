# Basic Static Techniques.

**We'll dicuss the following techniques**
* Using antivirus tools to confirm maliciousness.
* Using hashes to indentofy malware.
* Gleaning information from a file's strings,functions, and headers.

### Antivirus Scanning
[Virus Total](https://www.virustotal.com/gui/home/upload)

### Hashing: A Fingerprint for Malware
* md5sum
* hascalculator
* md5deep
### Finding Strings
* strings 
* bintext

### Packed and Obfuscade Malware.

**Packed and obfuscated code will often include at least the finctions LoadLibrary and GetProcessAddres**.
* UPX
* PeiD

### Portable Executable File Format.

### Linked Libraries and Functions

### STatic, Runtime, and Dynamic Linking.
* Dependency Walker

**COmmon DLLs**
* Kernel32.dll
* Advapi32.dll
* User32.dll
* Gdi32.dll
* Ntdll.dll
* WSock32.dll 
* Ws2_32.dll
* Wininet.dll

### Imported Functions.

### Exported Functions.

### PE File Header and Sections
* text : contains instructions that the CPU executes.
* rdata : contains import and export information.
* data : contains program's global data 
* rsrc : includes the resources used by he executable.
### PEview
