# FiDB

## example
### get library object files
```bash
$ wget https://uclibc.org/downloads/binaries/0.9.30.1/system-image-armv4l.tar.bz2
$ tar -xf system-image-armv4l.tar.bz2
$ cd system-image-armv4l/
$ debugfs -R "dump /lib/libc.a libc.a" image-armv4l.ext2
$ mkdir libc
$ ar x --output=libc/ libc.a
$ ls libc/
a64l.o                 getdents.o                 ntohl.o                     strchrnul.o
abort.o                getdirname.o               ntop.o                      strchr.o
abs.o                  getdomainname.o            ntp_gettime.o               strcmp.o
```

### make fidb
- open object file in Ghidra
- [Tools] -> [Function ID] -> [Create new empty FidDb...]
- [Tools] -> [Function ID] -> [Populate FidDb from programs...]
