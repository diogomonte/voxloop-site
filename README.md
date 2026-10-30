# voxloop-site

The website for **VoxLoop**, the app that turns your voice into a looping beat.

A static site with no build step: `index.html` (purpose, how it works, tutorial) and `brand.html` (mark, colour, type, voice). Styles live in `assets/styles.css`; colours are the app's own `AppTheme` tokens.

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. **Settings → Pages → Build and deployment**: Source *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The site appears at `https://<user>.github.io/voxloop-site/`.

`.nojekyll` is included so GitHub serves the files as they are.

## Preview locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Assets

- `assets/mark.svg`: the waveform mark with its gradient; `assets/mark-mono.svg` takes `currentColor`.
- `assets/app-icon.png`: the app icon (same art as the iOS and Android launcher icons).
- `assets/screens/`: screenshots from the Android emulator, staged with a demo song (boom, tss, kah, hey at 96 BPM). Retake them when the studio screen changes.
