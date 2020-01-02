# VsCode-Setting
{
    "workbench.colorTheme": "Monokai",
    "powermode.enabled": true,
    "powermode.enableShake": false,
    "editor.lineHighlightBackground": "#1E1E1EAA",
    // 配置是否从更新通道接收自动更新。更改后需要重启。
    "workbench.activityBar.visible": true,
    "workbench.statusBar.visible": true,
    "vetur.format.defaultFormatter": {
        "html": "prettier",
        "css": "prettier",
        "postcss": "prettier",
        "scss": "prettier",
        "less": "prettier",
        "js": "prettier",
        "ts": "prettier",
        "stylus": "stylus-supremacy",
    },
    "editor.minimap.enabled": true,
    "sync.gist": "6549dccc60c44003e96aaad029a7d51a",
    "files.autoSave": "onFocusChange",
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe",
    "workbench.sideBar.location": "left",
    "workbench.startupEditor": "newUntitledFile",
    "[scss]": {
        "editor.defaultFormatter": "michelemelluso.code-beautifier"
    },
    "[javascript]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    "[html]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    "ycy.reminderViewIntervalInMinutes": 50,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "editor.fontSize": 16,
    "editor.wordWrap": "on",
    "editor.wordWrapColumn": 1000,
    "git.autofetch": true,
    "editor.detectIndentation": false,
    "editor.tabSize": 4,
    "vsicons.dontShowNewVersionMessage": true,
    "vetur.format.options.tabSize": 4,
    // tab 大小为2个空格
    // 100 列后换行
    "editor.wordWrapColumn": 180,
    // 保存时格式化
    "editor.formatOnSave": true,
    // 开启 vscode 文件路径导航
    "breadcrumbs.enabled": false,
    // prettier 设置语句末尾不加分号
    "prettier.semi": false,
    // prettier 设置强制单引号
    "prettier.singleQuote": true,
    // 选择 vue 文件中 template 的格式化工具
    "vetur.format.defaultFormatter.html": "prettyhtml",
    // 显示 markdown 中英文切换时产生的特殊字符
    "editor.renderControlCharacters": true,
    // 设置 eslint 保存时自动修复
    "eslint.autoFixOnSave": true,
    // eslint 检测文件类型
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        {
            "language": "html",
            "autoFix": true
        }
    ],
    // vetur 的自定义设置
    "vetur.format.defaultFormatterOptions": {
        "prettier": {
            "singleQuote": true,
            "semi": false
        }
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    }
}
