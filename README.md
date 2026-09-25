# Ndebe Fonts — Fonts for the Ndebe Script

Copyright Lotanna Igwe-Odunze

Copyright Ndebe Project

## Current families

- **Ndebe Rounded**: desktop TTF and web WOFF/WOFF2 in `Ndebe Rounded/Font/`.
- **Ndebe Soft Bold**: desktop TTF and web WOFF/WOFF2 in `Ndebe Soft Bold/Font/`.
- **Ndebe Plain**: earlier font files retained in their existing folder.

Rounded and Soft Bold are the approved drawings exported as **Version 1.000; RC1**.
They remain release candidates pending the platform checks below.
`FONT-MANIFEST.json` records SHA-256 hashes of these exact font exports.

## Installation and use

Install the TTFs for desktop use. Select **Ndebe Rounded** or **Ndebe Soft Bold** in your application. They are separate families, each with a Regular face; Rounded has weight 400 and Soft Bold has weight 700. Use the actual family rather than applying synthetic bold.

For websites, load `fonts.css`, which references the bundled WOFF2 and WOFF files. Use `font-family: 'Ndebe Rounded'; font-weight: 400` or `font-family: 'Ndebe Soft Bold'; font-weight: 700` and `font-synthesis: none`.

Ndebe uses private-use character assignments. The font alone does not change keyboard mappings: use the Ndebe keyboard or paste Ndebe text. ASCII digits are not reassigned by the font. The approved exports include nzobe forms, numerals 0–19 and small forms, mathematics, currencies including plain ƙ for kobo, teaching placeholders, replacement/missing-glyph designs, and nonbreaking spaces.

Editable-document embedding is permitted by the fonts' `OS/2.fsType=8`. This technical setting does not grant additional distribution or licensing rights.

## Validation and application notes

Both families passed 60,930 automated assertions each, plus native CoreText shaping and visual TextEdit checks.
Physical Keyman typing for ordinary and nzobe combinations, numerals 0–19, vigesimal punctuation, quotations and interpunct tested and confirmed.
RTF and TXT save/reopen tested and confirmed.

**RTF retains font formatting. TXT retains characters only:** select a Ndebe font again after opening plain text if the application displays missing-character boxes. This is expected and does not mean the text was lost.

**Pending Verifications:**
- [] Windows
- [] Pages
- [] Physical mobile-device input
- [] Actual embedded-font document portability remain unverified.

The fonts do not contain an OpenType MATH table; stretchable equation layout depends on the receiving application.
Native Keyman quotation alternation has a 64-character context limit.
