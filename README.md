# VirtualDeskID

## 概要

**VirtualDeskID** は、タスクトレイに現在の Windows バーチャルデスクトップ番号を常に表示するソフトウェアです。モバイル PC のようにフルスクリーンモードを頻繁に使用する環境では、どのバーチャルデスクトップを使用中かを即座に把握できるため、特に便利です。

**VirtualDesktopManager**（バーチャルデスクトップのソリューションとして知られるツール）が Windows 11 では十分に機能しないため、**VirtualDesktopAccessor.dll** を活用しながらゼロから開発を行いました。  
また、本ソフトウェアはバーチャルデスクトップ番号の表示に特化させるため、**VirtualDesktopManager** にあったショートカットキー機能は省略しています。

## インストール／アンインストール

### インストール

1. ダウンロードした実行ファイル（`VirtualDeskID.exe`）を任意のフォルダに配置します。
2. そのまま実行すれば、特別なインストール作業なしで使用を開始できます。
3. Windows 起動時に自動で実行させたい場合は、スタートアップフォルダに登録するなどの方法で設定してください。

### アンインストール

- 配置したファイルを削除するだけでアンインストールは完了です。
- レジストリへの変更や追加ファイルのインストールは行いません。

## 使い方

1. **VirtualDisplayID.exe を実行**  
    起動すると、タスクトレイにアプリケーションのアイコンが表示されます。必要に応じて Windows 側の設定でアイコンが常に表示されるように調整してください。
    
2. **バーチャルデスクトップ番号の確認**
    
    - タスクトレイのアイコンにマウスカーソルを重ねるか、アイコンを見るだけで、現在のデスクトップ番号を確認できます。
    - デスクトップ番号が **1～9** の場合は、その番号に対応した専用アイコンが表示されます。
    - デスクトップ番号が **10 以上** の場合は、アイコンが `9+` に切り替わります。
3. **タスクトレイアイコンの右クリックメニュー**
    
    - **About**: バージョン情報などを表示します。
    - **Exit**: アプリケーションを終了します。

## システム要件

- Windows 11（Windows 10 では未テスト）
- x64 アーキテクチャ

## 謝辞

本ソフトウェアの開発にあたり、大きなインスピレーションを与えていただいた以下の開発者・コントリビューターの皆様に感謝いたします。

- [VirtualDesktopManager](https://github.com/m0ngr31/VirtualDesktopManager)
- [VirtualDesktopAccessor](https://github.com/Ciantic/VirtualDesktopAccessor)

---

## Overview

**VirtualDeskID** is a software utility that displays the current Windows virtual desktop number in the task tray at all times. It is particularly useful for environments where you often use full-screen mode (such as on a mobile PC), allowing you to quickly recognize which virtual desktop you are currently on.

Because **VirtualDesktopManager**, known for its virtual desktop solutions, does not function well on Windows 11, the code was developed from scratch while utilizing **VirtualDesktopAccessor.dll**. Shortcut key features found in VirtualDesktopManager were omitted to keep this tool simple and focused on showing the virtual desktop number.

## Installation / Uninstallation

### Installation

1. Place the downloaded executable file (`VirtualDeskID.exe`) in any folder of your choice.
2. That’s all you need—no separate installation is required.
3. If you want it to start automatically when Windows boots, add it to your Startup folder or configure it accordingly.

### Uninstallation

- To uninstall, simply delete the file you placed.
- This software makes no changes to the registry and does not install extra components.

## Usage

1. **Run VirtualDisplayID.exe**  
    After launching, an icon will appear in the task tray. If desired, configure Windows settings so that the icon is always displayed.
    
2. **Check the virtual desktop number**
    
    - Hover your mouse over the task tray icon or look at it directly to see which desktop number you are on.
    - If the number is between **1** and **9**, a dedicated icon with that number is displayed.
    - If the number is **10 or higher**, the icon changes to `9+`.
3. **Task tray icon right-click menu**
    
    - **About**: Displays version information and related details.
    - **Exit**: Exits the application.

## System Requirements

- Windows 11 (untested on Windows 10)
- x64 architecture

## Acknowledgments

We would like to express our gratitude to the authors and contributors of:

- [VirtualDesktopManager](https://github.com/m0ngr31/VirtualDesktopManager)
- [VirtualDesktopAccessor](https://github.com/Ciantic/VirtualDesktopAccessor)

Their work has greatly inspired the development of this software.