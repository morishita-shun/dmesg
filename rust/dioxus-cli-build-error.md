## dioxus-cli build error (gcc-9)

### error
```bash
$ cargo install dioxus-cli --locked
...

  ### COMPILER BUG DETECTED ###
  Your compiler (cc) is not supported due to a memcmp related bug reported in https://gcc.gnu.org/bugzilla/show_bug.cgi?id=95189. We strongly recommend against using this compiler.
```

### fix
```bash
$ gcc -v
gcc version 9.4.0 (Ubuntu 9.4.0-1ubuntu1~20.04.2)
```

Update to gcc-10 to avoid the error

```bash
$ sudo apt install gcc-10
$ sudo ln -s /usr/bin/gcc-10 /usr/bin/gcc

$ gcc -v
gcc version 10.5.0 (Ubuntu 10.5.0-1ubuntu1~20.04)
```

