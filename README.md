# Agentuity Theme

A dark VSCode theme with cyan/turquoise accents designed for comfortable coding sessions.

## Features

- Dark background to reduce eye strain
- Vibrant cyan/turquoise highlights for better code readability
- Carefully selected color palette for syntax highlighting
- Support for multiple programming languages
- Optimized for terminal, editor, and UI elements

## Installation

### Method 1: Install from Local Directory (Current Setup)

Your theme is already installed locally in VSCode. To activate it:

1. Open VSCode
2. Press `Ctrl+K Ctrl+T` (or `Cmd+K Cmd+T` on Mac) to open the theme picker
3. Select **Agentuity** from the list

Alternatively:
1. Go to `File > Preferences > Color Theme` (or `Code > Preferences > Color Theme` on Mac)
2. Select **Agentuity**

### Method 2: Install from VSIX Package

To share your theme or install it on another machine:

1. Package the theme:
   ```bash
   npx vsce package
   ```

2. This creates an `agentuity-theme-1.0.0.vsix` file

3. Install the VSIX file:
   - Open VSCode
   - Go to Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`)
   - Click the `...` menu at the top of the Extensions view
   - Select "Install from VSIX..."
   - Choose the `.vsix` file

### Method 3: Manual Installation

1. Copy this entire directory to your VSCode extensions folder:
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **macOS**: `~/.vscode/extensions/`
   - **Linux**: `~/.vscode/extensions/`

2. Reload VSCode
3. Select the theme from the Color Theme picker

### Method 4: Publish to Marketplace (For Public Distribution)

To make your theme available to everyone:

1. Create a publisher account at [Visual Studio Marketplace](https://marketplace.visualstudio.com/manage)

2. Update `package.json` with your publisher name

3. Install vsce (VSCode Extension Manager):
   ```bash
   npm install -g @vscode/vsce
   ```

4. Login to your publisher account:
   ```bash
   vsce login <your-publisher-name>
   ```

5. Publish your theme:
   ```bash
   vsce publish
   ```

## Color Palette

The theme uses a carefully selected color palette:

- **Background**: Deep dark blue-green (#041619)
- **Foreground**: Light cyan-gray (#afc8cc)
- **Accent**: Bright cyan (#42d8ea, #18a9bb)
- **Comments**: Muted teal (#5e8a90)
- **Strings**: Light cyan (#c5e8e8)
- **Keywords**: Purple (#b896d4)
- **Functions**: Blue (#7eb3d4)
- **Variables**: Teal (#76c7c7)

## Screenshots

![Agentuity Theme in Action](images/screenshot-1.png)

The theme features vibrant cyan/turquoise highlights on a deep dark background, optimized for comfortable coding sessions.

## Customization

If you want to customize specific colors, add this to your `settings.json`:

```json
"workbench.colorCustomizations": {
  "[Agentuity]": {
    "editor.background": "#your-color-here"
  }
}
```

## Feedback

If you have suggestions or find issues, please report them in the repository.

## License

See LICENSE file for details.
