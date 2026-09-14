# Karthik Rengarajan — personal site

Static academic / industry site: profile, career path, research, patents, repositories, writing, and contact.

The public page is meant to live on **Google Sites**. This folder is the source for that embed, plus a full standalone layout you can preview locally.

## Local preview

```bash
python3 -m http.server 4177
```

Then visit http://localhost:4177 (full site) or http://localhost:4177/embed.html (Google Sites widget).

## Google Sites

Google Sites cannot run this HTML as a pasted file. Host the widget, then iframe it:

1. Drag the folder `embed-host/` onto [Netlify Drop](https://app.netlify.com/drop).
2. Copy the `https://….netlify.app` URL.
3. In Google Sites: **Insert → Embed → By URL**, paste that link, stretch the box, and publish.

Details: [GOOGLE_SITES.md](GOOGLE_SITES.md).

## Edit

- Copy and facts live in `index.html` and `embed.html`.
- After editing `embed.html`, copy it to `embed-host/index.html` before dropping on Netlify.
- Look in `css/styles.css` for colors and layout.
- Cover image: `assets/cover.jpg`. CV: `assets/Karthik_Rengarajan_CV.pdf`.
