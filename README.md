<p align="center">
  <a href="https://github.com/mtdmali/daybreak-theme/">
    <img alt="daybreak banner" src="https://i.imgur.com/eaaoa9J.jpg">
  </a>
</p>

---

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=mtdmali.daybreak-theme">
    <img alt="Visual Studio Marketplace Version" src="https://img.shields.io/visual-studio-marketplace/v/mtdmali.daybreak-theme?color=%23FAB28E&style=for-the-badge">
    <img alt="Visual Studio Marketplace Downloads" src="https://img.shields.io/visual-studio-marketplace/d/mtdmali.daybreak-theme?color=%23FAB28E&style=for-the-badge">
    <img alt="Visual Studio Marketplace Rating (Stars)" src="https://img.shields.io/visual-studio-marketplace/stars/mtdmali.daybreak-theme?color=%23FAB28E&style=for-the-badge">
  </a>
</p>

<h1 align="center">
  <a href="https://daybreaktheme.com">daybreaktheme.com</a>
</h1>

<p align="center">
  <img alt="Daybreak preview" src="https://i.imgur.com/zAckDdQ.png" width="90%">
</p>

## Installation

1. Open the **Extensions** sidebar in VS Code
2. Search for `Daybreak`
3. Click **Install**
4. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`
5. Select **Preferences: Color Theme** and choose **Daybreak**
6. Select **Preferences: File Icon Theme** and choose a Daybreak variant.
7. Enjoy! 🌅 Also, check out some of the personalization options below...

## Personalization

This theme is the byproduct of some very opinionated changes to both <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">Horizon Theme</a> and <a href="https://marketplace.visualstudio.com/items?itemName=artlaman.chalice-icon-theme">Chalice Icon Theme</a>.

Included is the default version of the theme, with alternative options that support italic and bold syntax highlighting. I personally use the italic variant, but I encourage you to find an option that works best for you.

_For more info on theming, visit the [Theme Authoring Guide](https://code.visualstudio.com/api/extension-capabilities/theming) and [Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)._

## Recommended Fonts, Extensions & Settings

I am a big fan of fonts that support ligatures. I highly recommend the following fonts:

- <a href="https://dank.sh/">Dank Mono (£40)</a>
- <a href="https://github.com/tonsky/FiraCode">Fira Code (Free)</a>

> Note: Ensure you enable font ligatures by adding `"editor.fontLigatures": true,` to your `settings.json` file.

I also highly recommended two particular extensions to help augment this theme even further:

- <a href="https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments">Better Comments</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2">Bracket Pair Colorizer 2</a>

Download these extensions and add the following settings to your `settings.json` file.

### Better Comments

<img src="https://i.imgur.com/pPUkIlI.png" alt="Better Comments preview">

```json
"better-comments.tags": [
    {
      "tag": "!",
      "color": "#2E302E",
      "strikethrough": false,
      "backgroundColor": "#E95678"
    },
    {
      "tag": "?",
      "color": "#2E302E",
      "strikethrough": false,
      "backgroundColor": "#B877DB"
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "backgroundColor": "transparent"
    },
    {
      "tag": "todo",
      "color": "#FAB795",
      "strikethrough": false,
      "backgroundColor": "#2E302E"
    },
    {
      "tag": "*",
      "color": "#FDF0ED",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "#",
      "color": "#FDF0ED",
      "strikethrough": false,
      "backgroundColor": "#2E302E"
    },
    {
      "tag": "_",
      "color": "#2E302E",
      "strikethrough": false,
      "backgroundColor": "#FDF0ED"
    }
  ],
```

### Bracket Pair Colorizer 2

<img src="https://i.imgur.com/GprIokQ.png" alt="Bracket Pair Colorizer 2 preview">

```json
"bracket-pair-colorizer-2.colors": ["#FAC29A", "#B877DB", "#25B2BC"],
```

## License

[MIT](LICENSE) © [Mike Mali](https://github.com/mtdmali)
