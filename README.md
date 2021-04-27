# VS Code Settings

# Font

- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

## Themes/Color

- Current theme:
  - [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
- Icon Theme:
  - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

## IntelliSense/AutoComplete

- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  - HTML CSS Classes intellisense
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  - Autocompletes npm modules in import/require statements
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  - Autocompletes filenames
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  - Vue tooling

## Style/Formatting

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - Integrates ESLint JS
- [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  - Automatically format javascript, JSON, CSS, Sass, and HTML files.
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - Code formatter (optional, i'm not using this all times.)

# Settings

```json
{
  "explorer.openEditors.visible": 0,
  "editor.snippetSuggestions": "top",
  "emmet.showAbbreviationSuggestions": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "workbench.colorTheme": "Just Black",
  "window.zoomLevel": 1,
  "workbench.iconTheme": "vscode-icons",
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 24,
  "files.autoSave": "off",
  "editor.fontFamily": "Anonymous Pro",
  "markdown.preview.fontSize": 36,
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.minimap.enabled": false,
  "eslint.enable": true,
  // "files.exclude": { "**/.*": true },
  "eslint.validate": [
    {
      "language": "vue",
      "autoFix": true
    },
    {
      "language": "typescript",
      "autoFix": true
    },
    {
      "language": "html",
      "autoFix": true
    },
    {
      "language": "javascript",
      "autoFix": true
    }
  ],
  "workbench.startupEditor": "newUntitledFile",
  "editor.suggestSelection": "first",
  "[javascript]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[json]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[html]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[css]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "liveshare.featureSet": "insiders",
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveshare.anonymousGuestApproval": "accept",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.colorCustomizations": {},
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["comment", "comment.block"],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },
  "todo-tree.tree.showScanModeButton": false,
  "cSpell.userWords": [
    "deno",
    "feathersjs",
    "middlewares",
    "socketio",
    "upsert",
    "upvote"
  ],
  "editor.lineHeight": 0,
  "editor.fontSize": 27
}
```
