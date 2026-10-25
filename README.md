# valentine

A single-page, interactive Valentine card. No build step, no dependencies,
no external assets — just `index.html`.

## What it does

The page asks "Will you be my Valentine?" with an animated character holding
flowers and chocolate.

- The **No** button dodges and keeps moving when you try to click it, and is
  kept inside the screen on resize/rotate.
- Clicking **YES** shows "YAY!!! 💖" / "Happy Valentine's Day 🥰", switches
  the character to a kissing mood, plays a celebration sound, vibrates where
  supported, and showers floating hearts.

## Run it locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/

## Live preview (after merge — not live yet)

This is a static page, so it is GitHub Pages-ready with no extra config.
After this PR is merged, enable it in a browser (Pages settings cannot be
set via the GitHub App):

1. Repo **Settings → Pages → Build and deployment → Deploy from a branch**.
2. Branch: `main`, folder: `/ (root)`. Save.
3. The site will be at https://itsmeminsithu.github.io/valentine/

No preview URL is live until that post-merge step is done.

## License

MIT — see [LICENSE](LICENSE).
