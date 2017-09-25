# Visual Studio Code 个性化配置

## TOC

- [Font Setting](#font-setting)
- [Markdown Preview](#markdown-preview)
- [Extensions](./vscode-extensions.md)
- [License](#license)

## Font Setting

选择字体 --> [https://github.com/rocj/fonts-for-coder](https://github.com/rocj/fonts-for-coder)

```
//settings.json
{
    // 控制字体系列。
    "editor.fontFamily": "'Droid Sans Mono', 'Courier New', monospace, 'Droid Sans Fallback'",

    // 以像素为单位控制字号。
    "editor.fontSize": 14
}
```

## Markdown Preview

选择渲染样式 --> [./vscode-markdown-css/](https://github.com/rocj/vscode-settings/tree/master/vscode-markdown-css)

* [Github Markdown Style](./vscode-markdown-css/markdown-github.css)

```
//settings.json
{
    // 要在 Markdown 预览中使用的 CSS 样式表的 URL 或本地路径列表。相对路径被解释为相对于资源管理器中打开的文件夹。如果没有任何打开的文件夹，则会被解释为相对于 Markdown 文件的位置。所有的 "\" 需写为 "\\"。
    "markdown.styles": [
        "<folder-path>/vscode-markdown-css/markdown-github.css"
    ],

    // 设置换行符如何在 markdown 预览中呈现。将其设置为 "true" 会为每一个新行创建一个 <br>。
    "markdown.preview.breaks": true
}
```

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.