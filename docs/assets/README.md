# Asset Provenance

- `social-preview.png` (1280x640, <1MB) — rendered deterministically from `card.svg` via `rsvg-convert` + `oxipng`. No AI-generated pixels, no stock imagery, no third-party fonts embedded (system font stack: Inter/Helvetica/Arial, JetBrains Mono/SF Mono fallback chain).
- `card.svg` — original work for this repository, CC0 like the rest of the repo.

Regenerate:

```bash
rsvg-convert -w 1280 -h 640 docs/assets/card.svg -o docs/assets/social-preview.png
oxipng -o2 --strip safe docs/assets/social-preview.png
```
