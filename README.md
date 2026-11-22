# Hanh Nguyễn — Visual Archive

An editorial, animated, responsive documentary photography archive built from the user's **A Land of Many Lives** PDF.

## Publish for free using GitHub Pages

1. Create a public GitHub repository named `YOURUSERNAME.github.io`.
2. Upload the **contents** of this folder (not the enclosing folder) to the repository's root.
3. In repository **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)` and save.
4. Visit `https://YOURUSERNAME.github.io` after deployment.

Alternatively run locally: `python3 -m http.server 8000` inside this folder and visit `http://localhost:8000`.

## Edit the archive

- `archive.json`: edit photo titles, locations and captions. Several captions are intentionally empty rather than invented.
- `assets/`: extracted images from the portfolio PDF; replace with high-resolution original photographs using the same file names.
- `index.html`: edit artist bio and projects.
- **Important**: replace `hello@example.com` with your actual contact email before publishing.
- `Hanh_Nguyen_CV.pdf`: replace when your CV changes.

This is a static website. No subscription, custom domain, database, analytics, or tracking is required. Google Fonts loads from Google; for fully offline fonts, replace with local/system fonts.
