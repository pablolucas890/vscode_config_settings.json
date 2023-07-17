# vscode_config_settings.json
---
### Configurações do arquivo Settings.json do Visual Studio Code:
---
```javascript
{
    // Editor
    "editor.fontSize": 14,
    "editor.tabSize": 2,
    "editor.lineHeight": 22,
    "editor.fontLigatures": true,
    "editor.renderWhitespace": "all",
    "editor.inlineSuggest.enabled": true,
    "explorer.confirmDragAndDrop": false,
    "extensions.ignoreRecommendations": true,
    "explorer.confirmDelete": false,
    "editor.semanticHighlighting.enabled": false,
    "workbench.editor.labelFormat": "short",
    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
    "editor.rulers": [
        91,
        120
    ],
    "workbench.startupEditor": "newUntitledFile",
    "editor.lineNumbers": "on",
    // Terminal Linux
    "terminal.integrated.fontSize": 12,
    "terminal.external.linuxExec": "/usr/bin/fish",
    "terminal.integrated.shell.linux": "/usr/bin/fish",
    "terminal.integrated.env.linux": {
        "GTK_PATH": "/usr/bin/fish"
    },
    // Theme
    "workbench.colorTheme": "Dracula Purple",
    "workbench.iconTheme": "material-icon-theme",
    // Folders
    "explorer.compactFolders": false,
    "files.autoSaveDelay": 500,
    "files.trimTrailingWhitespace": true,
    "files.trimFinalNewlines": true,
    // Js and Ts
    "emmet.syntaxProfiles": {
        "javascript": "jsx"
    },
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true, 
            "source.organizeImports": true
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
            "source.organizeImports": true
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
            "source.organizeImports": true
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
            "source.organizeImports": true,
        },
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "terminal.integrated.fontFamily": "monospace",
    "diffEditor.ignoreTrimWhitespace": false,
    "git.enableSmartCommit": true,
    "terminal.integrated.enableMultiLinePasteWarning": false,
    "sync.autoDownload": true,
    "sync.autoUpload": true,
    "sync.forceDownload": true,
    "sync.forceUpload": true,
    "sync.quietSync": true,
    "sync.gist": "d41127f35e3e975755c2fb4c1870be06",
    "settingsSync.ignoredExtensions": [

    ],
    "[python]": {
        "editor.formatOnType": true
    },
    "git.openRepositoryInParentFolders": "never",
    "editor.minimap.enabled": false,
}
```
---
### Configurações do arquivo .eslintrc para projetos React Native:

```javascript
{
    "env": {
        "es2021": true,
        "node": true,
        "jest": true 
    },
    "extends": [
        "eslint:recommended",
        "plugin:@typescript-eslint/recommended",
        "prettier"
    ],
    "parser": "@typescript-eslint/parser",
    "parserOptions": {
        "ecmaVersion": "latest",
        "sourceType": "module"
    },
    "plugins": [
        "react", "react-hooks", "@typescript-eslint", "prettier"
    ],
    "rules": {
        "linebreak-style": [
            "error",
            "unix"
        ],
        "quotes": [
            "error",
            "single"
        ],
        "semi": [
            "error",
            "always"
        ],
        "no-dupe-else-if": "error",
        "spaced-comment": "error",
        "no-duplicate-imports": "error",
        "camelcase": "error",
        "react/react-in-jsx-scope": "off"
    },
    "settings": {
        "import/resolver": {
            "typescript": {}
        }
    }
}
```

### Configurações do arquivo .prettierrc para projetos React Native:

```javascript
{
  "semi": true,
  "tabWidth": 2,
  "printWidth": 120,
  "singleQuote": true,
  "trailingComma": "all",
  "jsxSingleQuote": true,
  "bracketSpacing": true,
  "bracketSameLine": false,
  "arrowParens": "avoid",
  "htmlWhitespaceSensitivity": "ignore"
}
```
