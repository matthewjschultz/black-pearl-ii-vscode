# Black Pearl II Original

The authentic Black Pearl II theme for Visual Studio Code, faithfully ported by Claude.ai from the original TextMate theme by Andrew Witte.

## About

This is a direct port of the original Black Pearl II TextMate theme created by Andrew Witte in 2006. Unlike other adaptations that have been modified through various editors, this version preserves the exact color values and styling from the original `.tmTheme` file.

## Features

- **Pure black background** (#000000) for maximum contrast
- **Faithful to the original** - All colors and styles exactly as Andrew Witte intended
- **High contrast syntax highlighting** with vibrant colors
- **Comprehensive language support** through TextMate scopes

## Original Color Palette

From the original TextMate theme:

- Background: `#000000` (Pure Black)
- Foreground: `#FFFFFF` (White) / `#CCCCCC` (Source)
- Comments: `#428BDD` (Blue, Italic)
- Strings: `#CC66FF` (Purple)
- Keywords: `#F8BB00` (Yellow/Gold, Bold)
- Control Keywords: `#FF9D00` (Orange)
- Functions: `#FFFFFF` (White, Bold)
- Variables/Constants: `#D0FF7E` (Lime Green)
- Numbers: `#EDDD5A` (Yellow)
- Language Constants: `#80D500` (Green, Bold)
- Symbols: `#66CCFF` (Cyan)
- Function Parameters: `#8AA6C1` (Light Blue, Italic)
- Invalid: `#670000` (Dark Red Background, Bold)
- CSS Selectors: `#B53B3C` (Red, Bold)

## Installation

### Method 1: Manual Installation
1. Create folder: `~/.vscode/extensions/black-pearl-ii-original/`
2. Copy `package.json` to that folder
3. Create subfolder: `themes/`
4. Save the theme JSON as `themes/black-pearl-ii-original.json`
5. Add entry to `~/.vscode/extensions/extensions.json`:
```json
{
  "identifier": {
    "id": "local.black-pearl-ii-original"
  },
  "version": "1.0.0",
  "location": {
    "$mid": 1,
    "path": "/Users/[YOUR_USERNAME]/.vscode/extensions/black-pearl-ii-original",
    "scheme": "file"
  },
  "relativeLocation": "black-pearl-ii-original",
  "metadata": {
    "installedTimestamp": 1756500000000,
    "pinned": false,
    "source": "vsix"
  }
}
```
6. Restart VS Code
7. Select "Black Pearl II Original" from Color Themes

### Method 2: Package as VSIX
```bash
cd ~/.vscode/extensions/black-pearl-ii-original
npm install -g vsce
vsce package --no-dependencies
code --install-extension black-pearl-ii-original-1.0.0.vsix
```

## Original Theme Information

- **Created by**: Andrew Witte
- **Year**: 2006
- **Original Platform**: TextMate
- **License**: Creative Commons Attribution 2.5 License
- **Original Contact**: tmthemes@andrewwitte.com

## Comparison with Other Versions

This "Original" version differs from other Black Pearl II ports:
- Preserved exact color values from the TextMate `.tmTheme` file
- Maintained all original font style attributes (bold, italic, underline)
- No color adjustments or "improvements" - pure authenticity
- Direct scope mappings from TextMate to VS Code

## Credits

- **Original Theme**: Andrew Witte (2006)
- **TextMate Theme Source**: Preserved via Archive.org
- **VS Code Port**: Faithful conversion maintaining original design intent

## License

Creative Commons Attribution 2.5 License (as per original theme)

Some Rights Reserved - Please attribute to Andrew Witte when distributing or modifying.

---

*This is the authentic Black Pearl II experience, exactly as it was designed for TextMate.*
