![BadWrite](assets/BadWrite.png)
# BadWrite

**A Markdown editor developed in Sicily with wine.**

BadWrite is a simple, fast and distraction-free Markdown editor for Windows. Write on one side, press **F5** and see the result.

🇮🇹 [Leggi in italiano](README.it.md) · 🌐 [Website](https://www.steo.it/badwrite/)

> \*\*Beta software.\*\* BadWrite is in beta: it works, but you may find rough edges. Please keep a backup of important documents and tell me what you find (see \[Feedback](#feedback)).

![screenshot_1](assets/screenshot_1.png)

## Download

Get the latest version from the [**Releases**](../../releases) page.

1. Download the `.zip` file from the latest release.
2. Extract it to any folder.
3. Run `BadWrite.exe`.

The SHA-256 checksum of each file is listed in the release notes, so you can verify your download.

### Windows SmartScreen

BadWrite is not code-signed yet, so Windows may show *"Windows protected your PC"* the first time. Click **More info → Run anyway**. You can compare the checksum with the one in the release notes before running it.

## Requirements

* Windows 10 or 11 (64-bit)
* [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) (x64, if not already installed)
* Microsoft Edge WebView2 Runtime (already included in Windows 11 and in up-to-date Windows 10)

## Features

**Writing**

* Markdown syntax highlighting while you type
* Continues lists and task lists when you press Enter
* Table insertion and automatic table formatting (`Ctrl+Shift+T`)
* Drag \& drop images into the document
* Find and replace with a floating panel (`Ctrl+F` / `Ctrl+H`)
* Focus mode (`F8`) and typewriter mode (`F9`)
* Full screen with clock (`F11`)

**Navigation**

* Outline panel to move through long documents
* Explorer panel for a whole folder of notes, with full-text search

**Spell checking**

* Spell checker as you type, with suggestions and a personal dictionary
* Hunspell dictionaries (`.dic` / `.aff`): some dictionaries are included, and you can add other languages by copying them into the `Dictionaries` folder

**Preview and export**

* HTML preview synchronized with the cursor (`F5`)
* Export to HTML page (with a choice of theme and optional copy of the images), HTML code, PDF and DOCX
* Copy the HTML of the document or of the selection to the clipboard
* Print

**Appearance**

* 11 themes, including Dark, Coffee, Midnight Blue, Sky Blue, Forest, Sepia, Solarized (light and dark), Nord and Antique Rose, plus *Automatic* to follow Windows

**Files**

* Automatic detection of the text encoding (UTF-8, ANSI, UTF-16) and the option to reopen or save with another one
* Autosave and recovery of unsaved text at the next start
* Recent files and folders

## Keyboard shortcuts

|Shortcut|Action|
|-|-|
|`F5`|Toggle preview|
|`F8` / `F9`|Focus mode / Typewriter mode|
|`F11`|Full screen|
|`Ctrl+N` / `Ctrl+Shift+N`|New document / New window|
|`Ctrl+O`|Open|
|`Ctrl+S` / `Ctrl+Shift+S`|Save / Save as|
|`Ctrl+F` / `Ctrl+H`|Find / Replace|
|`Ctrl+B` / `Ctrl+I` / `Ctrl+K`|Bold / Italic / Inline code|
|`Ctrl+Shift+T`|Format table|
|`Ctrl+Shift+H`|Copy HTML to clipboard|

## Feedback

This is a beta, and your feedback is what makes it better.

* Found a bug or have an idea? Open an [issue](../../issues).

When reporting a bug, please include the BadWrite version (shown in **Help → About**), your Windows version and the steps to reproduce it.

## License and credits

BadWrite is © Stefano Arcidiacono. It is free to use, but it is not open source:
all rights are reserved. Please do not redistribute modified versions;
to share BadWrite, link to this page.

BadWrite uses open-source components, listed with their licenses in [`THIRD-PARTY-LICENSES.txt`](THIRD-PARTY-LICENSES.txt) and in **Help → About**: AvalonEdit, Markdig, Open XML SDK, HtmlToOpenXml, AngleSharp, Microsoft.Data.Sqlite, WebView2, WeCantSpell.Hunspell and some dictionaries from LibreOffice.

