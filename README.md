# INLAND LUXURY — GitHub / Vercel ready

This is a lightweight static website with **3 core files** and one public video asset. The 49 original HTML pages are consolidated into `app.js`; navigation uses hash routes so each page works on GitHub Pages and Vercel without a build step.

## Files
- `index.html` — site shell and shared navigation
- `styles.css` — site styling
- `app.js` — all 49 page contents, routing, navigation and interactive UI
- `public/Real-Estate-video-SnapYT.App.mp4` — local hero video

## Deploy
1. Extract this ZIP.
2. Upload the contents of the `inland-luxury-github-ready` folder to the **root** of your GitHub repository (not the enclosing folder).
3. In Vercel, import that repository.
4. Framework Preset: **Other**. Build Command: leave blank. Output Directory: `.` (root).
5. Deploy.

No `npm install`, build command, or `package.json` is required because this is a static HTML/CSS/JS site.

## Notes
- Page navigation uses `#/page-slug`, so deep links work without server rewrite rules.
- The hero video is served from the included `public/` directory.
- Interior photography is loaded from Unsplash and therefore requires an internet connection.
- Estimate figures are indicative only; final project costs depend on site measurements, materials and scope.
