# Portfolio website

Single-page site: index.html (HTML, CSS and JS in one file; GSAP loads from cdnjs).

## Edit
Open index.html and find the "EDIT HERE" block in the script:
- CONFIG: name, email, WhatsApp, social links, about text.
- PROJECTS: one object per website (name, image, url, description, details, category, tags, featured).
  To add a project, copy an object and change its fields.

## Preview images
Put files in images/ (16:10, .webp) and set "image" to e.g. "images/my-site.webp".
No image or a failed load shows a generated placeholder.

## Deploy
Upload the whole folder to Netlify, Vercel, GitHub Pages or any static host.

## Placeholders still to replace
Name, email, LK FITNESS url and preview image, the two sample projects.
Projects live in this file, so they are the same on every device once deployed.
