# VSCode AppImage Builder
![example workflow](https://github.com/Toomoch/VSCode-AppImage-Builder/actions/workflows/vscode.yml/badge.svg)

This repository contains an action that builds the latest version of VSCode as an AppImage with [pkg2appimage](https://github.com/AppImage/pkg2appimage). If the version on the releases page is the same as the live one, it exits early in the build.