[![license](https://img.shields.io/github/license/xupefei/QuickLook.svg)](https://www.gnu.org/licenses/lgpl-3.0.en.html)
[![AppVeyor](https://img.shields.io/appveyor/ci/xupefei/QuickLook.svg)](https://ci.appveyor.com/project/xupefei/QuickLook)
[![Github All Releases](https://img.shields.io/github/downloads/xupefei/QuickLook/total.svg)](https://github.com/xupefei/QuickLook/releases)
[![GitHub release](https://img.shields.io/github/release/xupefei/QuickLook.svg)](https://github.com/xupefei/QuickLook/releases/latest)

*This project is currently under heavy development. Come back often to see what's new.*

<img src="http://pooi.moe/QuickLook/sample.gif?3" width="400">

## Background
One of the few features I missed from Mac OS X is [Quick Look](https://en.wikipedia.org/wiki/Quick_Look). It allows user peek into a file content in a lightening speed by just pressing the <kbd>Space</kbd> key. Windows, on the other hand, does not has this handy feature ... until now.

I am aware that several alternatives are already available on the Internet (e.g. [WinQuickLook](https://github.com/shibayan/WinQuickLook) and [Seer](https://github.com/ccseer/Seer)). Despite these options, I still decide to craft another one by myself, because they are either not being actively developed, lacks of variety, or asks for a amount of $$$.

## Highlights

 - Tons of supported file types (full list [here](https://github.com/xupefei/QuickLook/wiki/Supported-File-Types))
 - Fluent design (new in version 0.3)
 - Touchscreen friendly
 - HiDPI support
 - Preview from Open and Save File Dialog
 - Preview from 3rd-party file managers (see a list [here](https://github.com/xupefei/QuickLook/wiki/File-Managers))
 - Easy extended by plugins 
 - Strict GPL license to keep it free forever

## Usage

### Download / General usage

 [What are the differences between `.msi`, `.zip`, nightly and Store versions?](https://github.com/xupefei/QuickLook/wiki/Difference-between-distributions)

 1. Download from one of the following
    * Microsoft Store (for Windows 10 users) <a href="https://www.microsoft.com/store/apps/9nv4bs3l1h4s?ocid=badge" target="_blank"><img src="https://assets.windowsphone.com/13484911-a6ab-4170-8b7e-795c1e8b4165/English_get_L_InvariantCulture_Default.png" width="80px" alt="Store Link" /></a> 
    * Installer or portable archive of the stable version from [GitHub Release](https://github.com/xupefei/QuickLook/releases) 
    * Nightly builds from [AppVeyor](https://ci.appveyor.com/project/xupefei/quicklook/build/artifacts)
 2. Run `QuickLook.exe`
 3. Select a file/folder on the Desktop / in a File Explorer window / in an Open- or Save-File dialog
 4. Press <kbd>Spacebar</kbd>
 5. Select another file/folder in the same manner
 6. When you're done, click on the `⨉` button, or press <kbd>Spacebar</kbd> again

### Hotkeys and buttons

 - <kbd>Spacebar</kbd> Show/Hide the preview window
 - <kbd>Esc</kbd> Hide the preview window
 - <kbd>Enter</kbd> Open/Execute current file
 - <kbd>Mouse️</kbd> <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> Preview another file
 - <kbd>Ctrl-Wheel</kbd> Zoom in/out images
 - <kbd>Wheel</kbd> Increase/decrease volume

## Supported file types, file manager intergation, etc.

See the [Wiki page](https://github.com/xupefei/QuickLook/wiki)

## Translations

See the [Translation guide](https://github.com/xupefei/QuickLook/wiki/Translations)

## Thanks to

 - Many [open-source projects](https://github.com/xupefei/QuickLook/wiki/On-the-Shoulders-of-Giants) and their contributors
 - Our UI designers [@OiCkilL](https://twitter.com/OiCkilL) (“Fluent” user interface since v0.3) and [@QubitsDev](https://twitter.com/qubitsdev) (application icon since v0.3)
 - [Our contributers](https://github.com/xupefei/QuickLook/graphs/contributors) who
	 - teach QuickLook speaks *your* language
	 - send pull requests, report bugs or give suggestions
 - ... and you 😊

## Licenses

![GPL-v3](https://www.gnu.org/graphics/gplv3-127x51.png)

This project references many other open-source projects. See [here](https://github.com/xupefei/QuickLook/wiki/On-the-Shoulders-of-Giants) for the full list.

All source codes are licensed under [GPL-3.0](https://opensource.org/licenses/GPL-3.0).

If you want make any modification on these source codes while keeping new codes not protected by GPL-3.0, please contact me for a sublicense instead.
