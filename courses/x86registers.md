# x86 Registers

Intel x86 processor has a lot a registers, each has specific rôle.

## 1. Base registers

| Register | Name | Description |
|---|---|---|
|**eax**|**A**ccumulator | Used for several mathematicals operations, function to call and return value after result |
|**ebx**|**B**ase | Used for indirect addressing |
|**ecx**|**C**ounter | Used as counter for loop and handover between ESI and EDI registers |
|**edx**|**D**ata | Used for specific mathematicals operations |

***
## 2. Index and Pointers registers

| Register | Name | Description|
|---|---|---|
|**esp**|**S**tack **P**ointer| Point to last added element in the Stack |
|**ebp**|**B**ase **P**ointer| Reference stack begin address |
|**esi**|**S**ource **I**ndex| Used for some string operations |
|**edi**|**D**estination **I**ndex| Also used for some string operations |
|_**eip**_|_**I**nstruction **P**ointer_| _Cannot be edited_ Always reference next instruction address |
***

## 3. Flags register

Follewed bits compound flags registers which his size is :
* 16 bits (2 bytes) for *flag*
* 32 bits (4 bytes) for *eflags* register

| Flag | Name | Position | Size |
|---|---|---|---|
|**cf**|**C**arry **F**lag|0|2 bits|
|**pf**|**P**arity **F**lag|2|2 bits|
|**af**|**A**uxiliary carry **F**lag|4|2 bits|
|**zf**|**Z**ero **F**lag|6|2 bits|
|**sf**|**S**ign **F**lag|8|1 bit|
|**if**|**I**nterruption **F**lag|9|1 bit|
|**df**|**D**irection **F**lag|10|1 bit|
|**of**|**O**verflow **F**lag|11|1 bit|
