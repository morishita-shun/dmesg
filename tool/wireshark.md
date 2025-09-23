# wireshark

## TLS通信の復号
https://wiki.wireshark.org/TLS#tls-decryption
- 環境変数`SSLKEYLOGFILE`を設定
  - 変数値は保存したいファイルパス
- Wiresharkの設定項目に上記のファイルパスを設定
  - [Edit] -> [Preferences] -> [Protocols] -> [TLS] -> [(Pre)-Master-Secret log filename]
  - or [Tools] -> [TLS Keylog Launchar] -> [TLS (Pre)-Master-Secret log file path (tls.keylog_file)]
