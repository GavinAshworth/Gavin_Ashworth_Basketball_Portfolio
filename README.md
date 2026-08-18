# Gavin Ashworth — Basketball Portfolio

Static HTML/CSS/JS portfolio designed for GitHub Pages.

## Why this structure

The site is intentionally content-first. It is built to show actual basketball work rather than function as an expanded resume. The main work page is organized around evidence: scouting reports, player-evaluation video, game-day tracking, and basketball media.

## Files

- `index.html` — homepage
- `work.html` — basketball work / case studies
- `experience.html` — playing, coaching, professional, and academic background
- `resume.html` — resume and contact page
- `css/styles.css` — complete design system and responsive layout
- `js/site.js` — mobile navigation only
- `assets/` — place your PDFs, photos, videos, and other media here

## Adding your own content

The site contains bracketed placeholders instead of invented personal prose. Replace those with your own words.

### Recommended media folders

Create folders such as:

```text
assets/
  photos/
  scouting/
  player-videos/
  ballogy/
  basketball/
```

Keep filenames short and web-friendly. Example:

```text
assets/scouting/target-time-river-lions.pdf
assets/photos/sea-bears-headshot.jpg
assets/player-videos/player-01.mp4
```

### Embedding local video

Replace a video placeholder with:

```html
<video controls preload="metadata" poster="assets/player-videos/player-01-poster.jpg">
  <source src="assets/player-videos/player-01.mp4" type="video/mp4">
</video>
```

### Showing a PDF

Replace a placeholder link with:

```html
<a class="button button-primary" href="assets/scouting/target-time-river-lions.pdf">Open report PDF</a>
```

For very large PDFs/videos, consider external hosting and link to them instead of storing large files directly in the GitHub repository.

## GitHub Pages

This version requires no build step. Commit the repository and enable GitHub Pages from the repository's Pages settings using the branch/folder that contains `index.html`.

A custom domain can be added later without changing the site structure.

## Content strategy

Prioritize actual evidence of work:

1. Target Time Report — lead case study.
2. Prospective player videos — a small curated selection, not every file.
3. Game-day stat tracking — recreate a clean public version if the original sheet is gone.
4. Coaching/player-development work — photos + concise explanation.
5. Playing background — use photos to establish basketball credibility without making the site feel like an athlete recruiting page.
6. Ballogy — select representative posts and explain the communication/content role.
7. Future analytics/technical projects — add these as they become relevant.

Do not include confidential player information, internal team information, or material that your employer does not permit you to publish.
