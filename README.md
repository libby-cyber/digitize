# Digitize

A single-page tool for photographing a paper pattern piece and exporting it as a DXF
for AccuMark. All processing happens in the browser on the device; no photo is uploaded.

## Deploy

Static site, no build step. Vercel serves `index.html` at the root.

## Update

Edit `index.html`, commit, and push to `main`. Vercel redeploys automatically and the
home-screen icon picks up the new version the next time it is opened.
