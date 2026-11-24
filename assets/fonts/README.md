Subsets (ASCII + middle dot) of two fonts from Google Fonts, embedded into the SVG cards:

- Unbounded 800, by NamelessStudio. SIL Open Font License 1.1.
- Space Grotesk (variable), by Florian Karsten. SIL Open Font License 1.1.

`metrics.json` holds each glyph's advance width (in em) so `scripts/build_profile.py`
can wrap text without needing fontTools.
