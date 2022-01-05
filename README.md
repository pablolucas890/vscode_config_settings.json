# vscode_config_settings.json
Configurações do arquivo Settings.json do Visual Studio Code:
---
```javascript
{
    "terminal.integrated.fontSize": 14,
    "workbench.iconTheme": "material-icon-theme",
    "explorer.compactFolders": false,
    "emmet.syntaxProfiles": {"javascript": "jsx"},
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "editor.rulers": [91,120],
    "workbench.colorTheme": "Dracula",
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true, 
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true, 
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true, 
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true, 
        }
    },
    "explorer.confirmDragAndDrop": false,
    "extensions.ignoreRecommendations": true,
    "editor.renderWhitespace": "all"
}
``
