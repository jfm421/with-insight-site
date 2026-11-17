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

## Before you publish

- The "Selected work" section holds draft examples that are not records of specific
  engagements. Confirm or correct each one, then delete the paragraph with the class
  `draft-note`.
- The "Discretion" panel in the About section makes four commitments about client
  information. Confirm that each one matches your contracts and practice.
