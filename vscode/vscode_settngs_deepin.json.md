```json
{
  "terminal.integrated.rendererType": "dom", // 终端渲染模式
  "window.zoomLevel": 2,
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "sync.gist": "56470f8dc19f9f5972dc0503ffc3da09",
  "editor.suggestSelection": "first",
  "editor.rulers": [
    90,
    110
  ],
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.fontLigatures": true,
  "editor.fontFamily": "'Fira Code', 'Microsoft YaHei', 'monospace'",
  "editor.fontSize": 14,
  "editor.lineHeight": 20,
  // "editor.minimap.enabled": true,// 小地图
  "diffEditor.ignoreTrimWhitespace": false,
  "workbench.iconTheme": "vscode-icons",
  "workbench.startupEditor": "welcomePage",
  // 渲染字体
  "oneDarkPro.editorTheme": "onedarkPro",
  "oneDarkPro.bold": true,
  "terminal.integrated.fontFamily": "monospace",
  "[javascript]": {
    "editor.fontLigatures": "'ss02', 'ss19'",
    // "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  // 提示框
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  // git
  "git.autofetch": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "git.ignoreMissingGitWarning": false,
  // javascript
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
  ],
  // java
  "java.configuration.checkProjectSettingsExclusions": false,
  // php
  "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
  "php-cs-fixer.lastDownload": 1566926293981,
  // python
  "python.jediEnabled": false,
  "python.formatting.provider": "yapf", // 自动格式化pthon代码
  "python.linting.flake8Enabled": false, // flake8代码格式化标准
  "[python]": {
    "editor.defaultFormatter": "ms-python.python"
  }, // 快速移动
  "vim.sneak": true,
  "vim.incsearch": true,
  "vim.useSystemClipboard": true,
  "vim.hlsearch": true,
  "vim.leader": " ",
  // "vim.insertModeKeyBindings": [
  // {
  //   "before": [
  //     "j",
  //     "j"
  //   ],
  //   "after": [
  //     "<Esc>"
  //   ]
  // },
  // {
  //   "before": [
  //     "k",
  //     "k"
  //   ],
  //   "after": [
  //     "<Esc>"
  //   ]
  // },
  // {
  //   "before": [
  //     "l",
  //     "l"
  //   ],
  //   "after": [
  //     "<Esc>"
  //   ]
  // },
  // {
  //   "before": [
  //     "h",
  //     "h"
  //   ],
  //   "after": [
  //     "<Esc>"
  //   ]
  // }
  // ],
  "vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": [
        "<C-j>"
      ],
      "after": [
        "j",
        "j",
        "j"
      ]
    },
    {
      "before": [
        "C-k"
      ],
      "after": [
        "k",
        "k",
        "k"
      ]
    },
    {
      "before": [
        "C-h"
      ],
      "after": [
        "h",
        "h",
        "h"
      ]
    },
    {
      "before": [
        "C-l"
      ],
      "after": [
        "l",
        "l",
        "l"
      ]
    }
  ],
  // 取消绑定
  "vim.handleKeys": {
    "<C-a>": false,
    "<C-c>": false
  },
  // vim状态栏根据状态变色-太卡不要开
  // "vim.statusBarColorControl": true,
  // "vim.statusBarColors.insert": "#653030",
  // "vim.statusBarColors.normal": "#232221",
  // "vim.statusBarColors.visual": "#4c2968",
  // linux
  "terminal.integrated.shell.linux": "/usr/bin/zsh",
  // 非重要
  "vsicons.dontShowNewVersionMessage": true,
  "gitlens.advanced.messages": {
    "suppressLineUncommittedWarning": true
  },
  // 字典
  "cSpell.userWords": [
    "Wechat",
    "nodejieba"
  ],
  // 忽略搜索的文件夹
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true
  },
  // 忽略工程打开的文件夹
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "editor.tokenColorCustomizations": {
    "[One Dark Pro]": {},
    "comments": {
      // 设置字体样式 加粗 下划线 斜体等
      "fontStyle": "italic",
      // 设置字体颜色
      "foreground": "#5f9774"
    },
    // "keywords": { // 关键字
    //   "fontStyle": "bold"
    // },
    // "variables": { // 变量名
    //   "fontStyle": "bold"
    // },
    // "strings": { // 字符串
    //   "fontStyle": "bold"
    // },
    // "functions": { // 函数名
    //   "fontStyle": "bold"
    // },
    // "numbers": { // 数字
    //   "fontStyle": "bold"
    // }
  },
  // 插件配置
  "vim.easymotion": true,
  "update.mode": "none",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "files.autoGuessEncoding": false, // 自动猜编码方式
  "[c]": {
    "files.encoding": "gbk"
  },
  "[log]": {
    "files.encoding": "gbk"
  },
  "[batch]": {
    "files.encoding": "gbk"
  },
  "cSpell.language": "en-US,en-GB",
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "editor.formatOnSave": true,
  "workbench.colorTheme": "One Dark Pro",
}
```