# Welcome to Zaun 🏭

A VS Code color theme inspired by the underground city of Zaun from Arcane — damp stone streets lit by flickering gas lanterns, hextech pipes leaking green light, and the amber glow of makeshift machinery humming in the dark. Nothing screams. Everything glows.

---

## Preview

> _"We don't get the sun down here. We make our own light."_

The theme draws from Zaun's concept art — murky, layered, industrial. The editor background is almost black, like wet cobblestone. Green and amber don't flood the screen; they peek through, the way light leaks from a lantern grate or a cracked pipe. The deeper you look, the more you see.

**Core palette:**

| Color            | Hex       | Used for                      |
| ---------------- | --------- | ----------------------------- |
| 🌑 Wet stone     | `#0e130c` | Editor background             |
| 🪨 Void black    | `#0a0e09` | UI chrome, sidebar            |
| 🌿 Lantern green | `#4a9e52` | Functions, accents            |
| 💚 Pipe glow     | `#6dc275` | Highlights, bright accents    |
| 🍂 Amber lamp    | `#c9922a` | Cursor, active tabs, keywords |
| 🌾 Faded green   | `#8aab82` | Default text                  |
| 🫧 Steam blue    | `#4a7a9b` | Info, type hints              |
| 🟤 Rust          | `#c0523a` | Errors                        |
| 🌲 Shadow green  | `#3d7a44` | Variables, subdued tokens     |
| 🪵 Dim amber     | `#8a6120` | Line numbers, comments        |

---

## Features

- **Underground atmosphere** — all chrome (activity bar, sidebar, tabs, status bar, title bar) uses the same near-black `#0a0e09` so the whole window feels like one dark, cohesive space
- **Green that peeks, not screams** — lantern green is used only where it earns attention: function names, active selections, badges. Default text is a desaturated grayish-green you can read for hours
- **Amber as the true accent** — the cursor, active tab label, and breadcrumb selections use warm amber `#c9922a`, like a gas lamp casting light on stone
- **Fully themed terminal** — ANSI colors are reworked to stay in the Zaun palette instead of defaulting to stock VS Code colors
- **Themed widgets & popups** — autocomplete and hover popups use a dark green-tinted background `#0e1a0c` instead of generic gray
- **Semantic highlighting enabled** — variables, constants, and default library members each get their own distinct color layer on top of syntax highlighting
- **Broad language support** — fine-tuned scopes for JavaScript, TypeScript, Python, Rust, Java, PHP, Go, C/C++, C#, JSON, YAML, Markdown, and more

---

## Installation

### From the VS Code Marketplace

_(coming soon)_

### Manual install

1. Download or clone this repository
2. Copy the theme folder into your VS Code extensions directory:
   - **macOS / Linux:** `~/.vscode/extensions/`
   - **Windows:** `%USERPROFILE%\.vscode\extensions\`
3. Restart VS Code
4. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
5. Run **Preferences: Color Theme**
6. Select **Welcome to Zaun**

---

## Recommended Settings

This theme pairs best with a font that has some weight to it — the dark background makes lighter fonts harder to read.

```jsonc
{
  // Heavier fonts hold up better on dark backgrounds
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.7,

  // Bracket colors that don't fight the palette
  "editor.bracketPairColorization.enabled": true,

  // Amber cursor reads well with a gentle pulse
  "editor.cursorBlinking": "phase",
  "editor.cursorStyle": "line"
}
```

---

## Color Reference

### Syntax tokens

| Token                                   | Color                |
| --------------------------------------- | -------------------- |
| Keywords (`import`, `const`, `return`…) | `#c9922a`            |
| Functions & methods                     | `#4a9e52`            |
| Variables                               | `#3d7a44`            |
| Constants & numbers                     | `#c9922a`            |
| Strings                                 | `#6dc275`            |
| Classes & types                         | `#4a7a9b`            |
| Namespaces & modules                    | `#4a7a9b`            |
| Operators                               | `#3d7a44`            |
| Punctuation & brackets                  | `#8aab82`            |
| HTML/JSX tags                           | `#4a9e52`            |
| HTML/JSX attributes                     | `#c9922a`            |
| CSS property names                      | `#8aab82`            |
| CSS property values                     | `#c9922a`            |
| Comments                                | `#445544` _(italic)_ |
| RegExp                                  | `#4a7a9b`            |

### UI chrome

| Element                 | Color                      |
| ----------------------- | -------------------------- |
| Editor background       | `#0e130c`                  |
| UI chrome & sidebar     | `#0a0e09`                  |
| Active tab / selection  | `#182014`                  |
| Status bar              | `#111a0e`                  |
| Cursor                  | `#c9922a`                  |
| Active line number      | `#8a6120`                  |
| Error squiggles         | `#c0523a`                  |
| Warnings                | `#c9922a`                  |
| Primary button          | `#1e3a22` → text `#6dc275` |
| Progress bar            | `#4a9e52`                  |
| Icons                   | `#4a9e52`                  |
| Links                   | `#4a9e52`                  |
| Hover widget background | `#0e1a0c`                  |

---

## Inspiration

Zaun is the undercity beneath Piltover — where the hextech runoff drips through the cracks and people build lives in the dark. The color palette here is pulled from that environment: the green of shimmer and chemical light, the amber of gas lamps and rust, and the deep black of tunnels that never see the sun. If you've watched Arcane, you know exactly what this editor feels like.

---

## Also by ElizeCodes

Looking for something louder? Check out **[Jinx's Room](https://marketplace.visualstudio.com/items?itemName=ElizeSalvacion.jinxs-room-theme)** — the neon pink and teal counterpart to this theme, inspired by Jinx's hideout above the undercity.

---

## Contributing

Found a token that looks off, or a language scope that needs tuning? Open an issue or a pull request. The theme is a single JSON file with labeled scopes — easy to get into.

---

## License

MIT — do whatever you want with it.

---

## Support the Project

If this theme makes your late-night coding sessions feel a little more like Zaun,
☕ [Support this project on Ko-fi](https://ko-fi.com/I2I5WAZ5H)

_Made with too much caffeine and a very specific Arcane rewatch._
