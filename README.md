## My configuration: Visual Studio Code & Elixir

### Font

* Fira Code: https://github.com/tonsky/FiraCode
<img src="https://github.com/tonsky/FiraCode/blob/master/extras/logo.svg" />

### Plugins

* ElixirLS: Elixir support and debugger
* Elixir Templates Formatter
* EEx snippets
* Dark+ Elixir
* Beautify
* Material Icon Theme

### Settings
```json
{
    "window.zoomLevel": 2,
    "editor.cursorBlinking": "smooth",
    "workbench.iconTheme": "vscode-icons",
    "editor.suggestSelection": "first",
    "workbench.colorTheme": "dark+(elixir)",
    "editor.cursorStyle": "line",
    "editor.cursorSmoothCaretAnimation": true,
    "editor.cursorWidth": 3,
    "editor.fontSize": 11.5,
    "editor.fontFamily": "'Fira Code', Monaco, Menlo, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "beautify.language": {
        "js": [],
        "css": [],
        "html": [
            "html-eex"
        ]
    },
    "files.associations": {
        "*.ex": "elixir",
        "*.exs": "elixir",
        "*.eex": "eex",
        "*.leex": "html-eex",
        "*.html.eex": "html"
    },
    "[html-eex]": {
        "editor.trimAutoWhitespace": false,
        "files.trimTrailingWhitespace": true,
        "files.insertFinalNewline": true,
        "files.trimFinalNewlines": true,
        "editor.defaultFormatter": "HookyQR.beautify" // EXTENSION: Beautify
    },
    "emmet.includeLanguages": {
        "html-eex": "html"
    },
    "vscode-eex-format.tabStops": 2,
    "vscode-eex-format.tab": false,
    "vscode-eex-format.indentBy": 0,
    "vscode-eex-format.stopOnErrors": false,
    "vscode-eex-format.keepBlankLines": 0,
    "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.cursorWidth": 2,
    "terminal.integrated.cursorBlinking": true
}
```
