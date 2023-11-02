# OpenSIPS Syntax Highlighting

This Visual Studio Code (VSCode) extension provides basic syntax highlighting for OpenSIPS configuration files.

## Installation

This extension has not yet been published to the VSCode Marketplace, as it is still in beta.

### Legacy
To add the extension to VSCode, clone the project into your local VSCode folder:

- on Windows: `%USERPROFILE%\.vscode\extensions`
- on Mac/Linux: `$HOME/.vscode/extensions`

Restart VSCode and the extension will automatically run everytime you open a file with a `.cfg` or `.cfg.m4` extension.

### Current
To add the extension to VSCode, you will need to manually package the extension via [vsce](https://github.com/microsoft/vscode-vsce):

- run `vsce package`
- install the `.vsix` file in VSCode
  - Go to the Extensions view.
  - Click **Views and More Actions...**
  - Select **Install from VSIX...**