### My VS Code Settings  :heart:

#### Version1
1. Font -> [Victor Mono](https://github.com/rubjo/victor-mono) 
2. Theme -> [Ariake Dark](https://marketplace.visualstudio.com/items?itemName=wart.ariake-dark#review-details)
3. Icon -> [Seedling Icon Theme](https://marketplace.visualstudio.com/items?itemName=rastikerdar.vscode-seedling-icon-theme)
4. Setting
```json
{ 
    "workbench.colorTheme": "Ariake Dark",
    "workbench.colorCustomizations": {
        "statusBar.background": "#111518",
        "statusBar.noFolderBackground": "#111518",
        "statusBar.debuggingBackground": "#111518",
        "editor.background": "#1c1f26", 
        "tab.activeBackground":"#191c22", 
    },
    "editor.tabSize": 4,
    "editor.insertSpaces": true,
    "editor.detectIndentation": false,
    "editor.fontFamily": "'Victor Mono', monospace",
    "editor.fontLigatures": true,
    "workbench.iconTheme": "vscode-seedling-icon-theme"
}
```
5.Demo  :kissing_heart:  :kissing_heart:

![](https://i.imgur.com/XfnMko8.png)

#### Version2
```json
{
    "editor.fontFamily": "'Operator Mono Lig', monospace",
    "workbench.colorCustomizations": {
        "statusBar.background": "#0d0e0f",
        "statusBar.noFolderBackground": "#0d0e0f",
        "statusBar.debuggingBackground": "#0d0e0f",
        "contrastBorder": "#1A1C231A"
    },
    "window.zoomLevel": 0.8,
    "editor.fontLigatures": true,
    "editor.fontWeight": "300",
    "workbench.iconTheme": "vscode-seedling-icon-theme",
    "workbench.colorTheme": "CodeSandbox",
    "editor.fontSize": 15,
    "atomKeymap.promptV3Features": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.formatOnPaste": true,
    "editor.lineHeight": 23
}
```
### Version3
```json
{
   "editor.fontSize": 16,
   "editor.fontFamily": "'Operator Mono Lig'", //Operator Mono Lig // Dank Mono // Victor Mono // Ubuntu Mono
   "workbench.colorCustomizations": {
      "statusBar.background": "#0d0e0f",
      "statusBar.noFolderBackground": "#0d0e0f",
      "statusBar.debuggingBackground": "#0d0e0f",
      "contrastBorder": "#1A1C231A"
   },
   "window.zoomLevel": 0,
   "editor.fontLigatures": true,
   "editor.fontWeight": "200",
   "workbench.iconTheme": "seti",
   "editor.lineHeight": 30, // 24
   "editor.insertSpaces": true,
   "editor.detectIndentation": false,
   "editor.multiCursorModifier": "ctrlCmd",
   "editor.formatOnPaste": true,
   // performance vscode
   "telemetry.enableTelemetry": false,
   "files.exclude": {
      "**/.git": true,
      "**/.DS_Store": true,
      "**/.vscode": true,
      "**/__pycache__": true,
      "**/.pytest_cache": true,
      "**/node_modules": true,
      "node_modules": true,
      "venv": true,
      "*.sublime-*": true,
      "env*": true
   },
   "search.exclude": {
      "**/node_modules": true,
      "**/bower_components": true,
      "**/env": true,
      "**/venv": true
   },
   "files.watcherExclude": {
      "**/.git/objects/**": true,
      "**/.git/subtree-cache/**": true,
      "**/node_modules/**": true,
      "**/env/**": true,
      "**/venv/**": true,
      "env-*": true
   },
   "workbench.colorTheme": "CodeSandbox Black",
   "editor.tabSize": 3,
   "editor.formatOnSave": true
}
```
### Demo
![](https://i.imgur.com/p9VqswV.png)

### Version4
```
{
  "editor.fontSize": 14,
  "editor.letterSpacing": 0.5,
  "editor.fontLigatures": true,
  "editor.fontWeight": "normal",
  "editor.lineHeight": 26, // 24
  "editor.fontFamily": "OperatorMonoSSmLig-Light",
  "workbench.colorCustomizations": {
    "statusBar.background": "#0d0e0f",
    "statusBar.noFolderBackground": "#0d0e0f",
    "statusBar.debuggingBackground": "#0d0e0f",
    "contrastBorder": "#1A1C231A",
    // change color cursor
    "editorCursor.foreground": "#cccccc"
  },
  // setting Vibracy
  "vscode_vibrancy.opacity": 0,
  "editor.semanticHighlighting.enabled": false,
  //fase
  // emmet config
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "vue-html": "html",
    "javascript": "javascriptreact"
  },
  "emmet.triggerExpansionOnTab": true,
  // eslint
  "eslint.format.enable": true,
  // auto open new tab in vscode
  "workbench.editor.enablePreview": false,
  // disable warning plint
  "python.pythonPath": "/Users/quoctrung163/opt/miniconda3/envs/tensorflow/bin/python",
  "python.linting.pylintPath": "venv/bin/pylint",
  // Editor Tweak
  "files.eol": "\n",
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.renderWhitespace": "none",
  // TS lint
  "tslint.autoFixOnSave": true,
  // Git Lens
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },
  "gitlens.hovers.enabled": false,
  "gitlens.codeLens.enabled": false,
  "gitlens.statusBar.enabled": false,
  "gitlens.currentLine.enabled": false,
  "gitlens.blame.heatmap.enabled": false,
  "gitlens.mode.statusBar.enabled": false,
  "gitlens.blame.highlight.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  // Vetur
  "vetur.format.defaultFormatter.ts": "prettier",
  "vetur.format.defaultFormatter.js": "prettier",
  "vetur.format.defaultFormatter.css": "prettier",
  "vetur.format.defaultFormatter.less": "prettier",
  "vetur.format.defaultFormatter.scss": "prettier",
  "vetur.format.defaultFormatter.postcss": "prettier",
  "vetur.format.defaultFormatter.stylus": "stylus-supremacy",
  // System
  "window.zoomLevel": 0,
  "editor.detectIndentation": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": true,
  // performance vscode
  "telemetry.enableTelemetry": false,
  "files.exclude": {
    "**/.git": true,
    "**/.DS_Store": true,
    "**/.vscode": true,
    "**/__pycache__": true,
    "**/.pytest_cache": true,
    "**/node_modules": true,
    "node_modules": true,
    "venv": true,
    "*.sublime-*": true,
    "env*": true
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/env": true,
    "**/venv": true
  },
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/**": true,
    "**/env/**": true,
    "**/venv/**": true,
    "env-*": true
  },
  "editor.semanticTokenColorCustomizations": {
    "enabled": true
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "terminal.integrated.rendererType": "dom",
  "editor.formatOnType": true,
  "editor.formatOnSave": true,
  "terminal.integrated.inheritEnv": false,
  "files.associations": {
    "*.extension": "html"
  },
  "workbench.iconTheme": "vscode-seedling-icon-theme",
  "background.enabled": true,
  // Default Style BG
  // "background.style": {
  //   "content": "''",
  //   "pointer-events": "none",
  //   "position": "absolute",
  //   "z-index": "99999",
  //   "width": "100%",
  //   "height": "100%",
  //   "background-position": "100% 100%",
  //   "background-repeat": "no-repeat",
  //   "opacity": 1
  // },
  "background.useDefault": true,
  // "background.style": {
  //   "content": "''",
  //   "pointer-events": "none",
  //   "position": "absolute",
  //   "z-index": "99999",
  //   "width": "100%",
  //   "height": "100%",
  //   "background-position": "100% 35%",
  //   "background-repeat": "no-repeat",
  //   "opacity": 0.2
  // },
  "background.customImages": [
    "https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/ab07cff4-2b34-45e1-ab53-e8fb9517aa9a/dd9jrsv-809a44fd-d63f-4a80-bdcd-1e532e48dcad.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvYWIwN2NmZjQtMmIzNC00NWUxLWFiNTMtZThmYjk1MTdhYTlhXC9kZDlqcnN2LTgwOWE0NGZkLWQ2M2YtNGE4MC1iZGNkLTFlNTMyZTQ4ZGNhZC5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.ncWCy48oZ-qNbVQwReWNaykjE9xr1wXctpP2wpJDdJs",
    "https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/ab07cff4-2b34-45e1-ab53-e8fb9517aa9a/dd9jrsv-809a44fd-d63f-4a80-bdcd-1e532e48dcad.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvYWIwN2NmZjQtMmIzNC00NWUxLWFiNTMtZThmYjk1MTdhYTlhXC9kZDlqcnN2LTgwOWE0NGZkLWQ2M2YtNGE4MC1iZGNkLTFlNTMyZTQ4ZGNhZC5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.ncWCy48oZ-qNbVQwReWNaykjE9xr1wXctpP2wpJDdJs"
  ],
  "workbench.colorTheme": "CodeSandbox",
  // Decoration color for packages
  "importCost.smallPackageColor": "#c36e6e",
  "importCost.mediumPackageColor": "#c36e6e",
  "importCost.largePackageColor": "#d23b2c",
}
```
## Extention
- Atom One Dark Theme
- Auto Close Tag
- Babel Javascript
- Beautify css/sass/scss/less
- Better Comment
- Bracket Pair Colorize2
- CodeSandBox theme
- DotENV
- Elm Emmet
- ESLint
- GitLens - Git supercharged
- Live Server
- Markdown Preview Enhanced
- Path Intellisense
- Python
- Python for Vscode
- Seedling Icon Theme
- TSLint
- Vetur
- Background Video
