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
