# Burtonian Brewery – Visit Quiz

Post-visit English quiz for Emerald Language Learning (Emerald UI style, English-only interface).

1. **Brewing steps** – drag (or tap) each term onto the matching illustrated step.
2. **Crossword** – 20 brewing and beer words.
3. **The beers** – 16 questions on ABV, bitterness, hops, aromas and colour.

Single file: open `index.html` in any browser, or serve it with GitHub Pages.

## Editing
Everything is at the top of the `<script>` in `index.html`: `STEPS`, `BEERS`, `QS`.
Beer data comes from burtonian.fr, which gives a bitterness rating /5 and no IBU.
If the brewer gives IBU figures, fill in the `ibu` field of each beer and an IBU question is added automatically.
The crossword grid is in the `CW` constant.
