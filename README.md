# acvickers.com — static site

Hand-coded HTML/CSS. No build step, no dependencies. Open `index.html` in a browser to preview.

## Files

    index.html          Home
    color-quartet.html  The Color Quartet (campaign landing page)
    works.html          Catalogue
    commercial.html     Commercial work
    about.html          Biography
    lessons.html        Teaching
    contact.html        Contact
    styles.css          All styling (colors + fonts at the top)
    img/                Photos
    scores/             Perusal score PDFs

## Editing

Text lives directly in the HTML. Open a file in any text editor, find the sentence,
change it, save. Anything in [square brackets] is a placeholder waiting on you.

Colors and typefaces are the first block of `styles.css` (`:root`). Change one hex
value there and it updates everywhere.

## To finish

- Replace `VIDEO_ID` in color-quartet.html and commercial.html with real YouTube IDs
- Add the remaining perusal PDFs to `scores/`
- Fill the [bracketed] placeholders on works.html and lessons.html
- Point the LinkedIn and Instagram links in the footer of each page at your profiles

## Publishing

Drag this whole folder onto https://app.netlify.com/drop — it goes live immediately
on a temporary URL. To use acvickers.com, add it as a custom domain in Netlify and
update your DNS. Cloudflare Pages and GitHub Pages work the same way.

Your Wix site stays live until you change DNS, so there's no rush and no downtime.
