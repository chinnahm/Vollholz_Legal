# Hosting the privacy policy (GitHub Pages)

These files are **static HTML** so GitHub Pages does not need Jekyll configuration.

### Why README looks “nice” but the HTML files look like code

On **github.com**, GitHub **renders** Markdown files such as this `README.md` as formatted text when you browse the repo. For **`.html` files**, GitHub **does not** run them as a webpage in the file viewer; it only shows the **source** (tags and text). That is normal and expected.

**The policy as a real page** is only served at your **GitHub Pages** URL (after Pages is enabled), e.g. `https://<username>.github.io/Vollholz_Legal/` — open that in a browser, not the “blob” link under *Code → docs → index.html*.

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
