# Shellcoding


## Programs


### [RunBin]

This was migrated to an independent repository, [RunBin].

Executing data on the stack, which is used to test and debug shellcode.


## Scripts


### [mkhex.sh](./historic/mkhex.sh)

This was deprecated
and [IntelliCoder] is strongly recommended for the time being.

Extracting shellcode from binaries
and / or constructing C source code for demonstration or testing.


### disbin32 / disbin64

This was migrated to an independent repository, [RunBin].

Disassemble the given raw binary using `objdump`.


## Linux Shellcode

- [exit IA32 7 Bytes Null-Free](./linux/exit/expert.s)

- [execve /bin/sh IA32 21 Bytes Null-Free](./linux/sh/push.s)

- [execve /bin/sh AMD64 23 Bytes Null-Free](./linux/sh/push64.s)


## Windows Shellcode

- [user32!MessageBoxA "Hello World!" All x86 Windows 199 Bytes Null-Free](./windows/messagebox/messagebox32.asm)


## Documentation

- [对照内核结构深入理解动态定位 API](./doc/api-res-zh_CN.md)


[IntelliCoder]: https://github.com/NoviceLive/intellicoder
[RunBin]: https://github.com/NoviceLive/runbin
