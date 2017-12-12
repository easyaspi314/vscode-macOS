# macOS Theme for Visual Studio Code

This is a macOS theme for Visual Studio Code. It is based off of the
[Xcode_default TextMate theme](https://github.com/crmne/xcode-default.tmtheme). 

For best results, use the following config: 

```js
{
    // Tab close button on the left
    "workbench.editor.tabCloseButton": "left",
    // Remove icons on the tabs
    "workbench.editor.showIcons": false
}
```
If you are on macOS, also add this:
```js
{
    // Use the native titlebar
    "window.titleBarStyle": "native",
    // Also macOS. See below for how to get Xcode's San Francisco Mono font.
    "editor.fontFamily": "'SF Mono', Menlo, Monaco, 'Courier New', monospace"
}
```

To get Xcode's San Francisco Mono font installed, install Xcode, then open Finder.

Press Command+Shift+G, then paste this:
```
/Applications/Xcode.app/Contents/SharedFrameworks/DVTKit.framework/Versions/A/Resources
```

Now drag to select all of the SFMono-* fonts, double-click them, then select
Install to add SF Mono to your usable fonts. (You can also use it in other apps as well).

<!--## This is the README for your extension "macos-theme"
You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on OSX or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on OSX or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to see a list of Markdown snippets

### For more information
* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**-->