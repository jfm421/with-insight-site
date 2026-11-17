# with-insight-site

The website for With Insight, served by GitHub Pages at https://withinsight.com.au (see `CNAME`).

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts in one file. |
| `assets/fonts/` | Self-hosted fonts (Instrument Serif, Instrument Sans, Geist Mono) and their licence. |
| `assets/og.jpg` | The image shown when the link is shared. |
| `assets/apple-touch-icon.png`, `favicon.svg` | Icons. |

The site has no build step, no dependencies and no third-party requests.

## Preview on your computer

Run this command in the repository folder, then open http://localhost:8080 in a browser.

```bash
python3 -m http.server 8080
```

## Content rules

- The copy comes from the owner's work summary. Add no figure, date, result or quote
  that the summary does not contain.
- The "Selected work" section names no client, program, system, supplier or person.
  Keep any new example at the same level of generality.
- Three examples describe work in progress. Each one shows a status and claims no
  result. Add the result only when the work is complete.
