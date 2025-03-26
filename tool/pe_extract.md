## pe_extract
- https://github.com/TheEnergyStory/malware_analysis_tools/tree/main/pe_extract
- https://r136a1.dev/2022/05/25/introduction-of-a-pe-file-extractor-for-various-situations/

### Usecase
- Extract payload(s) from a manual memory dump
  - `python pe_extract.py <FilePathToDump> (--extract-xored)`
- Extract payload(s) from on-disk file(s)
  - `python pe_extract.py <FilePathToDump> --extract-xored (--extract-overlays)`
- Extract payload(s) from automatically created memory dumps
  - `python pe_extract.py <FolderPathToDumps> (--extract-overlays) (--extract-all)`
