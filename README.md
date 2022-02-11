# raspberrypi-winscp-synchronize
Bat files for VSCode development on RaspberryPiZero that doesn't support VSCode Remote Development.

# Requirement
winSCP

# Installation/Setup
以下をインストール
```
https://winscp.net/eng/download.php
git clone https://github.com/tamu1203/raspberrypi-winscp-synchronize
```
# 以下のサイトに従ってwinSCPの設定を済ませる  
### IPアドレスの固定化
https://dev.classmethod.jp/articles/raspberrypi-remote-connect/
### SSHの有効化
https://zenn.dev/ryo_kawamata/articles/raspberrypi-auth-setting

# Usage
sync.batはデスクトップにショートカットを作成し実行、connect.batはvscode内で実行するのを推奨します。
```cmd
sync.bat
connect.bat
```

