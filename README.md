### My VS Code Settings  :heart:
```
{
  "editor.fontSize": 14,
  "editor.letterSpacing": 0.1,
  "editor.fontLigatures": true,
  "editor.fontWeight": "100",
  "editor.lineHeight": 28, // 24
  "editor.fontFamily": "OperatorMonoSSmLig-Light",
  // version normal
  // "workbench.colorCustomizations": {
  //   "statusBar.background": "#0d0e0f",
  //   "statusBar.noFolderBackground": "#0d0e0f",
  //   "statusBar.debuggingBackground": "#0d0e0f",
  //   "contrastBorder": "#1A1C231A",
  //   // change color cursor
  //   "editorCursor.foreground": "#cccccc"
  // },
  // version dark
  "workbench.colorCustomizations": {
    // "statusBar.background": "#0d0e0f",
    // "statusBar.noFolderBackground": "#0d0e0f",
    // "statusBar.debuggingBackground": "#0d0e0f",
    // "contrastBorder": "#1A1C231A",
    "statusBar.background": "#0d0e0f",
    "statusBar.noFolderBackground": "#0d0e0f",
    "statusBar.debuggingBackground": "#0d0e0f",
    "contrastBorder": "#1A1C231A",
    // change color cursor
    "editorCursor.foreground": "#cccccc",
    // change color border highlightBorder
    "editor.lineHighlightBorder": "#141718",
    // change theme color
    "sideBar.background": "#141718",
    // "sideBarSectionHeader.background": "#ff0000",
    // "sideBar.border": "#ff0000",
    // "sideBar.dropBackground": "#ff0000",
    // "sideBar.foreground": "#fff",
    // "sideBarTitle.foreground": "#ff0000",
    // "sideBarSectionHeader.border": "#ff0000",
    // "sideBarSectionHeader.foreground": "#ff0000",
    // "minimapSlider.activeBackground": "#ff0000",
    // "activityBar.activeFocusBorder": "#ff0000",
    "list.hoverBackground": "#191B1D",
    "list.activeSelectionBackground": "#191B1D",
    // "list.activeSelectionForeground": "#ff0000",
    // "list.highlightForeground": "#ff0000",
    "list.inactiveSelectionBackground": "#191B1D",
    //
    "tab.activeBackground": "#141718",
    "tab.activeBorder": "#A7A8A8",
    "tab.unfocusedActiveBorder": "#141718",
    "tab.inactiveBackground": "#141718",
    //
    //
    "editor.background": "#141718",
    "terminal.background": "#141718",
    "panel.background": "#141718",
    "panelTitle.activeBorder": "#A7A8A8",
    "activityBar.background": "#141718"
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
  // "python.linting.pylintPath": "venv/bin/pylint",
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
  // "importCost.smallPackageColor": "#c36e6e",
  // "importCost.mediumPackageColor": "#c36e6e",
  // "importCost.largePackageColor": "#d23b2c",
  "python.defaultInterpreterPath": "/Users/quoctrung163/.pyenv/shims/python3",
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  /* custom css */
  "vscode_custom_css.imports": [
    "file:///Users/quoctrung163/Documents/Design/Vscode/custom.css"
  ],
  "vscode_custom_css.policy": true,
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
