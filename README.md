# Settings and Keyborad shortcuts for my vs code editor

## keybindings:
    - `alt+t` map to terminal->Run Task
    - `alt+r alt+t` map to terminal->Restarting Running Task
    - `alt+s alt+t` map to terminal->Terminate Task

## Settings:
```json
{
    "workbench.statusBar.visible": true,
    "workbench.activityBar.visible": false,
    "workbench.colorTheme": "Nova",
    "workbench.iconTheme": "eq-material-theme-icons",
    "html.format.enable": true,
    "html.format.wrapLineLength": 79,
    "code-runner.executorMap": {
        "python": "python"
    },
    "editor.fontSize": 16,
    "editor.minimap.enabled": false,
    "editor.renderWhitespace": "all",
    "editor.renderControlCharacters": true,
    "editor.fontFamily": "'Source Code Pro', 'monospace'",
    "editor.rulers": [
        79
    ],
    "editor.formatOnSave": true,
    "python.formatting.yapfPath": "/usr/local/bin/yapf",
    "python.formatting.autopep8Path": "/usr/local/bin/autopep8",
    "python.formatting.provider": "autopep8",
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "terminal.integrated.fontSize": 16,
    "workbench.editor.enablePreview": false,
    "window.menuBarVisibility": "default",
    "terminal.integrated.rendererType": "dom",
    "window.zoomLevel": 0,
    "editor.formatOnPaste": true,
    "workbench.settings.editor": "json"
}
```
