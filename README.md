# Buzzerio Static Site

This repository contains a simple static website that recreates the layout and content structure of the Buzzerio homepage using plain HTML and CSS.

## Structure

- `index.html`: The single-page site content.
- `styles.css`: The site styling and typography.

## How It Was Set Up

1. Created a single HTML page with the key sections from the original site (hero, approach, focus areas, about, mobility, contact).
2. Added a standalone CSS file to reproduce a calm, minimal look with custom typography, spacing, and card styling.
3. Kept everything framework-free and fully static for easy hosting.

## Run Locally

Open `index.html` directly in your browser.

If you want to serve it locally via a tiny static server:

```bash
python3 -m http.server 8000
```

Then visit:

```
http://localhost:8000
```

## Next Steps

Ask Claude to help with:

- Turn this into a responsive site with React.
- Break the site into easily-editable and updatable components.
- Add correct images.
- Fine-tune spacing, typography, and animations to better match the original.
- Set up a simple deployment workflow (e.g., GitHub Pages or Vercel).
