# Modern Personal Portfolio

A responsive, dark-themed static portfolio ready for GitHub Pages.

## Customize before publishing
- Edit `index.html` to change the name, bio, projects, and skills.
- Replace the placeholder GitHub and LinkedIn links in the Contact section.
- To add photos: create a `photos` folder, place images there, and replace each `.photo` placeholder with an `<img src="photos/photo1.jpg" alt="Description">` (and so on). Add CSS: `.photo img {width:100%;height:100%;object-fit:cover;border-radius:12px}`.
- Avoid publishing private contact details or sensitive information.

## Publish
1. Create a **public** GitHub repository (e.g. `portfolio`).
2. Upload `index.html`, `style.css`, and `script.js` to its root.
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
5. Your site will appear at `https://YOUR-USERNAME.github.io/portfolio/`.

No database or server-side code is needed. Google Fonts requires an internet connection.
