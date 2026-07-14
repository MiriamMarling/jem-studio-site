# JEM Studio site

The public marketing, privacy, and support site for **JEM Studio**, a native iOS
short-form video editor.

- Static HTML and CSS only. No JavaScript, no analytics, no trackers, no cookies,
  no external fonts, and no third-party CDNs.
- Served by GitHub Pages from the repository root of the `main` branch.
- Custom domain: `jem.bonquery.com`.

## Structure

```
index.html          Overview
privacy/index.html  Privacy policy
support/index.html  Support and troubleshooting
styles.css          Shared styles (light and dark)
404.html            Not-found page
icon.png            App icon (1024px, as shipped in the app)
icon-180.png        Same icon resized for favicon and header use
.nojekyll           Serve files as-is, without Jekyll processing
```

## Local preview

```
python3 -m http.server 8000
# open http://localhost:8000/
```
