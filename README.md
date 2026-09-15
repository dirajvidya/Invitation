# Wedding Invitation GitHub Pages site

## Before publishing

Open `index.html` and replace every occurrence of:

`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY/`

with the exact public GitHub Pages URL for this repository, including the trailing slash.

Example:

`https://example-user.github.io/wedding-invitation/`

The absolute URL is required in `og:url`, `og:image`, `og:image:secure_url`, `twitter:image`, and the canonical link so WhatsApp can fetch the preview image.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload `index.html`, `og-preview.jpg`, and `.nojekyll` to the repository root.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. After the site is live, share its GitHub Pages URL on WhatsApp.

If WhatsApp previously cached the link, share the URL once with a harmless query suffix such as `?v=2` after republishing.
