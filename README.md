# Aspect Ratio Calculator

Turn pixel dimensions into a simplified ratio, or solve for a missing dimension from a ratio. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/aspect-ratio-calculator/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

Two modes:

- **Width and height to ratio.** Type a width and a height (for example 1920 and 1080) and the tool shows the simplified ratio (16:9), the decimal ratio, and a scaled preview box. Preset buttons (16:9, 4:3, 21:9, 1:1, 9:16, 3:2, 2:1) snap the height to match your current width.
- **Solve for a missing dimension.** Set a ratio (for example 16 and 9), then enter either a known width or a known height. The tool fills in the other dimension. Leave one field blank and type in the other to flip which one gets solved.

Everything updates live as you type.

## Why this exists

Most aspect ratio calculators online are buried under ad units and load a dozen tracking scripts to do grade-school arithmetic. This is the same idea, single file, no analytics, no signup, MIT licensed.

## Privacy

Everything runs in your browser. The numbers you type never leave your machine. Verify by viewing the page source or by opening DevTools and watching the network tab, no requests are made.

## Run locally

```bash
git clone https://github.com/0xelitesystem/aspect-ratio-calculator
cd aspect-ratio-calculator
# Open index.html in your browser, or:
python -m http.server 8000
```

## Contribute

Issues and PRs welcome:

- More common presets
- Rounding or precision edge cases
- UI improvements (keep it minimal, no frameworks)
- Translations

Don't add: analytics, tracking, external scripts, npm dependencies. The whole point of this tool is no surveillance.

## Build

There is no build. It's a single HTML file.

## License

MIT.

## Related

- [color-format-converter](https://github.com/0xelitesystem/color-format-converter), convert between HEX, RGB, HSL, and HSV
- [url-parser-and-query-editor](https://github.com/0xelitesystem/url-parser-and-query-editor), break a URL into parts and edit query params
- [word-and-character-counter](https://github.com/0xelitesystem/word-and-character-counter), count words, characters, and reading time
