# DentisTree static website

Open `index.html` directly in a browser, or publish this folder to static hosting. The site uses HTML, CSS and vanilla JavaScript; there is no server or build step.

## Clinic details

Edit `js/config.js` to add the clinic phone, email, WhatsApp number and Google Maps embed URL. To enable the optional form handoff, set `formHandoff` to `mailto` or `whatsapp` after configuring the matching contact value. Form details are only placed into a link for the visitor to open; this site does not store or send form entries.

## Before deployment

Replace `https://www.example.com` in `sitemap.xml` and `robots.txt` with the confirmed production domain. The current contact and map values are intentional placeholders. Add verified clinical gallery photography only when it is available and appropriately approved.

## Supplied images

- `images/optimized/clinicians.webp` is the supplied team portrait.
- `images/optimized/consultation.webp` is the supplied patient consultation photograph.
- The original supplied PNGs remain in `images/`.
- `dentistree_logo.svg` is the supplied logo and is used as the favicon and wordmark source.
