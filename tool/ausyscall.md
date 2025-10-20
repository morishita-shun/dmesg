# ausyscall

## Install
```bash
$ sudo apt install auditd
```

## Usage
```bash
$ ausyscall
usage: ausyscall [arch] name | number | --dump | --exact
```

```bash
$ ausyscall arm --dump
Using armeb syscall table:
0       restart_syscall
1       exit
2       fork
3       read
4       write
5       open
6       close
8       creat
9       link
10      unlink
...

$ ausyscall arm 5
open

$ ausyscall arm open
open               5
mq_open            274
openat             322
perf_event_open    364
open_by_handle_at  371
open_tree          428
fsopen             430
pidfd_open         434
openat2            437

$ ausyscall arm open --exact
5
```
