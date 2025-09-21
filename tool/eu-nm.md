# eu-nm

```bash
$ sudo apt install elfutils
```

nmと違ってファイルの行数まで表示されることがある
```bash
$ eu-nm [file]
Symbols from [file]:

Name                                   Value    Class  Type     Size                  Line Section
...
_Unwind_ForcedUnwind                  |0001ae80|GLOBAL|FUNC    |00000024|                 |.text
_Unwind_GetCFA                        |0001a1c4|GLOBAL|FUNC    |00000008| unwind-arm.c:600|.text
_Unwind_GetDataRelBase                |0001a208|GLOBAL|FUNC    |0000000c|unwind-arm.c:1008|.text
_Unwind_GetLanguageSpecificData       |0001aea4|GLOBAL|FUNC    |00000044| pr-support.c:367|.text
_Unwind_GetRegionStart                |0001b644|GLOBAL|FUNC    |00000034| pr-support.c:356|.text
_Unwind_GetTextRelBase                |0001a1fc|GLOBAL|FUNC    |0000000c|unwind-arm.c:1014|.text
_Unwind_RaiseException                |0001ae14|GLOBAL|FUNC    |00000024|                 |.text
_Unwind_Resume                        |0001ae38|GLOBAL|FUNC    |00000024|                 |.text
```
