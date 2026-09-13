# George Askaroff — personal website

A static homepage with nine brief publication pages and three PDF downloads. No installation, build step, JavaScript, paid fonts or hosting subscription is required.

## Publish on GitHub Pages

1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload the contents of this folder to the repository root. Include `index.html`, `styles.css`, `favicon.svg`, `.nojekyll`, and all three folders: `assets`, `reading`, and `papers`. Upload the extracted files, not the ZIP.
3. In Settings → Pages, choose Deploy from a branch, then main and / (root). Save.
4. The site will appear at `https://YOUR-USERNAME.github.io/`. Publication can take up to 10 minutes.
5. Connect `georgeaskaroff.com` through GitHub Pages and your GoDaddy DNS settings when ready. Verify domain ownership in GitHub before completing the connection.

A differently named repository works at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`. All site links use relative paths, so both arrangements are supported.

[GitHub Pages setup instructions](https://docs.github.com/en/pages/quickstart)

## Edit content

- Homepage: edit `index.html`. Each research entry is an `<article class="work">`.
- Publication summaries: edit the corresponding HTML file in `reading/`. Its `.paper-blurb` paragraph contains the summary.
- Downloads: three PDFs are in `papers/`; replace a file using the same filename to retain its link. The NRR, frontier AI, epistemic fragmentation and journal landscape papers have no downloads.
- Contact and project links: edit their `href` values in `index.html`.
- Appearance: edit `styles.css`. Increment the `?v=` version in the stylesheet links if an old design remains cached.

The NRR and frontier AI paper display “In preparation for journal submission” and “Preprint available soon”. Other publication statuses follow the supplied information. The dissertation credits Dr Natasha Kuhrt. The Russia military essay uses author–date in-text citations. The original academic files remain separate and unchanged.

The two supplied project logos live in `assets/`; CSS controls their framing. No portrait, obsolete reader images, unpublished drafts, analytics or cookies are included in this folder.

All content and navigation work without JavaScript. Reduced-motion preferences are respected. A subtle page transition is available where browsers support it.
