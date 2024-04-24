# miniFox
### A simple and minimalist firefox
<img alt="Vedai" width="800" src="https://github.com/Nishantdd/miniFox/blob/main/img/swappy-20240424_205257.png"></p>

## ⚙️ Installation
#### `Note : Please install the font SF Pro Display in your systems or feel free to change the font in userContent.css file for the search box`
1. In the searchbar type ```about:config```. A dialog will be shown to you. Press the I accept the risk button.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`, `layers.acceleration.force-enabled`, `gfx.webrender.all`, and `svg.context-properties.content.enabled` and enable them all.
3. In the searchbar type ```about:profiles```. Search for the profile that says : This is the profile in use and it cannot be deleted.
4. Open the root directory of that profile
5. Paste the chrome folder from the git-clone or downloaded zip of the repo to that folder
### Directory Structure :
`Linux : $HOME/.mozilla/`<br>
`Windows : C:\Users\<USERNAME>\AppData\Roaming\Mozilla\`\
`MacOS : Users/<USERNAME>/Library/Application Support/`
```
├── firefox
│   ├── XXXXXX.default-XXXXXX
│   │   ├── chrome
|   │   │   ├── userChrome.css
|   │   │   ├── userContent.css
```

## Extra :
Visit the following repos for better understanding of firefox theming :<br>
[Haruzona](https://github.com/Haruzona/penguinFox) (PenguinFox)<br>
[migueravila](https://github.com/migueravila/SimpleFox) (SimpleFox)

