# PyGhidra

## install python3.12 (if needed)
```bash
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt update -y
$ sudo apt install -y python3.12 python3.12-venv
$ curl -sS https://bootstrap.pypa.io/get-pip.py | python3.12
```

## make venv
```bash
$ ./<GHIDRA_INSTALL_DIR>/support/pyghidraRun
```

## handle no module pip error (if needed)
```bash
$ ~/.config/ghidra_<VERSION>_PUBLIC/venv/bin/python3 -m ensurepip --default-pip
$ ./<GHIDRA_INSTALL_DIR>/support/pyghidraRun
```

## install additional packages
```bash
$ source ~/.config/ghidra/ghidra_<VERSION>_PUBLIC/venv/bin/activate
(venv)$ pip3 install <PACKAGE>
(venv)$ deactivate
```

or

```bash
$ ~/.config/ghidra/ghidra_<VERSION>_PUBLIC/venv/bin/pip3 install <PACKAGE>
```
