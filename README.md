# Cell Discovery Network — GitHub Pages site

Static landing page for **https://celldiscoverynetwork.github.io/**

## Contents

```
index.html      single-page site
styles.css      CDN brand styles
assets/         logos, images, and brand fonts (Gramatika)
assets/fonts/   Gramatika-Regular, Medium, Bold (.ttf)
.nojekyll       serve files as-is on GitHub Pages
```

## Local preview

```bash
cd ~/Desktop/CDN/celldiscoverynetwork.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages

1. Create repo `CellDiscoveryNetwork/celldiscoverynetwork.github.io` on GitHub (if it doesn't exist).
2. Push this folder:

```bash
cd ~/Desktop/CDN/celldiscoverynetwork.github.io
git init
git add .
git commit -m "Add CDN landing page with mission, calendar, workshops, and contact"
git branch -M main
git remote add origin git@github.com:CellDiscoveryNetwork/celldiscoverynetwork.github.io.git
git push -u origin main
```

3. In the repo: **Settings → Pages → Deploy from branch → `main` / root**.
4. Site goes live at **https://celldiscoverynetwork.github.io/** within a few minutes.

## Calendar

Office Hours embed uses the public Google Calendar:
`43a03c6feef66305f86297992f7d8873efe609f7ca886b6691a50a4d829212f5@group.calendar.google.com`

Ensure the calendar is set to **public** in Google Calendar settings, or the embed will show blank.
