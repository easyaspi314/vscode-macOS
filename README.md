# macOS Theme for Visual Studio Code

GitHub source: https://github.com/easyaspi314/vscode-macOS

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

## License

My workspace colors are released under the MIT license, but as for the syntax theme, no license was
provided.