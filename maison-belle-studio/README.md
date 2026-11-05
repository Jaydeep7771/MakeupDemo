# Maison Belle — Makeup & Hair Studio Template

A single-page website template for luxury makeup and hair studios. It uses HTML, Tailwind (CDN) and vanilla JS, with no build step.

## Customise for a client
- Search and replace `Maison Belle`, `Ananya`, `+91 98765 43210`, `919876543210`, `hello@maisonbelle.studio` and the address.
- Gallery: edit the `looks` array near the bottom of `index.html`.
- Other images: replace the Unsplash URLs in `background-image:url(...)`.
- Booking: paste the client's Calendly embed into the dashed "Booking Calendar" box.

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/maison-belle-studio.git
git push -u origin main
```

## Deploy (pick one)
**Vercel:** go to vercel.com/new, import the repo and click Deploy. No settings are needed.
**Netlify:** go to app.netlify.com, choose Add new site, then Import from Git and pick the repo. Leave the build command empty and set the publish directory to `/`.
**GitHub Pages:** go to the repo's Settings, then Pages. Choose Deploy from branch, select `main` and `/ (root)`. The site goes live at `https://<user>.github.io/maison-belle-studio/`.

Tip: create one repo per client, for example `client-name-studio`, so each one gets its own link.
