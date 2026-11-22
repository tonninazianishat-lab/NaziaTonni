# Nazia Nishat Tonni — Portfolio

Static site (HTML5, CSS3, vanilla JS). No build step, backend or paid services. Fonts are self-hosted. Live at `https://tonninazianishat-lab.github.io/NaziaTonni/` (GitHub Pages, branch `main`, root).

## Structure
```
index.html         single-page site: Home, About, Experience, What I bring, Work, Education, Skills, Beyond the CV, Contact
dissertation.html  case study for the MSc dissertation (add method, findings, recommendations)
404.html  favicon.svg  robots.txt  sitemap.xml  .nojekyll
css/styles.css     colours and spacing in :root at the top
js/main.js
assets/Nazia-Nishat-Tonni-CV.pdf   replace with your CV (same filename)
assets/img/profile.jpg             replace with your portrait (4:5, about 960x1200)
assets/img/gallery-1..4.jpg        replace with your photos (about 900x700)
assets/img/og-image.png            link-preview image
assets/fonts/*.woff2
```

## Adding your photos
Upload a new file with the **same filename** over the placeholder (GitHub: open the file's folder, *Add file → Upload files*). Keep each image under about 300 KB (resize first) for a fast site. Update the alt text and captions in `index.html`.

## Editing text
Open `index.html` (pencil icon on GitHub). Yellow `[PLACEHOLDER: ...]` text marks details still missing. Search for `PLACEHOLDER` and `editor-note` until none remain, and delete the editor-note boxes.

## Contact details
Email, phone, location and LinkedIn are set in `index.html` (Contact section and the flip card). Search for `tonninazianishat@gmail.com` and `7404` to change them.

If you rename the repository, also update `/NaziaTonni/` in `404.html` and the `tonninazianishat-lab.github.io/NaziaTonni/` URLs in `index.html`, `dissertation.html`, `sitemap.xml` and `robots.txt`.
