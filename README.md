# contentstation-drag-to-indesign
This integration adds a custom button to the Dossier panel which can be dragged to InDesign. When dropped the selected files are placed or loaded in the InDesign place gun.

![Drag & drop in action](https://github.com/WoodWing/contentstation-drag-to-indesign/blob/master/drag-to-indesign.gif "Drag & drop in action")

# Configuration
Add dragToInDesign.js to the 'contentStation' section of the Content Station [config.js](https://helpcenter.woodwing.com/hc/en-us/articles/115005560243-Configuring-Content-Station-Aurora) 

# Note
* The plugin assumes that the server url returned by the Content Station SDK matches the server url configured for InDesign. Please update the createDragData funciton if this is not the case. 
* The text of the button and tooltip can be localised by changing the D2ID_LABEL and D2ID_HINT_TEXT constants
