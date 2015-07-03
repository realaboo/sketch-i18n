# Sketch i18n
Sketch i18n enables you to generate translation files for a page and translate it. It acts in a non-destructive way so you can easily undo your changes later.

## Text Layer Filtering and Text Keys
This fork provides a way to generate text entries only for those need to be translated. You can do this by setting a layer name prefixed with "str_" for each text layer you want to translate. The text layer names will also be the keys in the translation files. This makes it easier for further processing the translation files to use in iOS and Android projects.

## Installation
1. Download the repository from this [link](https://github.com/kristof/sketch-i18n/archive/master.zip).
2. Grab the `Sketch i18n` folder from the ZIP.
3. In Sketch 3, select `Plugins > Reveal Plugins Folder...` from the menu bar, and put the `Sketch i18n` folder in this folder.

## Usage
### Create a translation file
1. Select a page in your Sketch file.
2. Run `1. Generate translation file` from the plugins menu.
3. The contents of your translation file is now in your clipboard.
4. Paste the contents of your clipboard in your favorite editor.
6. Save the file as a JSON file for example: `en-US.json`.

### Translating a page
1. Select a page in your Sketch file you wish to translate.
2. Run `2. Translate page`.
3. Select the JSON translation file for that page.
4. The current page has been copied and translated.

## Help me improve Sketch i18n
To propose changes, fork the repository and submit a pull request!

## Questions?
[@houbenkristof](http://twitter.com/houbenkristof)

## Contributors
All credit goes to Kristof Houben [(kristof)](https://github.com/kristof)
and
Florian Schulz [(getflourish)](https://github.com/getflourish)
