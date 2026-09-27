# CBB Toolkit

AIMS International's Cross-Border Business (CBB) toolkit, as a set of copy-paste
AI prompts. No engineering or CLI needed to use it — open the page, copy a
prompt into Claude or ChatGPT, paste in your own details, send.

Live page: https://spiritexec.github.io/cbb-toolkit/
PDF version: https://spiritexec.github.io/cbb-toolkit/CBB-Toolkit.pdf

## Contents

- `index.html` — the toolkit page itself (single file, no build step)
- `CBB-Toolkit.pdf` — a print export of the same page, for anyone who'd rather
  have a file than a link. Regenerate after editing `index.html`:
  `msedge --headless --disable-gpu --no-pdf-header-footer --print-to-pdf=CBB-Toolkit.pdf file:///<path>/index.html`
- `brand/aims-logo.png`, `brand/AIMS-CBB-deck-template.pptx` — source brand assets
- `brand/brand-kit.zip` — the two files above, zipped, linked from the page's
  "before you start" section so people can drop them into their own Claude/ChatGPT
  Project for consistent look-and-feel in whatever they generate
