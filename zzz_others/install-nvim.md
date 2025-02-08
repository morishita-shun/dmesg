## Install latest neovim

```bash
apt remove neovim
apt install libfuse2
wget https://github.com/neovim/neovim/releases/download/v0.10.4/nvim-linux-x86_64.appimage
chmod u+x nvim-linux-x86_64.appimage && ./nvim-linux-x86_64.appimage
./nvim-linux-x86_64.appimage --appimage-extract
mv squashfs-root/usr/bin/nvim /usr/local/bin/nvim
mv squashfs-root/usr/share/nvim /usr/local/share/nvim
rm -r nvim-linux-x86_64.appimage squashfs-root/
```
