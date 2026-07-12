# Whiteley Reunion 2026 Digital Schedule

Static website version of the Whiteley Reunion 2026 schedule.

## Recommendation

Use the HTML page as the primary link from the landing page.

Reasons:

- Better accessibility: semantic headings, real text, skip link, and readable download links.
- Better mobile behavior: schedule rows collapse into phone-friendly cards.
- Better navigation: users land directly on the schedule instead of opening Google Drive or a PDF viewer.
- Still print-safe: the original 11 x 17 PDF is included as a direct download.

Do not maintain a separate PDF-only branch unless a hosting provider requires it. Keeping the HTML, PDF, DOCX, and artwork in one static repo is simpler and less error-prone.

## Files

- `index.html`: primary web schedule.
- `styles.css`: responsive and print-aware styling.
- `assets/whiteley-reunion-2026-schedule.pdf`: poster PDF download.
- `assets/whiteley-reunion-2026-schedule.docx`: editable Word document download.
- `assets/whiteley-deep-roots-transparent.png`: transparent family-tree artwork.

## Local Preview

Open `index.html` directly in a browser, or serve the folder with any static file server.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This is a zero-build static site. It can be hosted by GitHub Pages, Sites, Netlify, Vercel, Cloudflare Pages, or any static web server.
