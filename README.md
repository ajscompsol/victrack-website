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

## Before launch — three TODOs

Search `index.html` for `TODO`:

1. Replace `hello@example.com` (appears twice) with your real contact email.
2. Fill in the contact line: `[Your name] · [contact email] · [phone]`.
3. Replace `ABN [placeholder]` in the footer.

## Adding real screenshots

The hero and Trends sections currently use built-in CSS mock-ups so the site
works with zero assets. To swap in real app screenshots:

1. Create a `screenshots/` folder in the repo and upload your PNGs.
2. In `index.html`, follow the HTML comments marked
   "To use a real screenshot" — each shows the exact one-line replacement.

## Editing text

Open `index.html`, Ctrl+F for the words you want to change, edit, commit.
Colours live at the top of `style.css` under `:root`.
