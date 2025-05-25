# OpenAI Docs Theme for VS Code

A dark theme for Visual Studio Code inspired by the OpenAI documentation website.

## Installation

### Local Installation
1. Clone this repository
2. Copy the `.vscode-theme` folder to a location of your choice
3. Open VS Code
4. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac) and type "Install from VSIX"
5. Navigate to the `.vscode-theme` folder and select the generated .vsix file

### Manual Installation
1. Copy the `.vscode-theme` folder to your VS Code extensions folder:
   - Windows: `%USERPROFILE%\.vscode\extensions`
   - macOS: `~/.vscode/extensions`
   - Linux: `~/.vscode/extensions`
2. Restart VS Code
3. Select the theme via `Preferences > Color Theme > OpenAI Docs Theme`

## Building the VSIX Package

To build the VSIX package, you'll need to install the VS Code Extension Manager (vsce):

```bash
npm install -g @vscode/vsce
cd .vscode-theme
vsce package
```

This will generate a .vsix file that you can install in VS Code.

## Features

- Dark theme inspired by the OpenAI documentation website
- Optimized for readability with carefully selected colors
- Syntax highlighting that matches the OpenAI docs aesthetic

## Screenshot

![OpenAI Docs Theme Example](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme/raw/main/images/gpt%20theme%20example.png)
*VS Code with the OpenAI Docs Theme applied*

## Color Palette

- Main Background: #202123
- Sidebar Background: #0F0F10
- Accent Colors: 
  - Green: #10A37F (primary accent)
  - Purple: #A292FF (for keywords and tags)
- Text: #FFFFFF 