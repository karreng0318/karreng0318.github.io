# Karthik Rengarajan — personal site

Static academic / industry site: profile, career path, research, patents, repositories, writing, and contact.

Live: **https://karreng0318.github.io/**

Push to `main` and GitHub Pages rebuilds that URL. `embed.html` is the compact version for Google Sites:

https://karreng0318.github.io/embed.html

## Local preview

```bash
python3 -m http.server 4177
```

Then visit http://localhost:4177 (full site) or http://localhost:4177/embed.html (Google Sites widget).

## Google Sites

Insert → Embed → By URL, then paste the embed URL. Details: [GOOGLE_SITES.md](GOOGLE_SITES.md).

## Edit

- Copy and facts live in `index.html` and `embed.html`.
- After editing `embed.html`, copy it to `embed-host/index.html` if you also keep a Netlify drop copy.
- Look in `css/styles.css` for colors and layout.
- Cover image: `assets/cover.jpg`. Resume: `assets/Karthik_Rengarajan_Resume.pdf`.
