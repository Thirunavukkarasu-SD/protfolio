# Thirunavukkarasu Portfolio Website (Multipage)

Apple-inspired, responsive multipage portfolio generated from `requirement_tk.txt`.

## Pages

- `index.html` — Home / Hero / What I Do / Flagship highlight
- `projects.html` — Project case studies
- `skills.html` — Skills and tech stack
- `about.html` — About, philosophy, services
- `contact.html` — Contact and availability
- `styles.css` — Shared design system and responsive layout
- `script.js` — Mobile nav toggle + subtle reveal-on-scroll animation

## Local setup

### Option 1 (recommended): run a local server

```bash
python3 -m http.server 4173
```

Open: `http://localhost:4173`

### Option 2
Open `index.html` directly in a browser.

## Deployment

### Netlify
- Drag and drop folder, or connect Git repo.
- Build command: *(empty)*
- Publish directory: `.`

### Vercel
- Import repository.
- Framework preset: Other
- Build command: *(empty)*
- Output directory: `.`

## Notes

- Content uses only data from the provided requirement file.
- UI follows minimalist Apple-style principles: single accent color, strong typography, wide whitespace, and subtle motion.
- Fully responsive for mobile, tablet, and desktop.
