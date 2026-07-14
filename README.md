# Paul E. Patton — Portfolio

A static, four-page academic portfolio. All files live in this folder and the site
opens by double-clicking `index.html`.

## Files

- `index.html` — home page, with the portrait placeholder and a short bio
- `about.html` — biography, research interests, education, fellowships, teaching
- `publications.html` — every peer-reviewed paper, abstract, feature article and
  selected talk, with links to the publisher of record where one exists
- `contact.html` — email, phone, mailing address, and affiliations
- `styles.css` — the shared stylesheet for all pages

## Adding the photograph

The home page has a placeholder where the portrait will go. To replace it:

1. Save the photograph in this folder as `portrait.jpg` (a 4:5 ratio works best —
   roughly 800 × 1000 px is plenty).
2. Open `index.html` and find this block:

   ```html
   <div class="portrait" aria-label="Portrait of Paul E. Patton">
     <!-- Replace the line below with: <img src="portrait.jpg" alt="Paul E. Patton"> -->
     <span class="portrait__placeholder">Photograph<br>to be added</span>
   </div>
   ```

3. Replace the `<span>…</span>` line with `<img src="portrait.jpg" alt="Paul E. Patton">`.

That is the only edit needed; the image will be cropped and centred by the CSS.

## Editing text

All copy is in plain HTML inside each page — open the file in any text editor.
The bio paragraphs are on `index.html` and `about.html`; the publication list is
on `publications.html`.

## Publishing

The site is fully static (no build step, no server). To put it online, upload
the whole folder to any web host — GitHub Pages, Netlify, a university web
directory, or any shared-hosting service all work without modification.
