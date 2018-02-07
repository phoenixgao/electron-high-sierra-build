https://github.com/Microsoft/vscode/issues/35361

https://github.com/electron/electron/issues/10657

https://github.com/electron/electron/pull/10696

# How to use
1. Open `Finder`, find `Visual Studio Code`, right click on it and select `Show Package Contents`
2. Under `Contents/MacOS` you will find the electron executable binary `Electron`, make a backup of it
3. Move the file you downloaded to here
4. Make sure its permission is set to 755

<b>Use this at your own risk! </b>

Built by [@primalmotion](https://github.com/primalmotion)

# Note

This will break vscode auto upgrade feature. You will need to manually download every new release and replace the bin, hoping it is still compatible.
