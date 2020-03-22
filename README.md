# vscode-settings
settings.json file for vscode


```javascript
{
    "workbench.startupEditor": "newUntitledFile",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.formatOnSave": true,
    "window.zoomLevel": -2,
    "workbench.editor.highlightModifiedTabs": true,
    "editor.cursorStyle": "block",
    "editor.cursorBlinking": "smooth",
    "files.trimFinalNewlines": true,
    "editor.minimap.enabled": true,
    "breadcrumbs.enabled": false,
    "workbench.colorTheme": "Monokai",
    "editor.fontFamily": "Dank Mono",
    // "editor.fontSize": 12,
    "editor.fontWeight": "normal",
    "editor.fontLigatures": true,
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": [
                    //following will be in italic (=FlottFlott)
                    "comment",
                    "entity.name.type.class", //class names
                    "keyword", //import, export, return…
                    "constant", //String, Number, Boolean…, this, super
                    "storage.modifier", //static keyword
                    "storage.type.class.js", //class keyword
                ],
                "settings": {
                    "fontStyle": "italic"
                }
            },
            {
                "scope": [
                    //following will be excluded from italics (VSCode has some defaults for italics)
                    "invalid",
                    "keyword.operator",
                    "constant.numeric.css",
                    "keyword.other.unit.px.css",
                    "constant.numeric.decimal.js",
                    "constant.numeric.json"
                ],
                "settings": {
                    "fontStyle": ""
                }
            }
        ]
    },
    "editor.lineHeight": 31,
    "debug.console.lineHeight": 31
}
```
