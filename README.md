Madoka-Higuchi-Custom-Tab
=========================
A custom new tab page with Madoka Higuchi image in it, and a simple to do list using JavaScript localStorage, so you won't lose your to do list if you closed the browser or turned off the device. Don't worry, there is a search bar to browse the web via <a href="google.com">Google</a>'s search engine. 

<a href="https://github.com/NavdPlay/Madoka-Higuchi-Custom-Tab/archive/refs/heads/main.zip">Download</a><br>
[How To Install?](#how-to-install)

Note!!!
=========================
- There are still some bug for the localStorage that is used for the functionality of the to do list. But this won't occur frequently.
- I haven't made this page responsive, so currently this web is only addressed for PC/laptop browsers.

How To Install
=========================
First, download this repository as a zip (you can use the download link above), and then extract it.

Because most of the browser doesn't allow you to make your custom new tab page, you should download an extension for your browser (see the list below).

| Chrome | <a href="https://chrome.google.com/webstore/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia/">Custom New Tab URL</a>  |
|--------|---------------------|
| Opera  | <a href="https://addons.opera.com/en/extensions/details/homepage-in-new-tab/">Homepage in New Tab</a> |

I've only tested for Chrome and Opera (GX), therefore I only have 2 extension recommendations, but maybe there will be future testing in some browser like Edge, Firefox, etc.

After you installed the extension for your browser, open the setting page of the extension, and there will be an input for your custom URL. Usually you can type as below:
```
file:\\\path-to-extracted-zip\Madoka-Higuchi-Custom-Tab-main\index.html
```
Note: The file location depends on where you downloaded the zip and extracted it.

If you're using Chrome, your new tab page is ready to go, you can press the new tab button or use ```Ctrl+T```.
If you're using Opera, you need some configuration to do, because you can't use your custom page as a new page uf you press the plus button. Using ```Ctrl+T``` also won't work, but we can configure the shortcuts. Here are the steps:

1. Open Opera settings and search for configure shortcuts. Or go to ```opera://settings/keyboardShortcuts```
2. In the shortcuts page look for the ```New Tab``` shortcut, you can either delete the shortcut by hovering on it and press the "x" symbol, or you can change the shortcut, for me I choosed ```Ctrl+Q``` for the new shortcut.
3. Still in the configure shortcuts page, scroll all the way to the bottom, you'll see lists of extensions with their own extensions, unless you changed them, the default is no shortcut for each extensions. So what you need to do is look for the extension "Homepage in New Tab", and set its shortcut to ```Ctrl+T```.

Now you should be able to open your custom new tab page by using the shortcut ```Ctrl+T```.


How To Custom Your Name
=========================
1. Open your code editor, if you don't have one you can use Notepad which most of the computers already have by default.
2. On the top left of the code editor window, press "File" and then press "Open", or just use ```Ctrl+O```.
3. After that look for where you stored the extracted zip, open the folder and select ```index.html```, make sure you changed from "Text Documents (*.txt)" to "All Files" on the bottom right of the Open File window, so the files in the folder is visible.
4. After you opened ```index.html```, search for "your-name" by using ```Ctrl+F```, and then replace "your-name" with your preferred name.

Now you should have your own customized name in the page.

Enjoy!
