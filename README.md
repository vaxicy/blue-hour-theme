<p align="center">
  <img src="https://raw.githubusercontent.com/vaxicy/blue-hour-theme/main/assets/icon.png" alt="Blue Hour Theme logo" width="128">
</p>

<h1 align="center">Blue Hour Theme</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=lilinhuang.blue-hour-theme"><img src="https://img.shields.io/badge/VS%20Code-Theme-4B5694?logo=visual-studio-code" alt="VS Code Theme"></a>
  <img src="https://img.shields.io/badge/version-1.0.0-7288AE?logo=visual-studio-code" alt="version 1.0.0">
  <img src="https://img.shields.io/badge/Variants-Light%20%26%20Dark-EAE0CF?logo=visual-studio-code" alt="Light and Dark variants">
  <a href="https://github.com/vaxicy/blue-hour-theme/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Non--Commercial-lightgrey" alt="License: Non-Commercial"></a>
</p>

A twilight-inspired editor theme built around **ink navy**, **indigo**, **slate blue** and **warm parchment**. Two coordinated variants share one palette, so the workspace keeps the same quiet blue-hour character in light and dark mode.

以**墨蓝、靛蓝、石板蓝与暖羊皮纸色**为核心的一套暮色主题：明暗两套变体共享同一色板，切换时保持同一份蓝调时刻的气质。

## Preview / 预览

| Light 浅色 | Dark 深色 |
| --- | --- |
| ![Blue Hour Theme Light](https://raw.githubusercontent.com/vaxicy/blue-hour-theme/main/store-assets/screenshots/en/screenshot-light.png) | ![Blue Hour Theme Dark](https://raw.githubusercontent.com/vaxicy/blue-hour-theme/main/store-assets/screenshots/en/screenshot-dark.png) |

> Both previews are captured from a real VS Code window running the theme — no mockups.
>
> 上方预览图取自真实运行该主题的 VS Code 窗口截图，非模拟图。

## Palette / 色板

| Role | Light | Dark |
| --- | --- | --- |
| Editor background | `#F5F0E7` warm parchment | `#111844` ink navy |
| Foreground | `#303952` ink slate | `#EAE0CF` parchment |
| Cursor | `#4B5694` indigo | `#EAE0CF` parchment |
| Focus border / links | `#4B5694` / `#46658B` | `#9CB6D8` |
| Selection | `#CFD8E8` | `#3B4874` |
| Current line | `#EDE7DD` | `#18214D` |
| Side bar | `#EAE0CF` | `#252E50` |
| Title bar | `#EAE0CF` | `#303B60` |
| Status bar | `#7288AE` | `#4B5694` |
| Activity bar | `#4B5694` with parchment icons | `#202951` with parchment icons |
| Tabs (bar / inactive tab) | `#DDE2EB` | `#303B60` |
| Borders / indent guides | `#D3D0C9` | `#404A6A` |
| Button | `#4B5694` with white text | `#EAE0CF` with ink navy text |
| Badge | `#111844` on `#EAE0CF` | `#111844` on `#EAE0CF` |

Both variants are built from the same roles, so switching between them changes the light level rather than the identity.

两套变体的角色色一一对应，切换时改变的是明暗而非风格。

## Syntax mapping / 语法映射

| Syntax | Light | Dark |
| --- | --- | --- |
| Comments | `#7D807F` | `#8391AD` |
| Keywords / storage / tags | `#4B5694` indigo | `#B0B8E0` periwinkle |
| Strings | `#46716D` pine | `#A8C5BD` mist |
| Numbers / constants | `#886A3F` bronze | `#D8C29E` sand |
| Types / classes | `#756082` plum | `#C5B3D0` lilac |
| Functions / methods | `#46658B` blue | `#9CB6D8` sky |
| Attributes | `#886A3F` | `#EAC18C` |
| Variables | `#303952` | `#EAE0CF` |
| Headings / invalid | `#4B5694` / `#AB4858` | `#B0B8E0` / `#E69DA8` |

Every accent stays desaturated on purpose: highlights read clearly without turning the editor into a neon rainbow.

所有强调色都刻意保持低饱和：清晰可辨，又不会把编辑器变成霓虹灯。

## Coverage / 覆盖范围

Every surface below is themed in both variants:

- **Editor** — background, foreground, selection and inactive selection, current-line highlight, find match and find highlight, bracket-match background and border, cursor, line numbers (plus the active line number), indent guides, whitespace, errors, warnings and info.
- **Workbench chrome** — activity bar and its badge, title bar (active and inactive), side bar and its border, status bar (normal, no-folder and debugging states), editor group header and tabs (active, inactive, border and active top border).
- **Panels and overlays** — panel, editor widgets, hover widget, suggest widget, dropdowns, inputs and placeholder text, notifications, quick input, and the focus border.
- **Lists** — active, inactive and hover selection backgrounds, plus the highlight color.
- **Terminal** — background, foreground and the full 16-color ANSI palette, matched to the theme.
- **Details** — workbench borders, scrollbar sliders, git decoration colors (added / modified / deleted), buttons and badges, and semantic token colors for function, method, class, type, string, number, keyword and comment.

Diff editor, peek view, breadcrumbs, minimap, debug toolbar and the settings UI are intentionally left to VS Code's defaults.

以下区域在两套变体中均已配色：编辑器本体（选区、当前行、查找匹配、括号匹配、光标、行号、缩进线、空白符、错误/警告/提示）、活动栏与角标、标题栏、侧边栏、状态栏（含无文件夹与调试态）、标签栏，以及面板与各类浮窗（悬停、建议、通知、快速输入）、下拉与输入框、列表选中/悬停、全部边框与滚动条、Git 装饰色、终端 ANSI 全色，以及函数/方法/类/类型/字符串/数字/关键字/注释的语义高亮。差异编辑器、peek 视图、面包屑、缩略图、调试工具栏与设置界面保留 VS Code 默认样式。

## Features / 功能

- **Two coordinated variants** — `Blue Hour Theme Light` and `Blue Hour Theme Dark` ship in one extension.
- **One twilight palette** — ink navy, indigo, slate blue and warm parchment run through the editor, side bar, activity bar, status bar and terminal.
- **Readable syntax colors** — indigo keywords, pine strings, bronze numbers and plum types, tuned for contrast on both backgrounds.
- **Semantic highlighting** enabled, so language-aware tokens are colored beyond the classic TextMate scopes.
- **Terminal ANSI colors** taken from the same palette, so the integrated terminal sits inside the theme.

- **明暗两套协调变体**——同一扩展内含 `Blue Hour Theme Light` 与 `Blue Hour Theme Dark`。
- **一套暮色色板**——墨蓝、靛蓝、石板蓝与暖羊皮纸色贯穿编辑器、侧边栏、活动栏、状态栏与终端。
- **可读的语法配色**——靛蓝关键字、松绿字符串、铜棕数字、梅紫类型，在明暗底色上均保持对比。
- **启用语义高亮**，在传统 TextMate scope 之外为语言感知的 token 着色。
- **终端 ANSI 配色**取自同一色板，集成终端与主题融为一体。

## Installation / 安装

Requires VS Code 1.80 or newer.

1. Search for **Blue Hour Theme** in the Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`), or open the [Marketplace page](https://marketplace.visualstudio.com/items?itemName=lilinhuang.blue-hour-theme).
2. Or install from a VSIX: download `blue-hour-theme-1.0.0.vsix`, open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run **Extensions: Install from VSIX...**.

需要 VS Code 1.80 或更高版本。

1. 在扩展面板（`Ctrl+Shift+X` / `Cmd+Shift+X`）搜索 **Blue Hour Theme**，或打开 [Marketplace 页面](https://marketplace.visualstudio.com/items?itemName=lilinhuang.blue-hour-theme)。
2. 也可以从 VSIX 安装：下载 `blue-hour-theme-1.0.0.vsix`，打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Extensions: Install from VSIX...** 并选择该文件。

Or from the command line:

或使用命令行：

```
ext install lilinhuang.blue-hour-theme
```

## Activation / 启用

Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`), run **Preferences: Color Theme**, and choose **Blue Hour Theme Light** or **Blue Hour Theme Dark**.

