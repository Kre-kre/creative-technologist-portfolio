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

The form sends through FormSubmit (free, no account).
1. Open the live site and send yourself a test message.
2. FormSubmit emails **gargitripathi19@gmail.com** an activation link. Click it.
3. Every message after that arrives in your inbox. Reply directly to the sender.

## Editing projects

Project titles, links and process notes live in `index.html` inside `projects = [ ... ]`.
Orbit card previews load each project's live site; Moonbrew uses the images in `assets/moonbrew/`.
