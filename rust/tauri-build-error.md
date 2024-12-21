## Tauri build error (libssl.so)

### error
```bash
$ cargo tauri dev
    Running BeforeDevCommand (`dx serve --port 1420`)
dx: error while loading shared libraries: libssl.so.1.1: cannot open shared object file: No such file or directory
    Error The "beforeDevCommand" terminated with a non-zero status code.
```

### fix
```bash
$ wget http://nz2.archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2.23_amd64.deb
$ sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2.23_amd64.deb
```
