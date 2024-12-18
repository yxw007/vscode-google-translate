# Vscode Google Translate Next

English | [简体中文](./README_zh-CN.md)

[![Licence](https://img.shields.io/github/license/yxw007/vscode-google-translate.svg)](https://github.com/yxw007/vscode-google-translate)

<h1 style="color:red">Special Note: This plugin will not be updated anymore, please use our newly developed plugin: <a href="https://github.com/yxw007/vscode-translate-next">vscode-translate-next</a>, which provides more features and better user experience. it provides more functions and better user experience, perfect replacement for vscode-google-translate.</h1>

Quickly translate text right in your code 🚀

![Demo](demo.gif)

## Usage

### Translate selected text

1. Select some text to translate
1. Press `ALT+SHIFT+T`
1. Select the output languages you want and enjoy 👍

### Translate a line under cursor

This feature inserts a newline under the current one with translation

1. Set cursor/cursors on line(s) to translate
1. Select menu 'Translate line(s) under the cursor'
1. Select the output languages you want and enjoy

## Preferred language settings

Want to quickly translate into a specific language?
Run Command 'Set Preferred Language' or Set it in VSCode extension settings

## Tooltip Hover Translation

By default when you hover over comments and code, you will get a translation into
your preferred language hovering above the element. If you want to turn this off
go into extension settings and un-check HoverTranslations then restart VSCode.

## Proxy Support

You can use a proxy to translate text with the following settings:

```js
"vscodeGoogleTranslate.host": "120.0.0.1"       // Proxy disabled if empty
"vscodeGoogleTranslate.port": "8080"            // Proxy port
"vscodeGoogleTranslate.username": "admin"       // Proxy auth disabled if empty
"vscodeGoogleTranslate.password": "password"    // Proxy password
```

## Pull request

Pull request are welcome. Fork the project, clone it, install dependencies `npm i` and start coding :-).

If you want to make changes to the code hovering translations. Please run "npm run compile" from the root in order to compile the typescript
part of the codebase.

Many thanks to the people who participate for making it awesome!

## Special Thanks

- [funkyremi/vscode-google-translate](https://github.com/funkyremi/vscode-google-translate)
