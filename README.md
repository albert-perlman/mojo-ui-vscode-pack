# mojo UI
[Keybindings](#keybindings)<br/>
[Activitus Bar](#activitus-bar)<br/>
[Setup](#setup)<br/>

## Overview
Dark theme, extensions, and settings that provide a minimal UI with convenient addons.<br/>
mojo UI extensions and settings can be used with any theme.

![image](https://user-images.githubusercontent.com/53355129/118393296-a4215a00-b5fb-11eb-9ae6-2fd245ed3da2.png)
transparency enabled
<br/><br/>
![image](https://user-images.githubusercontent.com/53355129/118392886-23615e80-b5f9-11eb-8413-5f8e4791b128.png)
transparency disabled
<br/>
## Keybindings
function | shortcut
-------- | -----
open settings | ctrl/cmd + ,
show/hide panel | ctrl/cmd + j
show/hide sidebar | ctrl/cmd + b
show/hide menu bar | alt
search in files |ctrl/cmd + shift + f
+/- transparency | ctrl + alt + z/c

## Activitus Bar
Open the Explorer and Extensions sidebar using the icons on the far left of the status bar. To add other activity bar icons to the status bar see [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar) configuration.

![image](https://user-images.githubusercontent.com/53355129/118390850-8dc0d180-b5ee-11eb-80f3-120270e06bfd.png)

## Setup
Recommended: drag-and-drop the Search pane from the sidebar to the bottom panel

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
"diffEditor.renderSideBySide": false,
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
"glassit.alpha": 255,
```