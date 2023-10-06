# vscode_settings
recommendations for setting up vs code

## .vscode/settings.json

```
{
    "ansible.python.interpreterPath": "/home/arenadata/projects/bundles/adcm_cluster_hadoop/.venv/bin/python",
    "yaml.format.enable": true,
    "ansibleServer.trace.server": "verbose",
    "ansible.ansible.reuseTerminal": true,
    "ansible.ansible.useFullyQualifiedCollectionNames": false,
    "ansible.validation.lint.enabled": false,
    "workbench.startupEditor": "none",
    "workbench.iconTheme": "material-icon-theme",
    "redhat.telemetry.enabled": false,
    // https://wiki.adsw.io/books/qa-bundles/page/configure-vscode-to-develop-and-run-tests-run-pytest-in-gui
    "git.confirmSync": false,
    "python.testing.pytestEnabled": true,
    "python.testing.unittestArgs": [],
    "python.testing.autoTestDiscoverOnSaveEnabled": false,
    "python.testing.pytestArgs": [],
    // https://wiki.adsw.io/books/bundles/page/vscode-settings
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    // VISUAL
    "editor.fontSize": 13,
    "editor.suggestFontSize": 6,
    "markdown.preview.fontSize": 0,
    "terminal.integrated.fontSize": 12,
    "window.zoomLevel": 0,
    "workbench.sideBar.location": "left",
    "editor.mouseWheelZoom": true
}

```
## .vscode/extensions.json

```
{
    "recommendations": [
        "redhat.ansible"
    ]
}
```
