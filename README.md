# aunoo banner generator

A single-file web app for generating aunoo social and article banners. Made by Lunch Money for aunoo.

## Templates

| Tab | Design | Sizes |
|---|---|---|
| General | Photo banner with title, date, and tag chip | WordPress 1617×1080 (default) · LinkedIn 1920×1080 |
| Bad Information | Newsletter banner with edition/date and hazard sticker | WordPress · LinkedIn |
| Daily Hot Topics | Red card with calendar date and typewriter illustration (optional title) | WordPress |
| Active Hot Topics | Blank red/light card stage for an uploaded image | WordPress |
| Curious.ai | Blue grid card with edition header, green tagline chip, title and subtitle | LinkedIn |

All designs, colors, and typography come from the aunoo Figma file and all assets are embedded — the page is fully self-contained and works offline once loaded (fonts load from Google Fonts when online).

## Usage

Open `index.html` in a browser, or host it anywhere static. Pick a tab, fill the fields, toggle WordPress/LinkedIn size where available, and Download PNG.

The General tab can pull photos from Pexels: expand "Pexels API key" and paste a free key from https://www.pexels.com/api/. The key is only stored in your browser's local storage and only sent to the Pexels API. You can also upload your own image instead.

## Deploying on GitHub Pages

1. Create a repository and upload `index.html` (and this README).
2. In the repository: Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The generator will be live at `https://<username>.github.io/<repository>/`.
