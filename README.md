# Muhammad Abdullah: DevSecOps Portfolio

Static site (HTML, CSS, JavaScript). No build step, no server.

## Files
- `index.html`: page structure
- `style.css`: design
- `script.js`: all your content (projects, competitions, certifications) at the top of the file

## Publish on GitHub Pages
1. Create a new public repository on github.com (e.g. `portfolio`, or `<username>.github.io`).
2. Upload `index.html`, `style.css`, `script.js` to the repository root.
3. Go to Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. Wait 1-2 minutes. Your site is at `https://<username>.github.io/<repo>/`.

## Editing content
Everything is at the top of `script.js`. Only entries with a real URL display as links.
To use an official digital badge: save the image in an `images/` folder, then add `badge: "images/name.png"` to that certificate's entry in `CERTS`.
