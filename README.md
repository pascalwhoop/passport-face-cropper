# Passport Photo Cropper

A small, free passport photo cropping tool that runs entirely in the browser.

**Use it:** https://pascalwhoop.github.io/passport-face-cropper/

Drop in a JPG, PNG, or WebP, mark your head and chin, adjust the crop, and download a JPG. Includes US 2 × 2-inch, UK 35 × 45-mm, German 35 × 45-mm, Spanish 26 × 32-mm, Canadian 50 × 70-mm, and Chinese 33 × 48-mm printed-photo templates. A general Europe 35 × 45-mm crop is provided as a starting point; European countries set their own head-size and digital-photo rules.

Country templates only measure what their linked official guidance publishes. Spain’s linked guidance does not state a head-height range, so the cropper does not claim the photo passes that measurement. Check the authority’s rules for the exact application before printing or submitting. These templates do not change any photo pixels except by cropping and resizing.

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

## Official photo-size references

- US: [U.S. Department of State](https://travel.state.gov/en/passports/how-apply/photos.html)
- UK: [HM Passport Office](https://www.gov.uk/photos-for-passports/photo-requirements)
- Germany: [Federal Foreign Office](https://spanien.diplo.de/es-es/service/02-paesseausweise/2594622-2594622)
- Spain: [Ministry of the Interior](https://www.interior.gob.es/opencms/es/servicios-al-ciudadano/tramites-y-gestiones/pasaporte/procedimiento-de-expedicion/)
- Canada: [Immigration, Refugees and Citizenship Canada](https://www.canada.ca/en/immigration-refugees-citizenship/services/canadian-passports/photos.html)
- China: [Government service guidance](https://gjzwfw.www.gov.cn/fwmh/item/v3/item_1110000000001301271001002002000.do)

## License

MIT.
