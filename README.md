# Burtonian Brewery – Visit Quiz

Emerald Language Learning's post-visit English quiz for the Burtonian Brewery (Castres): brewing steps (drag and drop), crossword and questions on the five beers. English-only interface.

- **Website:** https://emeraldlanguagelearning.github.io/Emerald-Burtonian-Quiz/ (`index.html` at the top of the repo; Settings → Pages → Source: GitHub Actions).
- **Android app:** a WebView around the same `index.html`, copied into the app when the APK is built.
  - Every push builds the APK: **Actions → Build APK → latest run → Artifacts → BurtonianQuiz-apk**.
  - To publish a download link: **Actions → Publish APK release → Run workflow**, with the build run's ID and a tag such as `v1.0`.
- **Editing:** the quiz data (`STEPS`, `BEERS`, `QS`, `CW`) is at the top of the `<script>` in `index.html`. Beer facts come from burtonian.fr, which gives a bitterness rating out of 5 and no IBU; fill in each beer's `ibu` to add an IBU question.
- Illustrations are original SVG drawings; the logo is Emerald Language Learning's own.

## Licence

© 2026 Emerald Language Learning. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (see [LICENSE](LICENSE)). Third-party material keeps its own licence.
