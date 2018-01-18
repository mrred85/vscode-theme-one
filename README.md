# One Dark and One Light themes for Visual Studio Code

Port of One Dark and One Light themes for VS Code.

## Syntax
- HTML
- Apache
- PHP
- Python
- Ruby
- Java
- JavaScript
- TypeScript
- CSS / SCSS
- SQL
- XML
- Markdown
- and so on

### How to install
Download files and place in `~/.vscode/extensions` folder.
Go to `Preferences > Color Theme` and select `One Dark` or `One Light` to load it.

### Indenticator plugin

If you use *Indenticator* plugin set below values in user settings, `settings.json`, to set active gutters colors.

```JSON
"indenticator.color.dark": "#9399be",
"indenticator.color.light": "#696c77"
```

### TODO Highlight plugin

If you use *TODO Highlight* set below values in user settings, `settings.json` to integrate `TODO:`, `@todo:` and `@TODO:` background colors with this theme.
This setting remove case sensitive check for a better integration with existing code syntaxes.
To color the whole line set `todohighlight.highlightWholeLine` to `true`.

### One Dark

```JSON
"todohighlight.isCaseSensitive": false,
"todohighlight.keywords": [
    {"text": "TODO:", "color": "#fafafa", "backgroundColor": "#50a14f", "overviewRulerColor": "#50a14f"},
    {"text": "FIXME:", "color": "#fafafa", "backgroundColor": "#d19a66", "overviewRulerColor": "#d19a66"},
    {"text": "NOTE:", "color": "#fafafa", "backgroundColor": "#61afef", "overviewRulerColor": "#61afef"},
    {"text": "BUG:", "color": "#fafafa", "backgroundColor": "#df6a73", "overviewRulerColor": "#df6a73"},
    {"text": "IMPORTANT:", "color": "#fafafa", "backgroundColor": "#c678dd", "overviewRulerColor": "#c678dd"}
]
```

### One Light

```JSON
"todohighlight.isCaseSensitive": false,
"todohighlight.keywords": [
    {"text": "TODO:", "color": "#fafafa", "backgroundColor": "#50a14f", "overviewRulerColor": "#50a14f"},
    {"text": "FIXME:", "color": "#fafafa", "backgroundColor": "#986801", "overviewRulerColor": "#986801"},
    {"text": "NOTE:", "color": "#fafafa", "backgroundColor": "#0184bc", "overviewRulerColor": "#0184bc"},
    {"text": "BUG:", "color": "#fafafa", "backgroundColor": "#e06c75", "overviewRulerColor": "#e06c75"},
    {"text": "IMPORTANT:", "color": "#fafafa", "backgroundColor": "#a626a4", "overviewRulerColor": "#a626a4"}
]
```

### Git Lens plugin

If you use *Git Lens* set below values in user settings, `settings.json` to integrate with this theme.

```JSON
"gitlens.insiders": true,
"gitlens.theme.annotations.file.gutter.dark.backgroundColor": "rgba(54, 58, 79, 0.6)",
"gitlens.theme.annotations.file.gutter.light.backgroundColor": "rgba(210, 211, 212, 0.6)",
"gitlens.theme.annotations.file.gutter.dark.foregroundColor": "rgb(214, 228, 254)",
"gitlens.theme.annotations.file.gutter.light.foregroundColor": "rgb(56, 58, 66)",
"gitlens.theme.annotations.file.gutter.dark.uncommittedForegroundColor": "rgb(209, 154, 102)",
"gitlens.theme.annotations.file.gutter.light.uncommittedForegroundColor": "rgb(152, 104, 1)",
"gitlens.theme.annotations.line.trailing.dark.backgroundColor": "",
"gitlens.theme.annotations.line.trailing.light.backgroundColor": "",
"gitlens.theme.annotations.line.trailing.dark.foregroundColor": "rgb(209, 154, 102)",
"gitlens.theme.annotations.line.trailing.light.foregroundColor": "rgb(152, 104, 1)",
"gitlens.theme.lineHighlight.dark.backgroundColor": "rgba(97, 175, 239, 0.3)",
"gitlens.theme.lineHighlight.light.backgroundColor": "rgba(64, 120, 242, 0.4)",
"gitlens.theme.lineHighlight.dark.overviewRulerColor": "rgba(97, 175, 239, 0.3)",
"gitlens.theme.lineHighlight.light.overviewRulerColor": "rgba(64, 120, 242, 0.4)",
```

Enjoy ;)
