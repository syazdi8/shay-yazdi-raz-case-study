# Ruby & Pita Bot: a case study by Shay Yazdi Raz

A static, single-page case study about an independent product project: a private,
phone-first, human-approved editorial workspace for a Hebrew football podcast.
It is written for recruiters and hiring managers. It describes the project, what
was proven and what was not, and the decisions that testing forced.

The application itself is private. This repository holds only the case-study page.

## Preview

There is no build step and no dependency. Open `site/index.html` in a browser, or
serve the `site` folder with any static file server, for example:

```bash
cd site
python -m http.server 8000
```

then open the address the server reports, on port 8000.

## What is in `site/`

| File | Purpose |
|---|---|
| `index.html` | The whole page. No JavaScript, no external requests, no analytics or cookies. |
| `assets/style.css` | All styling, including print styles (use the browser's Print, then Save as PDF). |
| `assets/screens/*.jpg` | Three phone screenshots of the real application showing invented demo data only. |
| `assets/favicon.svg` | Tab icon. |

## Maintenance

The page is deliberately small. Before sharing it again:

1. Re-check every dated figure in the page (test count, pull-request count, status of the deployed pilot) and update the "Evidence reviewed" date in the footer.
2. Keep the proof levels honest: do not move something from "built and tested locally" to "deployed and observed" without direct evidence.

## Licence

All rights reserved by the author. The screenshots show invented data produced by the application's built-in demo mode. No third-party article text or publisher images are used.
