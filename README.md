# valentine

A single-page Valentine card. No build step, no dependencies, no external assets — just `index.html`.

## What it does

The page asks "Will you be my Valentine?" with an animated character holding flowers and chocolate.

- The **No** button moves away when you try to click it, and stays inside the screen when the window is resized or rotated.
- Clicking **YES** shows "YAY!!! 💖" / "Happy Valentine's Day 🥰", switches the character to a kissing mood, plays a celebration sound, vibrates on devices that support it, and drops floating hearts down the page.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/

## Live preview (after merge — not live yet)

Static page, ready for GitHub Pages with no extra config. After this PR is merged, turn it on in a browser (Pages settings cannot be set through the GitHub App):

1. Repo **Settings → Pages → Build and deployment → Deploy from a branch**.
2. Branch: `main`, folder: `/ (root)`. Save.
3. The site will be at https://itsmeminsithu.github.io/valentine/

No preview URL is live until that step is done.

## License

MIT — see [LICENSE](LICENSE).
