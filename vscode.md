### setting.json
```
// // Place your settings in this file to overwrite the default settings
// {
//     "editor.tabSize": "2",
//     "editor.insertSpaces": true,
//     "files.eol": "\n",
//     "workbench.iconTheme": "material-icon-theme",
// }
{
    // ================
    // general settings
    // ================
    "debug.inlineValues": true,
    "debug.internalConsoleOptions": "openOnSessionStart",
    "debug.openDebug": "openOnSessionStart",
    "debug.toolBarLocation": "docked",

    "editor.acceptSuggestionOnCommitCharacter": true,
    "editor.cursorBlinking": "phase",
    "editor.dragAndDrop": false,
    "editor.find.autoFindInSelection": true,
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    // "editor.lineNumbers": "interval",
    "editor.minimap.maxColumn": 40,
    "editor.minimap.showSlider": "always",
    "editor.renderControlCharacters": true,
    "editor.renderLineHighlight": "all",
    "editor.renderWhitespace": "boundary",
    "editor.showFoldingControls": "always",
    // "editor.smoothScrolling": true,
    "editor.insertSpaces": true,

    "files.autoGuessEncoding": true,
    "files.defaultLanguage": "javascript",
    "files.eol": "\n",
    "files.hotExit": "onExitAndWindowClose",
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    // "files.trimTrailingWhitespace": true,

    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.enableBell": true,
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",

    "window.newWindowDimensions": "inherit",
    "window.restoreFullscreen": true,
    "window.zoomLevel": 0,

    // "workbench.editor.tabCloseButton": "left",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "none",

    // ===========================
    // language specified settings
    // ===========================
    "[git-commit]": {
      "editor.rulers": [
        100,
      ],
    },
    "[javascript]": {
      "editor.tabSize": 2,
    },
    "[javascriptreact]": {
      "editor.tabSize": 2,
    },
    "[json]": {
      "editor.tabSize": 2,
    },
    "[markdown]": {
      "editor.wordWrap": "off",
      "files.trimTrailingWhitespace": false,
    },
    "[typescript]": {
      "editor.tabSize": 2,
    },
    "[typescriptreact]": {
      "editor.tabSize": 2,
    },

    // ===================
    // extensions settings
    // ===================
    "gitlens.advanced.messages": {
      "suppressShowKeyBindingsNotice": true
    },
  "javascript.preferences.quoteStyle": "single",
  "typescript.preferences.quoteStyle": "single",
  "vsicons.projectDetection.autoReload": true,
}
```
