# sehokim09.github.io

Source for Seho Kim's academic website (University of Hawaiʻi at Mānoa, HIGP). Built with Jekyll and published automatically by GitHub Pages whenever `main` changes.

## Updating content

Most updates are a single edit to a file in `_data/`. You can edit them directly on github.com (pencil icon → Commit changes), and the site rebuilds in about a minute.

| To change… | Edit |
|---|---|
| News | `_data/news.yml` (newest first; home page shows 3) |
| Publications | `_data/publications.yml` (newest first; home page shows 3) |
| Lab members | `_data/people.yml` |
| Courses | `_data/teaching.yml` |
| Research text | `research.html` |
| Home page text | `index.html` |
| Email, Scholar and HIGP links, menu | `_config.yml` |
| Colors and fonts | `assets/css/style.css` (variables at the top) |

Each data file has a commented example entry at the top to copy.

## Adding photos later

Put images in `assets/img/`. Spots designed for photos are marked `PHOTO LATER` in `index.html` (hero and the two mission panels).

## Preview locally (optional)

```bash
gem install bundler jekyll
jekyll serve
```

Then open http://localhost:4000.

## Theme

Colors follow the SK-UHM presentation theme: Mānoa Green `#024731`, Basalt Ink `#14202B`, Reef Teal `#1C8C8C`, Sunrise Gold `#F2A541`, Mist `#EEF3F1`.
