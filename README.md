# mojo UI
**IMPORTANT:** to complete installation, copy UI settings in the [Setup](#setup) section. <br>

[Keybindings](#keybindings)<br/>
[Activitus Bar](#activitus-bar)<br/>
[Setup](#setup)<br/>

## Overview
Dark theme, extensions, and settings that provide a minimal UI with convenient addons.<br/>
mojo UI extensions and settings can be used with any theme.<br/>

![image](https://user-images.githubusercontent.com/53355129/125361858-280d6f00-e32b-11eb-8a7c-600d1c574ec4.png)
<br/>
## Keybindings
function | shortcut
-------- | -----
open settings | ctrl/cmd + ,
show/hide panel | ctrl/cmd + j
show/hide sidebar | ctrl/cmd + b
show/hide menu bar | alt
search in files |ctrl/cmd + shift + f

## Activitus Bar
Open the Explorer and Extensions sidebar using the icons on the far left of the status bar. To add other activity bar icons to the status bar see [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar) configuration.

![image](https://user-images.githubusercontent.com/53355129/118390850-8dc0d180-b5ee-11eb-80f3-120270e06bfd.png)

## Setup
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
"editor.renderIndentGuides": false,
"editor.suggest.showStatusBar": true,
"editor.bracketPairColorization.enabled": true,
"editor.guides.bracketPairs": "active",
"editor.guides.indentation": false,
"explorer.autoReveal": false,
"scm.countBadge": "off",
"workbench.colorTheme": "mojo",
"workbench.experimental.useCustomHover": true,
"workbench.activityBar.visible": false,
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
"diffEditor.renderSideBySide": false,
"gitlens.currentLine.enabled": false,
"gitlens.hovers.currentLine.over": "line",
"gitlens.codeLens.authors.enabled": false,
"gitlens.codeLens.recentChange.enabled": false,
"bracket-pair-colorizer-2.colors": [
    "LightSteelBlue"
],
"trailing-spaces.trimOnSave": true,
"trailing-spaces.backgroundColor": "rgba(55,55,55,0.3)",
"trailing-spaces.borderColor": "rgba(30,30,30,0.15)",
"opened-editors.openedEditors": false,
"opened-editors.copyFolderName": false,
"opened-editors.copyFileName": false,
"workbench.colorCustomizations": {

    "editorBracketHighlight.foreground1": "#abb2c0",
    "editorBracketHighlight.foreground2": "#abb2c0",
    "editorBracketHighlight.foreground3": "#abb2c0",
    "editorBracketHighlight.foreground4": "#abb2c0",
    "editorBracketHighlight.foreground5": "#abb2c0",
    "editorBracketHighlight.foreground6": "#abb2c0",
    "editorBracketHighlight.unexpectedBracket.foreground": "#db6165"
},
```