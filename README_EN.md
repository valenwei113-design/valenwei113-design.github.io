# Valen Wei

Personal website — a visual journal of travel, life, and learning.

## Pages

| Page | File | Description |
|------|------|-------------|
| **Home** | `index.html` | Full-screen video slideshow cycling through 6 locations. Background music with spinning vinyl toggle. Click the name to enter the Journey tree. |
| **Journey** | `journey.html` | Interactive SVG tree with ~2,300 procedurally-generated leaves and 22 animated falling leaves. Navigation hub linking to all sub-pages. |
| **Vibe Coding** | `journey-vibe coding.html` | Web application projects — "Offer Coming" job search dashboard screenshots and link. |
| **Study in Germany** | `journey-germany.html` | Study abroad guide — university types, application process, APS certification, costs breakdown, ECTS & grading system, student life photos and videos. |
| **Nordic Study Tour** | `journey-norway.html` | Nordic folk high school (Folkehøgskole) deep-dive — history, philosophy, country distribution, photos and video. |
| **Work Exchange** | `journey-work exchange.html` | Work exchange experiences with photo galleries from Christchurch (New Zealand) and Odda (Norway). D3.js world map, practical tips for accommodation, activities, travel buddies, and useful apps. |
| **Travel Calendar** | `journey-calendar.html` | Morandi-colored travel log with 500+ city database, year/month grid, custom city entries, and localStorage persistence. |
| **Xiaohongshu** | `xiaohongshu.html` | Xiaohongshu (RED) QR code cross-promo page. |

## Navigation Flow

```
index.html → journey.html → ├─ journey-vibe coding.html
                                ├─ journey-germany.html
                                ├─ journey-norway.html
                                ├─ journey-work exchange.html
                                ├─ journey-calendar.html
                                └─ xiaohongshu.html
```

Each sub-page includes a "Back to Journey" footer link.

## Interactions

- **Video slideshow** — each clip plays to end then fades to the next, with music player and spinning vinyl animation
- **SVG tree** — ~2,300 static leaves generated procedurally along branches, plus 22 CSS-animated falling leaves with spin
- **Photo lightbox** — click any gallery image to zoom; prev/next navigation with arrow keys and Esc to close
- **D3.js world map** — interactive country highlights with hover tooltips on the Work Exchange page
- **Calendar city picker** — live search across 500+ cities, support for custom country entries, year summary stats
- **Card hover effects** — lift animations on university cards, tool cards, and city tags
- **Fade-up animations** — staggered entry animations on page load

## Tech

Plain HTML + Tailwind CSS CDN + D3.js (for maps) + SVG animations. No frameworks, no build step. Hosted on GitHub Pages.

## Directory Structure

```
├── index.html
├── journey.html
├── journey-calendar.html
├── journey-germany.html
├── journey-norway.html
├── journey-vibe coding.html
├── journey-work exchange.html
├── xiaohongshu.html
├── home/           # Homepage assets (videos, images, music)
├── journey/        # Germany & Norway page assets (photos, videos)
├── norway/         # Work Exchange — Norway photos
├── new zealand/    # Work Exchange — New Zealand photos
├── cairns/         # Queensland photos (unused in current pages)
├── offer coming/   # Vibe Coding page screenshots
├── README.md       # Chinese README
└── README_EN.md    # This file
```
