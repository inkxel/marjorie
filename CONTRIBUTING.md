# Contributing to Marjorie

Thanks for your interest in Marjorie. This is a small, single-style typeface, so contributing is simple.

## Reporting a problem

Open a [GitHub issue](https://github.com/inkxel/marjorie/issues) and include:

- What you saw and what you expected (a screenshot helps for glyph problems).
- The font file and format you used (`.otf`, `.ttf`, `.woff2`, `.woff`).
- Your app or browser and operating system.

Useful reports include spacing or kerning problems, missing characters, outline glitches, and installation trouble.

## Suggesting changes

For anything beyond a typo fix, open an issue first so we can agree on the direction before you spend time on it. Design decisions (shapes, spacing, new glyphs) rest with the designer, David Tucker.

Pull requests for documentation fixes are welcome directly.

## Source files

The source of truth is [`sources/Marjorie.glyphs`](sources/Marjorie.glyphs), edited in [Glyphs](https://glyphsapp.com/). Please don't hand-edit the binaries in `fonts/`; they are exported from the source. See the [README](README.md#building-from-source) for how to build.

## Making your own version

The font is licensed under the [SIL Open Font License 1.1](OFL.txt), so you are free to modify and redistribute it. Please note:

- **"Marjorie" is a Reserved Font Name.** A modified version must be released under a different name.
- Derivatives must stay under the OFL.
- Keep the copyright notice and license with any redistributed font files.
- If you change the font, add yourself to the acknowledgements in [`FONTLOG.txt`](FONTLOG.txt) (name, email, web address, and a short description of your changes).
