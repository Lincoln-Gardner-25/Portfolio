# Portfolio — Project Briefing

## What is this?
Lincoln Gardner's personal portfolio website. Showcases projects, skills, and background.
Static HTML/CSS — no build system, no framework, no dependencies.

## Tech Stack
- Pure HTML5 + CSS3 (no frameworks)
- Google Fonts: Inter (400, 500, 600, 700)
- No JavaScript (intentionally minimal)
- Hosted on GitHub Pages via `Lincoln-Gardner-25/Portfolio` repo

## File Structure
| File | Purpose |
|------|---------|
| `index.html` | Home — profile photo, tagline, social links, featured projects |
| `about.html` | About — bio, background, skills, contact |
| `projects.html` | Projects list — all project cards |
| `images/` | Static assets (profile photo goes here as `profile.jpg`) |

## Design System
- Font: Inter (system fallback stack)
- Max content width: 900px (main), 1200px (nav)
- Background: `#fff`
- Text: `#333` (primary), `#666` (secondary/muted)
- Links: `#0066cc`
- Border/divider: `#e5e5e5`
- Border radius: `8px` (cards), `6px` (buttons)
- Card hover: `box-shadow: 0 4px 12px rgba(0,0,0,0.05)` + border `#ccc`

## Pages
- **Home** (`index.html`): Profile section (photo placeholder at `images/profile.jpg`) + Featured Projects section
- **About** (`about.html`): Bio, background, skills list, contact links
- **Projects** (`projects.html`): Full project grid — one card per project

## What's Built
- [x] Static HTML scaffold — home, about, projects pages
- [x] Sticky navbar with active state
- [x] Profile section with social links (LinkedIn + GitHub)
- [x] Project cards with hover effects
- [x] Responsive mobile layout (breakpoint: 600px)
- [x] GitHub repo: https://github.com/Lincoln-Gardner-25/Portfolio

## What Needs Doing
- [ ] Add profile photo to `images/profile.jpg` (placeholder currently showing)
- [ ] Update LinkedIn URL (`linkedin.com/in/yourprofile` is a placeholder)
- [ ] Add Everest project card to `index.html` featured section and `projects.html`
- [ ] Consider deploying via GitHub Pages for a live public URL

## Dev Notes
- To preview locally: open `index.html` directly in browser, or run `python3 -m http.server 8080` in the portfolio dir
- `.claude/launch.json` is configured to serve on port 8080 via Python
- No build step — edit HTML directly
- GitHub repo canonical name is `Portfolio` (capital P) — remote URL redirects automatically from lowercase
