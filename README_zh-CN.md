# Vscode Google Translate Next

简体中文 | [English](./README.md)

[![Licence](https://img.shields.io/github/license/yxw007/vscode-google-translate.svg)](https://github.com/yxw007/vscode-google-translate)

<h1 style="color:red">特别说明：此插件将不再更新，请使用我们全新开发的插件: <a href="https://github.com/yxw007/vscode-translate-next">vscode-translate-next</a>，它提供了更多功能和更好的用户体验，完美替代vscode-google-translate</h1>


快速在您的代码中翻译文本 🚀


![Demo](demo.gif)

## 使用

### 翻译选定的文本

1. 选择一些文字进行翻译
2. 按 `ALT+SHIFT+T`
3. 选择您想要的输出语言并享受 👍

### 在光标下翻译一条线

此功能在当前的一个下插入一个Newline，并通过翻译

1.将光标/光标设置在线上以翻译
1.选择“光标下的翻译行”菜单'
1.选择您想要的输出语言并享受

## 首选语言设置

是否想快速转化为特定语言？
运行命令“ SET首选语言”或在VSCODE扩展设置中设置它

## 工具提示悬停翻译

默认情况下，当您悬停在评论和代码上时，您将转换为
您首选的语言徘徊在元素之上。如果您想关闭它
进入扩展设置和未检查的悬停转换，然后重新启动VSCODE。

## 代理设置

您可以使用代理将文本转换为具有以下设置：

```js
"vscodeGoogleTranslate.host": "120.0.0.1"       // Proxy disabled if empty
"vscodeGoogleTranslate.port": "8080"            // Proxy port
"vscodeGoogleTranslate.username": "admin"       // Proxy auth disabled if empty
"vscodeGoogleTranslate.password": "password"    // Proxy password
```

## Pull request

欢迎拉拉请求。分叉项目，克隆它，安装依赖项`npm i`并开始编码

如果要更改代码悬停翻译。请从根部运行"npm run compile"以编译打字稿
代码库的一部分。

非常感谢参与使它很棒的人！

## 特别感谢

- [funkyremi/vscode-google-translate](https://github.com/funkyremi/vscode-google-translate)
