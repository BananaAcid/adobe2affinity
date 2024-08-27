# Photoshop to Affinity Photo
Documentation on using photo - listing frequently asked questions when switching from Photoshop to Affinity Photo

**Please feel free to open a discussion, post issues and provide pull requests.**

FAQs on licensing and more is at Affinities forum https://forum.affinity.serif.com/

An overview off the UI and some examples (layers, masking, ...) can be found here: https://affinity.serif.com/learn/photo/desktop/quickstart/

(Yes finding it, was not intuitive, luckily, it's existence was mentioned in the forums) 

---

## Remove image background / select object, like with PS's AI
Affinity Photo has no smart-background-remove tools. <kbd>*2024-06-28, AP v2.5.3*</kbd>
### Solutions
- possible external solution: use https://www.photoroom.com/ (1280x1280px download) -- https://www.remove.bg/ (637x392px download) or others, then save the image and use it as mask in Affinity Photo, [see How-To](./detailed/Remove%20image%20background%20-%201.md) <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Paste an image from clipboard as new image
... Since the welcome screen with the new image options has no option to use clipboard size <kbd>*2024-06-28, AP v2.5.3*</kbd>
### Solutions 
- Do not use the welcome dialog, use the menu instead: File > New from Clipboard <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Something similar like smart-objects?
Smart-Objects are Photoshop specific: https://helpx.adobe.com/photoshop/using/create-smart-objects.html
### Solutions 
- yes, but: you have to create a separate .afphoto file and either drag it in or use `File > Place`. <kbd>*2024-06-28, AP v2.5.3*</kbd>
    - Double click will also navigate into it as in PS (layer filters work as well, but will be cut off, if they would render outside of the object frame)

## No transform mode or tool?
`CTRL + T` does no work, there seems to be no extra tool. <kbd>*2024-06-28, AP v2.5.3*</kbd>
### Solutions 
- Transform options are part of the object selection (Move Tool) <kbd>*2024-06-28, AP v2.5.3*</kbd>

## How do I enable snapping for the crop tool?
Using the crop tool to crop the image, the magnet does not affect it, it does not snap to the outermost used pixels. <kbd>*2024-06-28, AP v2.5.3*</kbd>
### No Solution known

## Why does the magic wand not select anything?
Sometimes, there is no layer selected/active when opening an image / removing layers <kbd>*2024-06-28, AP v2.5.3*</kbd>
### Solutions
- You need to make sure, to select a layer first. (It seems, unlike the area selection tool) <kbd>*2024-06-28, AP v2.5.3*</kbd>

## How do I make the negative-selection-rectangle show up to know where I started selecting?
It is invisible, but works. <kbd>*2024-06-28, AP v2.5.3*</kbd>
### No solution known
- <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Where are the layer filters?
Double clicking on the layer's right side itself is not available <kbd>*2024-06-28, AP v2.5.3*</kbd>
### Solutions
- The button is below the layers, (once the FX icon appeared for a layer, it can be clicked). The pattern-overlay is not available. <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Is there an option to disable: auto select layer
There seems to be no toggle to change auto selecting the layer by clicking on pixels to only select within the current selected layer <kbd>*2024-06-28, AP v2.5.3*</kbd>
### No solution known
### Related
- But there is a dropdown top left below the menu, to select a specific object selection mode, but you need to activate the `Move Tool` and have no layer selected, to be able to change it <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Masking is ... different?
### Solutions
- Select your layer you want to add a mask to, click the mask-button below the layers. Do not expand the layer with its empty mask, and drag your masking layer right to the empty mask in that original layer. Click on the empty mask and press delete on your keyboard. <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Export multiple image versions
... is close to what Photoshop has <kbd>*2024-06-28, AP v2.5.3*</kbd>
### Solutions
- Select the `Export Persona` top left, right below the file menu. ON the right side, click on the `Slices` tab, right next to `Layers`. The initial/first slice is always the full image. The export options above, are always for the selected slice. <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Export the current image
### Solutions
- File > Export <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Are there more filters?
### Solution
- you may use https://github.com/0xC0000054/gmic-8bf for windows (plugin install help: https://github.com/0xC0000054/gmic-8bf/wiki/Installing-in-Affinity-Photo ) <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Is there a list of previously used colors?
There is no list of custom colors like within the color selection dialog in PS or other tools <kbd>*2024-06-28, AP v2.5.3*</kbd>
### No solution known 
- <kbd>*2024-06-28, AP v2.5.3*</kbd>

## Where is the Web Font selection?
Only those installed on the system are available, not even google fonts or alike <kbd>*2024-06-28, AP v2.5.3*</kbd>
### No solution known 
- <kbd>*2024-06-28, AP v2.5.3*</kbd>

## What plugin to use to export to .ico (for windows programs or web) with multiple sizes included
Threre is no plugin. Visual Studio has an integrated .ico icon editor on windows. (https://learn.microsoft.com/en-us/cpp/windows/image-editor-for-icons?view=msvc-170)
### Solution
- you may use https://redketchup.io/icon-converter <kbd>*2024-08-27, AP v2.5.3*</kbd>


---

If any explanation needs more then a sentance, it will link to a different markdown file in the same repo, where images can be included. In this main document, images may only be linked for now.
