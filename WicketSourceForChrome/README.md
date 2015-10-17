To create the extension for chrome do the following steps:

Open the Chrome browser and open Chrome's extension page, unfold "Developer Tools" and "Load unpacked extension...". 

Navigate to this project folder and load it.


That's it. The extension is now in your Chrome browser. 

### Pack it

If you want to pack it then navigate again to 
the Chrome's extension page, unfold "Developer Tools" and "Load unpacked extension..." and push the 'Pack extension' button.
A dialog will open and will ask you to choose the root folder of the extension. 
Choose as root folder this project folder(/wicket-source/WicketSourceForChrome) and optionally choose a private key.
Then push the button 'pack extension' to pack this project. The result will be that two files will be created in the parent root folder.

/wicket-source/WicketSourceForChrome.crx
and
/wicket-source/WicketSourceForChrome.pem
