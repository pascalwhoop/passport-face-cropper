# Passport Photo Cropper

A small, free passport photo cropping tool that runs entirely in the browser.

**Use it:** https://pascalwhoop.github.io/passport-face-cropper/

Drop in a JPG, PNG, or WebP, mark your head and chin, adjust the crop, and download a JPG. Includes US 2 × 2-inch and UK 35 × 45-mm printed-photo templates, an eye-level guide, free positioning, and keyboard nudging.

## Privacy

Photos never leave the device. No uploads, AI models, third-party scripts, analytics, cookies, accounts, or browser storage. The page uses a Content Security Policy that blocks network connections and workers. GitHub Pages serves the website and may log ordinary page requests under GitHub's privacy policy; it does not receive selected photos.

Save `index.html` and open it in a browser to use it offline. Downloaded photos remain on the user's device.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` from this directory. No install or build step is required.

## Passport requirements

This tool checks framing based on manually placed markers. It does not guarantee acceptance or verify expression, background, lighting, photo age, or image quality. It does not retouch faces or replace backgrounds. Check the official requirements for your specific application; online US passport renewal has different upload instructions.

## Publishing and search

GitHub Pages publishes the repository's `main` branch from `/`. The page includes a descriptive title, privacy-focused description, canonical URL, social metadata, WebApplication structured data, and a sitemap at `/passport-face-cropper/sitemap.xml`. These make the page understandable to crawlers; they do not guarantee Google indexing or ranking.

## Templates

Add templates in the `templates` object in `index.html`. Each template owns its crop dimensions, pixel output, head limits, and official source link.

## License

MIT.
