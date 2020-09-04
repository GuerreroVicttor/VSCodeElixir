## My configuration: Visual Studio Code and Elixir

### Font

* Fira Code: https://github.com/tonsky/FiraCode
<img src="https://github.com/tonsky/FiraCode/blob/master/extras/logo.svg" />

### Plugins

* ElixirLS: Elixir support and debugger
* EEx snippets
* Dark+ Elixir
* Beautify
* Material Icon Theme

### Settings
```json
{
    "window.zoomLevel": 0,
    "editor.cursorBlinking": "smooth",
    "workbench.iconTheme": "material-icon-theme",
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
        "*.eex": "html-eex",
        "*.leex": "html-eex",
        "*.html.EEx": "html-eex"
    },
    "[html-eex]": {
        "editor.trimAutoWhitespace": false,
        "files.trimTrailingWhitespace": true,
        "files.insertFinalNewline": true,
        "files.trimFinalNewlines": true
    },
    "emmet.includeLanguages": {
        "html-eex": "html"
    },
    "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.cursorWidth": 2,
    "terminal.integrated.cursorBlinking": true
}
```
