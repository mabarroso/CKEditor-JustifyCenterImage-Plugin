# CKEditor-JustifyCenterImage-Plugin
  Justify center images plugin for CKEditor

# Description
  There's no center image alignment in HTML, so the Center button is disabled for images. To center it, the image must be wrapped in a (psuedo)block element with text-align: center; to be centered.

  This plugin allow center selected images.

# Installation

 1. Extract the contents of the file into the "plugins" folder of CKEditor.
 2. In the CKEditor configuration file (config.js) add the following code:

````
config.extraPlugins = 'justifycenterimage';
````

 3. Include the plugin in the toolbar

````
toolbar :[ ... ['JustifyCenterImage']...]
````

# License
  Released under the MIT license: [http://www.opensource.org/licenses/MIT](http://www.opensource.org/licenses/MIT)
