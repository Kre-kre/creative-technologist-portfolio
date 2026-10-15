# Gargi Tripathi — Independent Creative Practice

Portfolio site. Static files only; no build step.

## Structure

```
index.html            the site (Ice Night palette)
support.js            runtime that renders index.html (loads React from unpkg)
assets/
  grain-tile.png      background texture
  moonbrew/           Moonbrew Café gallery images
.nojekyll             tells GitHub Pages to serve files as-is
```

## Publish on GitHub Pages

1. Create a repository (e.g. `portfolio`) and upload **everything in this folder**, keeping the structure above.
2. Repository → Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. After a minute the site is live at `https://<your-username>.github.io/portfolio/`.

## Activate the contact form (one time)

The form posts straight to FormSubmit (free, no account).
1. Open the live site, fill in the form and press **Send it**.
2. FormSubmit shows a page saying the form needs activation, and emails **gargitripathi19@gmail.com** an "Activate Form" link. Check Spam / Promotions if it isn't in your inbox.
3. Click **Activate Form**. From then on every message lands in your inbox, and visitors are sent back to your site with a "Received." confirmation. Hit reply to answer the sender.

## Editing projects

Project titles, links and process notes live in `index.html` inside `projects = [ ... ]`.
Orbit card previews load each project's live site; Moonbrew uses the images in `assets/moonbrew/`.