To switch between the two variants quickly, use the keyboard shortcut `Ctrl+K Ctrl+T` at any time.

打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Preferences: Color Theme**，选择 **Blue Hour Theme Light** 或 **Blue Hour Theme Dark**。

随时可用快捷键 `Ctrl+K Ctrl+T` 在两套变体之间快速切换。

## Development / 开发

Open this folder in VS Code and press `F5` to launch an Extension Development Host with the theme loaded. Regenerate the real-window preview screenshots with:

在 VS Code 中打开本文件夹并按 `F5`，在扩展开发宿主中预览主题。重新生成真实窗口预览图：

```bash
python3 scripts/capture-real-screenshots.py
```

The script builds a throwaway VS Code profile, installs this theme into it, opens the sample project under `scripts/demo-project` and captures the window for both variants into `store-assets/screenshots/en/`.

脚本会临时创建一个独立的 VS Code 配置目录，把本主题装进去，打开 `scripts/demo-project` 示例工程，并把两套变体的窗口截图输出到 `store-assets/screenshots/en/`。

## License / 许可

Released under the **Non-Commercial License** — licensed for personal, educational and non-commercial use. See [LICENSE](LICENSE) for details.

基于 **Non-Commercial License（非商业使用许可）** 发布，可用于个人、教育及非商业用途，详见 [LICENSE](LICENSE)。

## Feedback / 反馈

Found an unthemed area or want a tweak? Open an issue at [github.com/vaxicy/blue-hour-theme/issues](https://github.com/vaxicy/blue-hour-theme/issues).

发现没有配色的区域或想调整某处颜色，欢迎在 [GitHub Issues](https://github.com/vaxicy/blue-hour-theme/issues) 反馈。

## Publisher / 发布者

Published by **lilinhuang** on the Visual Studio Code Marketplace.
