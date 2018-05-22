# Visual Studio CheatSheet


## Useful Extensions

### HTML & CSS

* `CSScomb`: Codeing style formatter for CSS, Less, SCSS and Saas.

* `Puglint`: Linter and style checker for pug.

* `SCSS IntelliSense`: Advanced autocompletion and refactoring support for SCSS.

### JavaScript, Node & NPM

* `ESLint`: Integrates ESLint into VS Code

* `NPM`: NPM support for VS Code.

* `NPM Intellisense`: Visual Studio Code plugin that autocompletes NPM modules in import statements.

* `Version Lens`: Shows the latest version for each package using code lens.


### SPA

* `Vetur`: Vue tooling for VS Code.


### Miscellaneous

`Final-Newline`: Inserts a final newline when saving the document.

`Open in Github/Bitbucket...`: Jump to a source code line in Github / Bitbucket, Gitlab, VisualStudio.com

`OpenChrome`: Open file with Chrome.

`Output Colorizer`: Syntax Highlighting for log files.

`SVG Viewer`: SVG Viewer for Visual Studio Code.

`Terminal`: Terminal for Visual Studio Code.


##############################################################################
# USER SETTINGS
##############################################################################


```javascript
{
    // Controls the font size in pixels
    "editor.fontSize": 14,

    // Render vertical rulers after a certain number of
    // monospace characters. Use multiple values for multiple
    // rulers. No rulers are drawn if array is empty
    "editor.rulers": [100],

    // The number of spaces a tab is equal to
    "editor.tabSize": 2,

    "[python]": {
        "editor.tabSize": 4
    },

    // Controls the line height
    "editor.lineHeight": 22,

    // Controls the font family
    "editor.fontFamily": "Fira Code",

    // Enables font ligatures
    "editor.fontLigatures": true,

    // Controls whether snippets are shown with other suggestions and how they are sorted.
    "editor.snippetSuggestions": "top",

    // Ignore extension recommendations
    "extensions.ignoreRecommendations": false,

    // Controls auto save of dirty files
    "files.autoSave": "afterDelay",
  
    // Controls the delay in ms after which a dirty file is saved automatically
    "files.autoSaveDelay": 1000,

    // Configure glob patterns for excluding files and folders
    "files.exclude": {
        ".yarn": true,
        "**/*.pyc": true
    },

    // Insert a final new line at the end of the file when saving it
    "files.insertFinalNewline": true,

    // Confirm before synchronizing git repositories
    "git.confirmSync": false,

    // Commit all changes when there are no staged changes
    "git.enableSmartCommit": true,

    // Whether to lint Python files using pylint
    "python.linting.pylintEnabled": false,

    // Whether to lint Python files using flake8
    "python.linting.flake8Enabled": true,

    // Configure glob patterns for excluding files and folders in
    // searches. Inherits all glob patterns from the files.exclude setting.
    "search.exclude": {
        "**/.git": true,
        "**/.nuxt": true,
        "**/build": true,
        "**/data": true,
        "**/dist": true,
        "**/env": true
    },

    // Adjust the zoom level of the window. The original size is 0
    // and each increment above (e.g. 1) or below (e.g. -1) represents
    // zooming 20% larger or smaller. You can also enter decimals to
    // adjust the zoom level with a finer granularity.
    "window.zoomLevel": 0,

    // Overrides colors from the currently selected color theme.
    "workbench.colorCustomizations": {
        "statusBar.background": "#8252be",
        "statusBar.foreground": "#eeffff",
        "titleBar.activeBackground": "#282b3c",
        "titleBar.activeForeground": "#eeefff"
    },

    // Specifies the color theme used in the workbench
    "workbench.colorTheme": "Material Palenight",

    // Specifies the icon theme used in the workbench
    "workbench.iconTheme": "material-icon-theme",
  
    // Controls font aliasing method in the workbench
    "workbench.fontAliasing": "antialiased",
    "explorer.confirmDragAndDrop": false
}
```
