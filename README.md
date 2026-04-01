# README

For a quick start guide, please refer to the [VS Code Extension Quickstart](vsc-extension-quickstart.md).

Use command to build.
```bash
sudo apt install nodejs npm
sudo npm config set registry https://mirrors.cloud.tencent.com/npm/
sudo npm install -g @vscode/vsce
vsce package
code --install-extension my-extension-0.0.2.vsix
```
**Enjoy!**
