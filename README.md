# vscode_config_settings.json
---
### Configurações do arquivo Settings.json do Visual Studio Code:
---
```javascript
{
    "editor.fontSize": 14,
    "editor.tabSize": 2,
    "editor.lineHeight": 1.8,
    "editor.fontLigatures": true,
    "editor.renderWhitespace": "all",
    "editor.renderLineHighlight": "gutter",
    "editor.inlineSuggest.enabled": true,
    "explorer.confirmDragAndDrop": false,
    "extensions.ignoreRecommendations": true,
    "explorer.confirmDelete": false,
    "editor.semanticHighlighting.enabled": false,
    "workbench.editor.labelFormat": "short",
    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
    "editor.minimap.enabled": false,
    "editor.scrollbar.horizontal": "hidden",
    "editor.scrollbar.vertical": "hidden",
    "workbench.statusBar.visible": false,
    "editor.rulers": [
        80,
        120
    ],
    "workbench.startupEditor": "newUntitledFile",
    "workbench.activityBar.orientation": "horizontal",
    "editor.lineNumbers": "on",
    "terminal.integrated.fontSize": 12,
    "terminal.external.linuxExec": "/usr/bin/fish",
    "terminal.integrated.env.linux": {
        "GTK_PATH": "/usr/bin/fish"
    },
    "terminal.integrated.defaultProfile.linux": "fish",
    "terminal.integrated.profiles.linux": {
        "fish": {
            "path": "/usr/bin/fish"
        }
    },
    "terminal.integrated.automationProfile.linux": "fish",
    "workbench.colorTheme": "Dracula Refined",
    "workbench.iconTheme": "material-icon-theme",
    "explorer.compactFolders": false,
    "files.autoSaveDelay": 500,
    "files.trimTrailingWhitespace": false,
    "files.trimFinalNewlines": true,
    "emmet.syntaxProfiles": {
        "javascript": "jsx"
    },
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit",
            "source.organizeImports": "explicit"
        },
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit",
            "source.organizeImports": "explicit"
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit",
            "source.organizeImports": "explicit"
        },
        "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit",
            "source.organizeImports": "explicit"
        },
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "terminal.integrated.fontFamily": "",
    "window.titleBarStyle": "native",
    "diffEditor.ignoreTrimWhitespace": false,
    "git.enableSmartCommit": true,
    "terminal.integrated.enableMultiLinePasteWarning": "never",
    "sync.autoDownload": true,
    "sync.autoUpload": true,
    "sync.forceDownload": true,
    "sync.forceUpload": true,
    "sync.quietSync": true,
    "sync.gist": "d41127f35e3e975755c2fb4c1870be06",
    "settingsSync.ignoredExtensions": [],
    "[python]": {
        "editor.defaultFormatter": "ms-python.black-formatter",
        "editor.formatOnSave": false
    },
    "git.openRepositoryInParentFolders": "never",
    "[json]": {
        "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    },
    "[html]": {
        "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    },
    "[javascriptreact][typescript][typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit",
            "source.organizeImports": "explicit"
        }
    },
    "editor.unicodeHighlight.invisibleCharacters": false,
    "workbench.editor.enablePreview": false,
    "prisma.showPrismaDataPlatformNotification": false,
    "github.copilot.editor.enableAutoCompletions": true,
    "explorer.fileNesting.patterns": {
        "*.ts": "${capture}.js",
        "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
        "*.jsx": "${capture}.js",
        "*.tsx": "${capture}.ts",
        "tsconfig.json": "tsconfig.*.json",
        "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
        "*.sqlite": "${capture}.${extname}-*",
        "*.db": "${capture}.${extname}-*",
        "*.sqlite3": "${capture}.${extname}-*",
        "*.db3": "${capture}.${extname}-*",
        "*.sdb": "${capture}.${extname}-*",
        "*.s3db": "${capture}.${extname}-*"
    },
    "[scss]": {
        "editor.defaultFormatter": "vscode.css-language-features"
    },
    "window.customTitleBarVisibility": "auto",
    "workbench.activityBar.location": "hidden",
    "editor.fontFamily": "JetBrains Mono",
    "window.menuBarVisibility": "compact",
    "workbench.layoutControl.enabled": false
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
