# DirtView — Customer-Facing Site

DirtView is a small static customer-facing website containing marketing pages and downloadable ambassador materials.

## Contents
- **Home & Pages:** [index.html](index.html), [become_ambassador.html](become_ambassador.html)
- **Assets:** `assets/` (downloads and other static media)

## Features
- Static HTML pages ready to be hosted on any static hosting provider (Netlify, GitHub Pages, S3, Vercel).
- Downloadable ambassador assets in `assets/downloads/ambassador/`.

## Local Preview
The site is static — to preview locally you can open `index.html` in a browser, or run a simple HTTP server from the project root:

```bash
# Python 3
python3 -m http.server 8000

# then open http://localhost:8000
```

## Deploy
- Push to a Git repo and enable GitHub Pages, or
- Drag & drop the site folder into Netlify or Vercel for instant deploy, or
- Upload files to an S3 bucket configured for static website hosting.

## Contributing
- Make content or asset changes directly on the HTML files and `assets/` folder.
- Open a PR with the proposed change and a short description of the update.

## License & Contact
- Check project owner or org for license details.
- For questions, contact the site maintainer.
