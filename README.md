# BG Mineral Themes

Three color themes for VS Code and Cursor. Flat UI. Code colors inspired by minerals and ocean.

## Themes

### BG Galena
Mint greens with teal and gold.

**Key Colors:**
- Strings: `#A0E8C8`
- Numbers: `#e8c870`
- Types: `#60d8a8`
- Functions: `#40c8a8`

### BG Peridot
Light greens, yellows, and orange.

**Key Colors:**
- Strings: `#AAFFCC`
- Numbers: `#FFEE88`
- Types: `#88DDAA`
- Functions: `#60B9E0`

### BG Rutile
Dark with muted blues.

**Key Colors:**
- Strings: `#6088a0`
- Numbers: `#c0b070`
- Types: `#5090b0`
- Functions: `#4090c0`

## Installation

### Via VSIX File (Manual Installation)

1. Download the latest `bg-mineral-theme-1.0.0.vsix` file from the [releases](https://github.com/bjarnig/cursor-themes/releases)
2. Open VS Code or Cursor IDE
3. Press `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows/Linux)
4. Type "Extensions: Install from VSIX"
5. Select the downloaded `.vsix` file
6. Reload the editor when prompted

### Via VS Code Marketplace (Coming Soon)

Search for "BG Mineral Themes" in the Extensions marketplace.

## Activation

1. Press `Cmd+K Cmd+T` (Mac) or `Ctrl+K Ctrl+T` (Windows/Linux)
2. Select one of:
   - **BG Galena**
   - **BG Peridot**
   - **BG Rutile**

Or go to **Preferences → Color Theme** and choose your preferred theme.

## Features

- Flat UI
- Three themes
- Blues, greens, and earth tones
- Good contrast ratios

## Philosophy

UI is flat and minimal. Code colors are distinct. Pick the theme that works for you.

## Building from Source

```bash
# Clone the repository
git clone https://github.com/bjarnig/cursor-themes.git
cd cursor-themes

# Install vsce (VS Code Extension Manager)
npm install -g @vscode/vsce

# Package the extension
vsce package

# This creates bg-mineral-theme-1.0.0.vsix
```

## Contributing

Found a bug or have a suggestion? Please open an issue on [GitHub](https://github.com/bjarnig/cursor-themes/issues).

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Author

Bjarni Guðmundsson

## Inspiration

Named after minerals. Peridot is green. Rutile is dark. Galena is silvery.

