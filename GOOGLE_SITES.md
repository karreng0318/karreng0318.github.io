# Embed this page in Google Sites

Google Sites cannot run a pasted HTML file. It can iframe a public HTTPS URL. `embed.html` is the page built for that: one file, tabbed layout, links open in a new tab.

## Host the widget (no GitHub Pages)

1. Open [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the folder `embed-host/` onto the page. It already contains `index.html` plus the assets the widget needs.
3. Copy the `https://….netlify.app` URL Netlify gives you.

After you edit `embed.html`, copy it to `embed-host/index.html` and drop the folder again (or replace the file in the existing Netlify site).

## Put it on your Google Site

1. In Google Sites, click **Insert → Embed**
2. Choose **By URL** and paste the Netlify link  
   **or** choose **Embed code** and paste:

```html
<iframe src="YOUR_NETLIFY_URL_HERE" style="border:0; width:100%; min-height:900px; height:70vh;" loading="lazy" title="Karthik Rengarajan profile"></iframe>
```

3. Stretch the embed box until the tabs and cards are fully visible (about 900–1100 px tall).
4. Publish the Google Site.

External links (GitHub, patents, email) open outside the iframe.
