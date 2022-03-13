# UserScipt Installation tutorial

Depending on the browser you use and the extension you choose, the installation may differ.

Do you have an idea for improving the tutorial? Share your suggestion here: [Issues](https://github.com/sz3lbi/userscipt-installation-tutorial/issues)

_Read this in other languages: [English](README.md), [Polski](README.pl.md)._

## Table of Contents

- [Violentmonkey (recommended)](#violentmonkey-recommended)
- [Greasemonkey](#greasemonkey)
- [Tampermonkey](#tampermonkey)

## Violentmonkey (recommended)

Go to: [Get Violentmonkey](https://violentmonkey.github.io/get-it/). There, select the browser you are using and then, after being redirected to the extension store, install Violentmonkey.  
Due to its open source code, availability for many browsers, and automatic script update enabled by default, this is the preferred installation option.

After installing the extension, navigate to the script file. Violentmonkey will automatically detect the opening of the `.user.js` file and in a new tab offer to install the script. After confirming the installation with the "**Confirm installation**" button, close the tab with the "**Close**" button next to it.  
There is a possibility that the extension will not automatically detect the opening of a file with the UserScript. If this happens, copy the entire contents of the file, click on the Violentmonkey icon in the browser bar, and then the plus symbol in the upper right corner of the menu. In the newly opened tab, replace the sample code with the one from the clipboard and save. Automatic updates are enabled by default.

### Violentmonkey compatible browsers

- Chrome
- Firefox,
- Edge,
- Opera,
- Maxthon 4 & 5.

## Greasemonkey

The Firefox browser offers an extension called Greasemonkey. Due to its open source code, it is the preferred option over the Tampermonkey.  
The extension can be found at: [Greasemonkey - Firefox Addons](https://addons.mozilla.org/pl/firefox/addon/greasemonkey/)

After installing the extension, navigate to the script file. Greasemonkey should automatically detect the opening of the user script file and open a new tab, suggesting the installation. In this case, simply press the green "**Install**" button.  
Otherwise, when the extension does not propose installation, copy the entire contents of the opened file, then press the Greasemonkey icon in the browser bar and select "**New user script...**". In the newly opened tab, replace the sample script code with the contents of the clipboard and save the script (the floppy icon in the upper left corner or the keyboard shortcut CTRL+S). The disadvantage of this path is that the script does not update automatically, so you have to do it yourself (by deleting and reinstalling the script).

### Greasemonkey compatible browsers

- Firefox.

## Tampermonkey

If you are using a different browser or do not want to use Violentmonkey and Grasemonkey for other reasons, install the Tampermonkey extension from the link: [Tampermonkey.net](https://www.tampermonkey.net/)  
This page should automatically detect what browser you are using and display the appropriate version of the extension.

Once the extension is installed, navigate to the script file. Tampermonkey will detect that you have opened the `.user.js` file and open a tab where you can install the script.  
If nothing happens, you can click the Tampermonkey icon in the browser bar, then "**Create a new script**" and replace the entire contents of the newly opened window with the one you copied from the file. Remember to save the script. Then you can close the tab.

If you use the second installation path, after installing the script you should click on the Tampermonkey icon in the browser bar, then "**Dashboard**" and the name of the script installed. Navigate from the "**Editor**" tab to the "**Settings**" tab and make sure you check the "**Check for updates**" checkbox in the "**Updates**" section. If you don't do that, your script will not automatically update to the latest version when it is released. Remember to click the "**Save**" button below before closing the tab.

### Tampermonkey compatible browsers

- Chrome,
- Firefox,
- Edge,
- Opera,
- Safari.
