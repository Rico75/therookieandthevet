# The Rookie And The Vet Podcast

Static site for the **The Rookie And The Vet Podcast** YouTube playlist and episode archive.

## Project structure

The site is served from `docs/`:

- `docs/index.html` — homepage
- `docs/episodes/` — episode archive and individual episode pages
- `docs/hosts/` — host/archetype hub and character pages
- `docs/about/` — creator/about page
- `docs/contact/` — contact and mailing list links
- `docs/assets/` — CSS, images, and site assets
- `docs/rss/` — RSS landing page and feed XML files

## Playlist metadata

- **Title:** The Rookie And The Vet Podcast
- **Channel:** The Rookie And The Vet Podcast Talk
- **Playlist:** `PLK17qjXUqfN_ZyNf4JJHgXMbZ6KUm1p5T`
- **Thumbnail:** `https://i.ytimg.com/vi/clUWeHUAGI4/hqdefault.jpg`

## Run locally

From the repository root:

```bash
cd docs
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Publishing

Deploy the `docs/` directory as the site root for GitHub Pages or any static host.
