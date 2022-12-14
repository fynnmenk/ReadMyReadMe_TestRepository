# ReadMyReadMe for Visual Studio Code <!-- omit in toc -->

## Description

This is a Testrepository to do evaluation on the [ReadMyReadMe Extension](https://marketplace.visualstudio.com/items?itemName=fynnmenk.readmyreadme).
Consider it in the [Marketplace](#Marketplace).
Be aware some ReadMe flaws are in this ReadMe.

## Table of Content

- [Description](#description)
- [Table of Content](#table-of-content)
- [Installation](#installation)
- [Usage](#usage)
- [Usage if you are new](#usage-if-you-are-new)
- [Contributing](#contributing)
- [Contributors](#contributors)
- [License](#license)

## Installation

1. Open [Visual Studio Code](https://code.visualstudio.com/)
2. Press `Ctrl+P`/`⌘P` to open the Quick Open dialog
3. Type `ext install readmyreadme` to find the extension
4. Click the `Install` button, then the `Enable` button

OR

1. Press `Ctrl+Shift+X`/`⇧⌘X` to open the Extensions tab
2. Type `readmyreadme` to find the extension
3. Click the `Install` button, then the `Enable` button

OR

1. Open a command-line prompt
3. Run `code --install-extension fynnmenk.readmyreadme`
In VSCode
Press F1 or CTRL+P (or CMD+P) and type out `> ext install fynnmenk.readmyreadme`. Check out the latest published version on the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=fynnmenk.readmyreadme).

## Usage

When editing your `README.md` this linter is checking following features:

- outline structure of the README should match recommended outlines by the [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950584922000775?via%3Dihub#preview-section-snippets).
- TBA
Note: recommended to also consider following extension for a better Documentation Quality in your README file
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

## Usage if you are new

When editing your `README.md` this linter is checking following features:

- outline structure of the README should match recommended outlines by the [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950584922000775?via%3Dihub#preview-section-snippets).
- TBA

Note: recommended to also consider following extension for a better Documentation Quality in your README file

- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

## Contributing

- Install Node.js
- Run `npm install` in this folder. This installs all necessary npm modules in both the client and server folder
- Open VS Code on this folder.
- Press Ctrl+Shift+B to start compiling the client and server in [watch mode](https://code.visualstudio.com/docs/editor/tasks#:~:text=The%20first%20entry%20executes,the%20HelloWorld.js%20file.).
- Switch to the Run and Debug View in the Sidebar (Ctrl+Shift+D).
- Select `Launch Client` from the drop down (if not already).
- Press ▷ to run the launch config (F5).
- If you want to debug the server as well, use the launch configuration `Attach to Server`
- In the [Extension Development Host](https://code.visualstudio.com/api/get-started/your-first-extension#:~:text=Then%2C%20inside%20the%20editor%2C%20press%20F5.%20This%20will%20compile%20and%20run%20the%20extension%20in%20a%20new%20Extension%20Development%20Host%20window.) instance of VSCode, open a document in 'plain text' language mode.
    - Open your `README.md` add uncommon headlines i.e. `## Uncommon` to see features

## Contributors

- contribute to be the first in this section :)

## License

This is licensed under the MIT open source license. Do what you want with this software, include notice that it orginated with me.
