# Christopher M. Kaiser — Academic Website

This is a simple static website: no database, account, or Google Drive access is required.

## Preview locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Edit

- Page text lives in the four `.html` files.
- Colors, typography, and layout live in `styles.css`.
- Replace `files/Christopher_Kaiser_CV.pdf` to update the CV.
- The homepage uses `assets/christopher-kaiser-headshot.jpg`.

## Publish

This site is prepared for the public repository `chris-m-kaiser.github.io`.
Publish the `main` branch from the repository root using GitHub Pages.
The old CV, unpublished draft, and reference screenshot are excluded from Git.

After publishing, updates follow this workflow:

1. Edit and review the local website.
2. Commit the reviewed changes.
3. Push to GitHub; Pages publishes the updated files automatically.
