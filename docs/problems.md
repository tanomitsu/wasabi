# Problems & Solutions

## QEMU error

### Problem

```
$ qemu-system-x86_64 -bios third_party/ovmf/RELEASEX64_OVMF.fd
undefined symbol: __libc_pthread_init, version GLIBC_PRIVATE
```

### Solution

It was because I was executing the command **inside VSCode's integrated terminal**.

S