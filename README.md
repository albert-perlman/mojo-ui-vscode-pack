# mojo UI
Dark theme, extensions, and settings that provide a minimal UI with convenient addons.

UI modifications can be used with any theme.

Copy to settings.json
```
"breadcrumbs.filePath": "last",
"window.menuBarVisibility": "toggle",
"window.title": "${activeEditorMedium}",
"editor.minimap.enabled": false,
"editor.overviewRulerBorder": false,
"editor.scrollBeyondLastColumn": 1,
"editor.cursorBlinking": "phase",
"editor.renderLineHighlight": "gutter",
"editor.suggest.showStatusBar": true,
"explorer.autoReveal": false,
"scm.countBadge": "off",
"workbench.colorTheme": "mojo",
"workbench.experimental.useCustomHover": true,
"workbench.activityBar.visible": false,
"autoHide.autoHideSideBar": false,
"autoHide.panelDelay": 0,
"autoHide.sideBarDelay": 0,
"autoHide.hideOnOpen": false,
"activitusbar.searchViewInPanel": true,
"activitusbar.views": [
    {
        "name": "explorer",
        "codicon": "explorer-view-icon"
    },
    {
        "name": "extensions",
        "codicon": "extensions-view-icon"
    }
],
"todohighlight.isCaseSensitive": false,
"todohighlight.keywords": [
"TODO"
],
"todohighlight.defaultStyle": {
    "color": "rgba(0,255,255,1.0)",
    "backgroundColor": "rgba(100,100,100,0.5)",
},
"bookmarks.label.suggestion": "suggestWhenSelectedOrLineWhenNoSelected",
"diffEditor.renderSideBySide": false,
"diffEditor.ignoreTrimWhitespace": false,
"gitlens.currentLine.enabled": false,
"gitlens.hovers.currentLine.over": "line",
"bracket-pair-colorizer-2.colors": [
    "LightSteelBlue"
],
"trailing-spaces.trimOnSave": true,
"trailing-spaces.backgroundColor": "rgba(100,100,100,0.3)",
"trailing-spaces.borderColor": "rgba(0,122,204,0.15)",
"opened-editors.openedEditors": false,
"opened-editors.copyFolderName": false,
"opened-editors.copyFileName": false,
"glassit.alpha": 245,
```