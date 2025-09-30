# Auto Analyze

## ARM

### Aggressive Instruction Finder (Prototype)
- ディスアセンブルされていないコードを探索

### Apply Data Archives
- Data Type Archivesを適用
  - デフォルトでは用意されたgdtから自動で選択されて適用
  - ユーザ定義のgdtもオプションから設定可能

### ARM Aggressive Instruction Finder (Prototype)
- ディスアセンブルされていないARM/Thumbの混合コードを探索

### ARM Constant Reference Analyzer
- ARMの定数の参照状況を解析

### ARM Symbol
- Thumbのシンボルのバイト列を解析

### ASCII Strings
- ASCII文字列を探して自動定義
  - 最小の長さを設定可能（デフォルトは5）

### Call Convention ID
- デコンパイラで未知の呼出規約を特定
