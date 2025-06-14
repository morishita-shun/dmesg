## system-calls
- https://pypi.org/project/system-calls/
- https://github.com/hrw/syscalls-table

### Usage
```bash
pip3 install system-calls
```

```python
>>> import system_calls
>>> syscalls = system_calls.syscalls()
>>> syscall_arch = "arm"
>>> syscalls.get("write", syscall_arch)
4
```
