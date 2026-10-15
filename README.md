# Marjorie

![Marjorie specimen: the word "MARJORIE" in large capitals above the uppercase, lowercase and figure set, in black on a peach background](documentation/specimen.jpg)

**Marjorie** is a display typeface with Art Deco bones — high-waisted proportions, classical Roman skeletons, and flared strokes, with geometric inspiration in its round forms. Drawn for headlines, posters, logotypes, and packaging, where a single confident voice carries the layout.

Free and open source under the [SIL Open Font License 1.1](OFL.txt). Current version: 1.001.

## At a glance

| | |
| --- | --- |
| **Category** | Display typeface, Latin script |
| **Styles** | One: Regular |
| **Best at** | Headlines, posters, logotypes, packaging |
| **License** | SIL Open Font License 1.1 (free for personal and commercial use) |
| **Designer** | David Tucker, [tvcker.com](https://tvcker.com) |

## Specimen

The image above shows the basic character set: the name set large, then uppercase, lowercase, figures and a few punctuation marks. The capitals are open and widely spaced, with tall, slender proportions and classical Roman skeletons. The geometric influence shows in the round shapes, such as the `O` and the bowls of letters like `a`, `b`, `d`, `p` and `q`. Stroke ends are slightly flared, which gives words a carved, poster-like rhythm. The lowercase is single-storey and open, and a few letters (`J`, `g`, `y`) drop below the baseline.

Character coverage:

- Uppercase and lowercase Latin (`A–Z`, `a–z`)
- Figures `0–9` and some punctuation (as shown in the specimen)

Marjorie is built for display sizes. It sings as a headline and on a poster; for long passages of body text, reach for something else.

## Styles and files

There is a single style, **Regular** (upright), supplied in four formats:

| File | Format | Use it for |
| --- | --- | --- |
| [`fonts/Marjorie-Regular.otf`](fonts/Marjorie-Regular.otf) | OpenType | Desktop apps and print. Recommended. |
| [`fonts/Marjorie-Regular.ttf`](fonts/Marjorie-Regular.ttf) | TrueType | Desktop apps that prefer TrueType, and broad compatibility. |
| [`fonts/Marjorie-Regular.woff2`](fonts/Marjorie-Regular.woff2) | WOFF2 | Websites. Smallest, supported by current browsers. |
| [`fonts/Marjorie-Regular.woff`](fonts/Marjorie-Regular.woff) | WOFF | Websites that need a fallback for older browsers. |

## Install

**Desktop.** Download [`Marjorie-Regular.otf`](fonts/Marjorie-Regular.otf) (or the `.ttf`) from [`fonts/`](fonts/), then:

- **macOS:** double-click the file and choose *Install Font*.
- **Windows:** right-click the file and choose *Install* (or *Install for all users*).
- **Linux:** copy it to `~/.local/share/fonts/` and run `fc-cache -f`.

Restart any open design apps so they pick up the new font.

**Web.** Copy the `.woff2` and `.woff` files to your site and add an `@font-face` rule:

```css
@font-face {
  font-family: "Marjorie";
  src: url("Marjorie-Regular.woff2") format("woff2"),
       url("Marjorie-Regular.woff") format("woff");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

h1 {
  font-family: "Marjorie", sans-serif;
}
```

## License

Marjorie is licensed under the **SIL Open Font License, Version 1.1** — see [`OFL.txt`](OFL.txt). In plain language:

- **You can** use it in personal and commercial work, in print, on the web, in apps and in logos, at no cost.
- **You can** study it, modify it, and redistribute it, including bundled with your own software or documents.
- **You can't** sell the font by itself.
- **Derivatives** must stay under the OFL and must not use the name "Marjorie", which is a **Reserved Font Name**. Rename any modified version.

This is a summary, not legal advice; the text of [`OFL.txt`](OFL.txt) is what applies.

## Credit

Credit is appreciated but not required for ordinary use of the font, including commercial work. If you would like to credit it, something like this works:

> Set in Marjorie by David Tucker (github.com/inkxel/marjorie), SIL Open Font License 1.1.

If you redistribute the font files themselves, keep [`OFL.txt`](OFL.txt) and its copyright notice with them.

## Building from source

The source of truth is [`sources/Marjorie.glyphs`](sources/Marjorie.glyphs), drawn in [Glyphs](https://glyphsapp.com/).

- **In Glyphs:** open the source and `File → Export` to OTF / TTF / Web (WOFF2).
- **Command line** ([fontmake](https://github.com/googlefonts/fontmake)):

  ```sh
  pip install fontmake
  fontmake -g sources/Marjorie.glyphs -o otf ttf
  ```

## Contributing

Bug reports and suggestions are welcome; see [`CONTRIBUTING.md`](CONTRIBUTING.md). Version history is in [`FONTLOG.txt`](FONTLOG.txt).

## Author

Designed by **David Tucker** — type design and creative technology.
[tvcker.com](https://tvcker.com) · [@inkxel](https://instagram.com/inkxel)
