# Setting up VS Code:

## Downloading VS Code:

Visit https://code.visualstudio.com/ and download Studio.

## Configuring VS Code:

### Portable Mode
I use VS Code's [Portable Mode](https://code.visualstudio.com/docs/editor/portable) which allows me to store all of my editor settings in an easy to find place. All I have to do is drop a folder named `code-portable-data` in the same directory as the `Visual Studio Code.app` file. The instructions from Microsoft are fairly straightforward.

### Custom Snippets
I created several custom snippets to increase my efficiency. These can be found at:

- [html snippets](./config/snippets/html.json)
- [javascript snippets](./config/snippets/javascript.json)

There aren't any overly useful snippets for our current goals, but these should provide an example of how you can create custom snippets that enhance your own workflow.

### Custom Config
My custom config settings are available [as well](./config/settings.json). This details any "user" settings I've modified in VS Code such as colors, fonts, rules for _TODO Parser_ and several others. Feel free to use this as a reference on things that might be useful to you. 

## Productivity Extensions 🤓

VS Code is highly extensible and there are many extensions available to perform various enhancements to your workflow. There are many that do the same function. Please research the plugins you choose and determine which will work best for you and the way you work.

I just want to share my current setup with anyone who is interested.

The following extensions I use to aid in my workflow:

### _Auto Close_ Tag by Jun Han

- Name: Auto Close Tag
- Description: Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text
- Publisher: Jun Han
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag
  ![auto close tag demo][auto-close-tag]

### _Auto Rename_ Tag by Jun Han

- Name: Auto Rename Tag
- Description: Auto rename paired HTML/XML tag
- Publisher: Jun Han
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag
  ![auto rename tag demo][auto-rename-tag]

### _Babel Javascript_ by Michael McDermott

- Name: Babel JavaScript
- Description: VSCode syntax highlighting for today's JavaScript, ported from gandm's language-babel for Atom.
- Publisher: Michael McDermott
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel

### _Bracket Pair Colorizer_ by CoenraadS

Name: Bracket Pair Colorizer
Description: A customizable extension for colorizing matching brackets
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer
![Bracket Colors Exmaple][bracket-pair-coloerizer]

### _htmltagwrap_ by Brad Gashler

- Name: htmltagwrap
  Description: Wraps selected code with HTML tags
  Publisher: Brad Gashler
  VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap
  ![html tag demo][htmltagwrap]

### _Intellisense for CSS_ by Zignd

- Name: IntelliSense for CSS class names in HTML
- Description: CSS class name completion for the HTML class attribute based on the definitions found in your workspace.
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion
  ![Intellisense for css][css_intellisense]

### _NPM Intellisense_ by Christian Kohler

- Name: npm Intellisense
- Description: Visual Studio Code plugin that autocompletes npm modules in import statements
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense
  ![Intellisense for NPM][npm_intellisense]

### _Path Intellisense_ by Christian Kohler

- Name: Path Intellisense
- Description: Visual Studio Code plugin that autocompletes filenames
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense
  ![Intellisense for local paths][path_intellisense]

### _Prettier_ by Esben Petersen

- Name: Prettier - Code formatter
- Description: VS Code plugin for prettier/prettier
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
- This extension formats your code after you write it to fall into line with opinionated rules.

  Generally in my own environment I try to follow the [airbnb styleguide](https://github.com/airbnb/javascript); but some devs prefer a different style. This helps inforce those style guides automagically after being configured. Out of the box it's pretty decent though as well.

  ![Shai Lebouf is magical][magic]

### _React snippets_ by Equimper

- Name: React-Native/React/Redux snippets for es6/es7
- Description: Code snippets for React-Native/React/Redux es6/es7 and flowtype/typescript, Storybook
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux
- VS Code allows for code snippets that auto expand into full lines. For instance, using react snippets, one can type `imrc` will populate that line with `import React, { Component } from 'React'`. There are other snippets available, but this is probably one of my most used.
- No demo gif here, but a complete list of snippets can be found on this plugin's [READEME](https://github.com/EQuimper/VSC-React-Native-React-Redux-Snippets/blob/master/README.md).

### _TODO Parser_ by minhthai

- Name: TODO Parser
- Description: Parse TODOs in your working files.
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=minhthai.vscode-todo-parser
- By placing comments in your code such as `// TODO: Need to fix this` the TODO's will populate in VS Code's Problems tab and be highlighted so you don't forget!
  ![TODO Parser demo][todo_parser]

## Cosmetic Extensions 💅

The following Extensions help make VS Code more visually appealing to me. These visuals also help make files and folders stand out in the file browser pane. These are just eprsonal preferences.

### _Material Icon Theme_ by Philip Kief

- Name: Material Icon Theme
- Description: Material Design Icons for Visual Studio Code
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
- Makes pretty icons show up in the file browser
- No demo images here either, but checkout all of the icons available in the [README](https://github.com/PKief/vscode-material-icon-theme/blob/master/README.md).

### _Gruvbox Minor_ by adamsome

- Name: Gruvbox Minor
- Description: Gruvbox Minor
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=adamsome.vscode-theme-gruvbox-minor
- Color theme for my editor.
  ![gruvbox minor demo][gruvbox_minor]

[css_intellisense]: ./assets/css_intellisense.gif
[npm_intellisense]: ./assets/npm_intellisense.gif
[path_intellisense]: ./assets/
[magic]: ./assets/magic.gif
[todo_parser]: ./assets/todo.gif
[gruvbox_minor]: ./assets/gruvbox.png
[auto-close-tag]: ./assets/auto-close-tag.gif
[auto-rename-tag]: ./assets/auto-rename-tag.gif
[bracket-pair-coloerizer]: ./assets/bracket-pair-coloerizer.png
[htmltagwrap]: ./assets/htmltagwrap.gif
