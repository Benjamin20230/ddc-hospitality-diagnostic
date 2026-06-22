# DDC Hospitality Diagnostic

## What This Site Is

This is a static MVP prototype for the Digital Drinks Consulting hospitality diagnostic platform.

It is a Spanish-first, mobile-first audit experience for:

- Bars
- Restaurants
- Boutique hotels
- Resorts

The site includes a business profile, diagnostic questionnaire, visual results dashboard, PDF report request flow, and optional professional review request.

## GitHub Pages Deployment

This folder is ready to upload directly to a new GitHub repository.

Required structure:

```text
ddc-hospitality-diagnostic/
├── index.html
├── prototype-assets/
│   └── hospitality-hero.png
├── README.md
├── .nojekyll
└── .github/
    └── workflows/
        └── pages.yml
```

## Deploy With GitHub Actions

1. Create a new GitHub repository.
2. Upload all files and folders from this folder to the repository root.
3. Open the repository on GitHub.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to **GitHub Actions**.
6. Go to the **Actions** tab.
7. Run or wait for the workflow named **Deploy static site to GitHub Pages**.
8. When the workflow completes, GitHub will show the live Pages URL.

## Alternative: Deploy From Branch

This site also works with the simpler branch deployment option:

1. Go to **Settings → Pages**.
2. Set **Source** to **Deploy from a branch**.
3. Select the default branch, usually `main`.
4. Select `/ (root)`.
5. Save.

## How To Update The Site Later

1. Edit `index.html`.
2. If replacing images, keep them inside `prototype-assets/`.
3. Make sure image paths remain relative, for example:

```html
prototype-assets/hospitality-hero.png
```

4. Upload or commit the updated files to GitHub.
5. GitHub Pages will redeploy automatically.

## Notes

This MVP does not include:

- Booking
- Stripe
- GoHighLevel integration
- Backend database
- User accounts
- Real PDF generation

It is intentionally static and lightweight for fast validation.
