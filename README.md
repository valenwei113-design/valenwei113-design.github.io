# Valen Wei

Personal website — a visual journal of travel, life, and learning.

## Pages

| Page | File | Description |
|------|------|-------------|
| **Home** | `homepage.html` | Full-screen video slideshow cycling through 6 locations. Background music with spinning vinyl toggle. Click the name to enter the Journey tree. |
| **Journey** | `journey.html` | Interactive SVG tree with ~2300 procedurally-generated leaves and 22 animated falling leaves. Navigation hub linking to all sub-pages. |
| **Vibe Coding** | `journey-vibe coding.html` | Web application projects — "Offer Coming" job search dashboard screenshots and link. |
| **德国留学** | `journey-germany.html` | Study abroad in Germany — university types, application process, APS certification, costs, ECTS & grading system, student life photos and videos. |
| **挪威游学** | `journey-norway.html` | Nordic folk high school (Folkehøgskole) deep-dive — history, philosophy, country distribution, photos and video. |
| **打工换宿** | `journey-work exchange.html` | Work exchange with photo galleries from New Zealand (Christchurch) and Norway (Odda). D3.js world map, travel tips for accommodation, activities, travel buddies, and apps. |
| **旅居日历** | `journey-calendar.html` | Morandi-colored travel log with 500+ city database, year/month grid, custom city entries, and localStorage persistence. |
| **小红书** | `xiaohongshu.html` | Xiaohongshu QR code cross-promo page. |

## Navigation Flow

```
homepage.html → journey.html → ├─ journey-vibe coding.html
                                ├─ journey-germany.html
                                ├─ journey-norway.html
                                ├─ journey-work exchange.html
                                ├─ journey-calendar.html
                                └─ xiaohongshu.html
```

## Interactions

- Video slideshow (each clip plays to end then fades to next)
- SVG tree with dynamic leaf generation and CSS falling-leaf animations
- Photo lightbox with prev/next navigation and keyboard shortcuts (← → Esc)
- D3.js interactive world map with country highlight and tooltip
- Calendar city picker with live search and custom country entries
- Card hover lift effects and fade-up entry animations
- Music player with spinning vinyl disc animation

## Tech

Plain HTML + Tailwind CSS CDN + D3.js (maps) + SVG animations. No frameworks, no build step. Hosted on GitHub Pages.

## Directory Structure

```
├── homepage.html
├── journey.html
├── journey-calendar.html
├── journey-germany.html
├── journey-norway.html
├── journey-vibe coding.html
├── journey-work exchange.html
├── xiaohongshu.html
├── home/           # Homepage assets (videos, images, music)
├── journey/        # Germany & Norway page assets
├── norway/         # Work exchange — Norway photos
├── new zealand/    # Work exchange — New Zealand photos
├── cairns/         # (unused currently)
├── offer coming/   # Vibe Coding page screenshots
└── README.md
```
