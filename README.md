# VSCode Stardew Icon Theme

A Stardew Valley themed product icon pack!
Currently for common front-end web development file types

<img width="165" alt="Screen Shot 2020-08-31 at 8 26 01 PM" src="https://user-images.githubusercontent.com/7905522/91792254-f5063500-ebc9-11ea-9baa-560540a92613.png">

### Autumn mode:

<img width="242" alt="Screen Shot 2020-10-02 at 4 21 06 PM" src="https://user-images.githubusercontent.com/7905522/94976906-54a67780-04cb-11eb-803e-8972a21a9e6b.png">

### Download at https://marketplace.visualstudio.com/items?itemName=klyap.vscode-stardew-icon-theme
<img width="739" alt="Screen Shot 2020-10-02 at 4 14 12 PM" src="https://user-images.githubusercontent.com/7905522/94976903-52dcb400-04cb-11eb-8d84-04c2094ea725.png">

## Development

This extension uses image files directly from the `icons` folder in `icons.json`.

Open this repo in VSCode and hit F5 to test it out.

You will need to run to develop:
```yarn install```
```yarn install -g vsce```

### To publish a new version to the VS Code Extension Marketplace
Update the version number in package.json and run:
```vsce publish```

### To package for sharing with others
Run this command to generate a VSIX file:
 ```vsce package```
To load this VSIX extension into your VS Code IDE, replacing the file name with the generated one:
```code --install-extension vscode-stardew-icon-theme-0.0.3.vsix```

## Resources

Icons from https://stardewvalleywiki.com/Stardew_Valley_Wiki


