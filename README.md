# Victorian Curriculum Data Tracker — sales website

Plain HTML + CSS. No build step, no frameworks — what you see in the files is
what appears on the page.

## Files

- `index.html` — all the page content (text, sections, links)
- `style.css` — colours, fonts and layout (brand kit already applied)
- `README.md` — this file

## Get it live

1. Upload these files to your GitHub repository
   (repo page → **Add file → Upload files** → drag them in → **Commit changes**).
2. In Cloudflare Pages: **Create a project → Connect to Git** → pick the repo.
3. Framework preset: **None**. Build command: leave blank. Output directory: leave blank (root).
4. Deploy. You'll get a live `*.pages.dev` URL immediately.
5. Add your custom domain in the Pages project → **Custom domains**.

Every future commit to the repo republishes the site automatically.

## Before launch — one TODO

Contact email is `admin@vcdatatracker.com.au` throughout (contact section + FAQ).

1. Replace `ABN [placeholder]` in the footer.

## Screenshots

The hero and the click-through Tour section use REAL screenshots of the
Windows app, in the `screenshots/` folder:

- `screenshots/overview.png` — the colour-coded results view (hero)
- `screenshots/trends.png` — Trends (tour slide 1)
- `screenshots/insights.png` — Insights quadrant (tour slide 2)
- `screenshots/statistics.png` — Statistics dashboard (tour slide 3)
- `screenshots/profile.png` — student profile (tour slide 4)
- `screenshots/all-semesters.png` — All semesters view (tour slide 5)
- `screenshots/below-level.png` — Below level watchlist (tour slide 6)

To update them, replace the PNG files (keep the same names). They're
captured with the app licensed to a demo school and only fake student names, so
they're safe to publish. Keep them under ~500 KB each for fast loading.

## Editing text

Open `index.html`, Ctrl+F for the words you want to change, edit, commit.
Colours live at the top of `style.css` under `:root`.
