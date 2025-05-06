## PyGhidra

### make venv
```bash
$ ./<GHIDRA_INSTALL_DIR>/support/pyghidraRun
```

### handle no module pip error (if needed)
```bash
$ ~/.config/ghidra_<VERSION>_PUBLIC/venv/bin/python3 -m ensurepip --default-pip
$ ./<GHIDRA_INSTALL_DIR>/support/pyghidraRun
```

### install additional packages
```bash
$ source ~/.config/ghidra/ghidra_<VERSION>_PUBLIC/venv/bin/activate
(venv)$ pip3 install <PACKAGE>
(venv)$ deactivate
```

or

```bash
$ ~/.config/ghidra/ghidra_<VERSION>_PUBLIC/venv/bin/pip3 install <PACKAGE>
```
