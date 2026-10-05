# Pixel Forge

An original, touch-first pixel-by-number puzzle inspired by satisfying color-clear games. It is a dependency-free Progressive Web App (PWA), designed for iPhone and playable offline after the first visit.

## Play locally

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Run the included **Deploy to GitHub Pages** workflow, or push to `main`.
4. Open the deployed URL in Safari on iPhone.
5. Tap **Share → Add to Home Screen**, keep **Open as Web App** enabled, then tap **Add**.

## Features

- Four original 20×20 pixel-art missions
- Tap or drag to fill matching numbered pixels
- Hints, zoom, sound, haptics, progress saving, and mission selection
- Responsive phone/tablet/desktop layout
- Web app manifest, Home Screen icon, and offline service worker
- No framework, ads, analytics, account, or external assets

## Customize

Edit `rawLevels` and `COLORS` in `app.js`. Each level contains 20 strings of 20 digits: `0` is blank and `1`–`9` select palette colors.

## License

MIT. The code and artwork in this repository are original and do not reuse assets or branding from the reference game.
