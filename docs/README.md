# Hosting the privacy policy (GitHub Pages)

These files are **static HTML** so GitHub Pages does not need Jekyll configuration.

If the GitHub repository is **private**, check your GitHub plan: free Pages hosting often requires a **public** repo, or use a small separate public repository that only contains these `docs/` files.

## 1. Replace placeholders

Edit `index.html` (German) and `privacy-en.html` (English): every yellow-highlighted `[…]` block must be filled with your real legal name, address, date, and contact email **before** you use the URL in Play Console.

## 2. Enable GitHub Pages

1. Push this repository (including the `docs/` folder) to GitHub.
2. On GitHub: **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. **Branch:** your default branch (e.g. `main`). **Folder:** `/docs`.
5. Save. After a minute or two, GitHub shows the site URL (typically `https://<username>.github.io/<repo>/`).

## 3. URL for Google Play Console

Use the **German** page as the primary policy link unless you prefer English:

- German: `https://<username>.github.io/<repo>/` (serves `docs/index.html`)
- English: `https://<username>.github.io/<repo>/privacy-en.html`

If you later use a **custom domain**, update the Play Console link to match.

## 4. Keeping it accurate

When you change data practices (new analytics, new providers, new permissions), update both HTML files and bump the “Stand” / “Last updated” date.
