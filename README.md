conf_vscode

* Intelephense

* PHP Namespace Resolver

* vscode-phpcs
    - composer global require squizlabs/php_codesniffer

* PHP CS Fixer for Visual Studio Code

* Material Icon Theme

*  File -> Preferences -> Settings -> settings.json
```
{
    "workbench.colorTheme": "Dracula",
    "window.zoomLevel": 0,
    "editor.rulers": [
        120
    ],
    "workbench.iconTheme": "material-icon-theme",
    "editor.letterSpacing": 0.7,
    "editor.lineHeight": 25,
    "editor.fontSize": 16,
    "editor.formatOnPaste": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "terminal.integrated.lineHeight": 1.4,
    "phpcs.standard": "PSR2",
    "namespaceResolver.sortAlphabetically": true,
    "namespaceResolver.sortOnSave": true,
    "php-cs-fixer.onsave": true,
    "[php]": {
        "editor.defaultFormatter": "junstyle.php-cs-fixer"
    },
    "editor.fontFamily": "'Fira Code'",
    "editor.fontLigatures": true,
}
```

* JetBrains-like Keymap for Visual Studio Code

* vscode-nb-keybinding

* GitLens