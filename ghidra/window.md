# Window

## Bookmarks
- Bookmarksを追加
  - Listing内で右クリック->[Bookmarks...] (Ctrl-D)
- Bookmarksに移動
  - Bookmarksウィンドウ内の対象Bookmarksをダブルクリック

## Bundle Manager
- ghidra_scriptsフォルダの設定

## Bytes
- Enable/Disable editing of bytes in Byte Viewer panels. (Ctrl+Alt+E)
  - 命令(instruction)以外のバイト列を書き換え可能
- Set Byte Viewer Options
  - 行当たりのバイト数変更
  - Ascii文字の表示

## Checksum Generator
- Listing内で選択したアドレスレンジのバイト列のチェックサムを計算

## Comments
- コメントの一覧を表示
  - Filterで絞り込み
  - ダブルクリックで移動

## Console
- Scroll Lock
- Clear Console

## Data Type Manager
- 右クリック->New
  - Category
  - Enum...
  - Function Definition...
  - Structure...
  - Typedef...
  - Union...

## Data Type Preview
- Listing内で選択したアドレスを複数のデータ型で認識したときのプレビューを表示
  - byte
  - char
  - double
  - dword
  - float
  - qword
  - TerminatedCString
  - TerminatedUnicode
  - word

## Decompile
- 右クリック
  - Previous Highlight (Ctrl+Comma)
  - Next Highlight (Ctrl+Period)
  - Find... (Ctrl+F)
    - StringとRegular Expressionで検索
  - Properties
    - DecompilerのOptionsを設定
- ツールバー
  - Export current function to C
  - Create a snapshot (disconnected) copy of this Decompiler window (Ctrl+Shift+T)

## Defined Data
- プログラム内に定義されたデータの内容、位置、タイプ、サイズを表示
