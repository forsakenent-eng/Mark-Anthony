# markanthonymartinez.com

Static rebuild of markanthonymartinez.com, made to be hosted for free on GitHub Pages instead of the paid WordPress service.

## What's here
- `index.html` — the homepage, rebuilt from the WordPress/Elementor export you provided
- `about.html` — the About page, rebuilt from the content you provided
- `consulting.html` — the former "Speaker" page, reframed as a "Consulting" page per your note (renamed in the nav, headline, and form). Ends in a static mailto-based request form since there's no backend to process a real form submission.
- `press-media.html` — the Press & Media page, with the CXO Dispatch feature and a YouTube video link
- `contact.html` — the Contact page, rebuilt from the content you provided, with the same static mailto-based form approach as Consulting (First/Last name, email, company, website, phone, purpose dropdown, message)
- `privacy-policy.html` — the Privacy Policy page, rebuilt from the content you provided
- `assets/images/` — your header photo and headshot, pulled from the live site before cancellation
- `assets/css/style.css` — hand-written CSS that matches the original's fonts, colors, and layout (not a literal copy of the paid Elementor/UiCore/BDThemes plugin CSS, since that's licensed and wouldn't survive the WordPress cancellation anyway)

All six pages from the original nav are now built out with real content.

## Publishing on GitHub Pages
1. Create a new GitHub repo (e.g. `yourusername.github.io` for a root domain, or any name for a project site).
2. Push this folder's contents to it.
3. In the repo's Settings → Pages, set the source to the `main` branch, root folder.
4. Your site will be live at `https://yourusername.github.io/` (or `https://yourusername.github.io/repo-name/` for a project site).

If you want to keep `www.markanthonymartinez.com` as the URL, add a `CNAME` file containing that domain, and point your domain's DNS at GitHub Pages (GitHub's docs walk through the A/AAAA/CNAME records).

## Known gaps vs. the original
- **Both forms use a placeholder email address** (`hello@markanthonymartinez.com`) — in `consulting.html` and `contact.html`, each in two spots (a visible note on the page and the `<script>` block that builds the mailto link). Replace it with your real email in both files before publishing. Search for `hello@markanthonymartinez.com` across the folder to find every occurrence.
- The former "Speaker" page was renamed "Consulting" throughout (nav, headline, form) based on your note about reframing it — let me know if you'd rather keep "Speaker" or run them as two separate offerings instead.
- The Press & Media page's YouTube entry uses a generic "Video Feature" label since no title was provided — let me know the real title if you'd like it more specific.
