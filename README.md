# naga-michi — Binder Insert Cropper

A single-page, browser-only tool for turning images into print-accurate
trading-card **binder inserts**. You lay images across a 3×3 pocket grid,
frame them, choose which gaps between slots stay or are joined, and print at
true physical size to cut out and slot in.

Everything runs client-side — **images never leave your machine** (they're read
locally via the file picker), and there is no backend.

## Use it

Open `index.html` in a browser, or visit the hosted page.

- **Select pockets:** click pockets (or drag) on the 3×3 grid, then **Place image**.
- **Frame:** drag the image to move it; use the zoom slider in the region bar.
- **Join slots:** click a red **✕** chip in a gap to remove that gap (the image
  becomes continuous across those slots). Hover a joined seam and click to
  restore the gap.
- **Print:** at **100% / Actual size**, A4 **landscape**. Pieces are packed
  row-by-row; joined slots print as one continuous piece, separate slots as
  individual 68×95 mm pockets.

Pocket size is 68×95 mm with a 5 mm gap (webbing) between slots — adjustable in
the toolbar.

## Hosting

It's a static site (one file). Deploy to any static host — GitHub Pages,
Cloudflare Pages, Netlify, etc. Nothing to build.
