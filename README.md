# AposVSCode
My personal settings for vscode.

Those are the best settings in the world. If you don't agree, make an issue with your proposed changes and I will take them into consideration.

## Extensions

* AposTheme
* C#
* C# Extensions
* C# FixFormat
* C# XML Documentation Comments
* compareit
* Git History
* HTML CSS Support
* Material Theme
* MSBuild project tools
* NuGet Package Manager
* PHP Debug
* PHP IntelliSense
* Plastic
* Python
* Shader languages support for VS Code
* Spell Right
* To Do Tasks
* todo-txt
* Toggle CodeLens
* Vim
* vscode-icons
* vscode-solution-explorer
* yo

## User Settings

```json
// Place your settings in this file to overwrite the default settings
{
    "terminal.integrated.shell.windows": "C:\\Windows\\sysnative\\WindowsPowerShell\\v1.0\\powershell.exe",
    "editor.fontFamily": "iosevka",
    "editor.fontLigatures": true,
    "editor.fontSize": 18,
    "editor.wordWrap": "on",
    "editor.renderWhitespace": "all",
    "window.zoomLevel": 1,
    "terminal.integrated.fontSize": 22,
    "editor.renderControlCharacters": true,
    "editor.minimap.enabled": true,
    "vim.useSystemClipboard": true,
    "workbench.colorTheme": "AposTheme",
    "workbench.iconTheme": "vscode-icons",
    "editor.minimap.renderCharacters": false,
    "editor.minimap.showSlider": "always",
    "editor.quickSuggestions": {
        "other": true,
        "comments": false,
        "strings": true
    },
    "editor.snippetSuggestions": "none",
    "editor.quickSuggestionsDelay": 0,
    "editor.parameterHints.enabled": true,
    "editor.wordBasedSuggestions": true,
    "editor.detectIndentation": false,
    "editor.acceptSuggestionOnCommitCharacter": false,
    "editor.tabSize": 4,
    "editor.insertSpaces": true,
    "vsicons.dontShowNewVersionMessage": true,
    "git.autofetch": true,
    "git.confirmSync": false,
    "csharp.format.enable": false,
    "editor.formatOnPaste": true,
    "editor.codeLens": false,
    "editor.rulers": [
        120
    ],
    "workbench.colorCustomizations": {
        "editorGutter.background": "#090909",
    },
    "csharpfixformat.style.spaces.beforeParenthesis": false,
    "csharpfixformat.style.spaces.afterParenthesis": false,
    "python.pythonPath": "C:\\Python34\\python.exe",
    "python.linting.pylintEnabled": false,
    "window.titleBarStyle": "custom",
    "workbench.editor.enablePreview": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "debug.toolBarLocation": "docked",
    "debug.openDebug": "openOnDebugBreak",
    "typescript.tsc.autoDetect": "off",
    "csharp.suppressDotnetRestoreNotification": true,
    "csharp.suppressDotnetInstallWarning": true,
    "csharp.suppressProjectJsonWarning": true,
    "csharp.suppressHiddenDiagnostics": true,
    "omnisharp.disableMSBuildDiagnosticWarning": true,
    "spellright.language": [
        "en"
    ],
    "spellright.documentTypes": [
        "markdown",
        "latex",
        "plaintext",
        "csharp"
    ],
    "spellright.notificationClass": "information"
}
```
