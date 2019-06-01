# Asset Management Blender 2.8
v2.3.7
* Added auto thumbnail rendering for materials
---
v2.3.6
* fixed bug on the setup previous settings if the library haven't got any 
asset type
* fixed bug on the add new library
---
v2.3.5
* fixed import bug with several preview displayed
* resize preview to the maximum width of the N panel
---
v2.3.4
* link datas in the scene when we use the editing asset tool
* remove the invalid libraries from the database
* "lock import" added (to avoid importing an asset when you choose in the preview)
* fixed bug when exporting ibl to the library
---
v2.3.3
* Added replace asset with an option to use the existing thumbnail
* Added a ALT+click on any category to hide the hierarchy
* Fixed bug on the rename category
* Added edit asset tool
---
v2.3.2
* added preview visibility in the hierarchy
* fixed bug if the active category of the previous blender session was deleted
* added an error report if the targeted material is not found in the .blend 
(in case of the material in the .blend does not have the same name as the 
thumbnail)
* fixed bug on adding ibl asset
---
v2.3.1
* auto path correction for "From computer" thumbnails
* fixed bug for thumbnail in "Rendered" mode if it's different from "Render Result"
* Reset the update of the "library_path" property to update the json
---
v2.3.0
* New hierarchy system to replace collections/categories
* Remove assets
* Displaying several previews
---
v2.2.9
* Export IBL with auto thumbnails render
* Export scenes asset with rendered (in image editor) or existing thumbnail 
(on your computer).
* Moved "Preview size" and "Popup icon size" from assets to thumbnail 
preferences.
---
v2.2.8
* Export material asset with rendered (in image editor) or existing thumbnail 
(on your computer).
* Added option in the tool panel to display the IBL settings from meshes, 
materials and scenes asset type.
---
v2.2.7
* Fixed bug when creating a category that did not display the default icon
* Fixed poor management of invalid libraries
* Draw enum items in alphabetical order
* Set the newest asset as active in the preview
* Delete the default icon if the category is empty when adding a new
 asset
 ---
v2.2.6
* Fixed the bug that prevented the libraries from being displayed correctly 
* Added list of lost libraries in the addon preferences
* Link for asset's collections (like groups for 2.79)
* Export mesh asset with rendered (in image editor) or existing thumbnail 
(on your computer).
* Added options for preview size and popup icon size
---
v2.2.5
* Fixed preview's bug that did not display the content of some categories
---
v2.2.4
* fixed bug for the categories (Beyond the first 9 collections, the categories 
were no longer displayed)
* fixed bug due to the bl_idname of the class menu
---
v2.2.3
* automatic update detector
* library manager
* import/link assets
