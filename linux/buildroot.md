# buildroot
- https://buildroot.org/

## Usage

```bash
$ sudo apt install -y make binutils build-essential gcc unzip libncurses-dev
$ git clone https://gitlab.com/buildroot.org/buildroot.git
$ cd buildroot/
$ git checkout 2025.08.1
$ make menuconfig
$ make
```

## Target Architecture
- ARC (little endian)
- ARC (big endian)
- ARM (little endian)
- ARM (big endian)
- AArch64 (little endian)
- AArch64 (big endian)
- i386
- LoongArch64
- m68k
- Microblaze AXI (little endian)
- Microblaze non-AXI (big endian)
- MIPS (big endian)
- MIPS (little endian)
- MIPS64 (big endian)
- MIPS64 (little endian)
- OpenRISC
- PowerPC
- PowerPC64 (big endian)
- PowerPC64 (little endian)
- RISCV
- s390x
- SuperH
- SPARC
- SPARC64
- x86_64
- Xtensa
