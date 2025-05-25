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

## Showcase

Here's how the OpenAI Docs Theme looks in action:

![OpenAI Docs Theme in Action](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme/raw/main/images/gpt%20theme%20example.png)
*VS Code with the OpenAI Docs Theme applied - showing syntax highlighting and UI theming*

### Theme Details
- Clean, modern interface with focus on code readability
- Carefully selected color palette that's easy on the eyes
- Consistent theming across all UI elements
- Optimized for long coding sessions

## Color Palette

### Main Colors
[![Main Background](https://img.shields.io/badge/Main%20Background-%23202123-202123?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=202123&colorA=202123&colorB=10A37F&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)
[![Sidebar Background](https://img.shields.io/badge/Sidebar%20Background-%230F0F10-0F0F10?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=0F0F10&colorA=0F0F10&colorB=10A37F&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)

### Accent Colors
[![Primary Accent](https://img.shields.io/badge/Primary%20Accent-%2310A37F-10A37F?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=10A37F&colorA=10A37F&colorB=202123&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)
[![Purple Accent](https://img.shields.io/badge/Keywords%20%26%20Tags-A292FF-A292FF?style=flat-square&logo=visualstudiocode&logoColor=black&labelColor=A292FF&colorA=A292FF&colorB=202123&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)

### Additional UI Colors
[![Text Color](https://img.shields.io/badge/Text-FFFFFF-FFFFFF?style=flat-square&logo=visualstudiocode&logoColor=black&labelColor=FFFFFF&colorA=FFFFFF&colorB=202123&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)
[![Selection](https://img.shields.io/badge/Selection-2A2B32-2A2B32?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=2A2B32&colorA=2A2B32&colorB=10A37F&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)
[![Active Tab](https://img.shields.io/badge/Active%20Tab-343541-343541?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=343541&colorA=343541&colorB=10A37F&label=)](https://github.com/FalloutGhoulBusta/openai-docs-vscode-theme)
