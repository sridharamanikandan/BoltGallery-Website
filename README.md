# BoltGallery landing page

A responsive, static marketing website for BoltGallery, styled with a premium, Apple-inspired visual direction.

## Files
- `index.html` — landing page, features, app preview, privacy summary and FAQ
- `privacy.html` — full privacy policy draft
- `styles.css` — responsive design and visual system
- `script.js` — mobile navigation and current year
- `assets/boltgallery-icon.svg` — editable vector icon inspired by the supplied app icon

## Publish free
### GitHub Pages
1. Create a GitHub repository (for example, `boltgallery-site`).
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.

### Cloudflare Pages
1. Create a Cloudflare account and open **Workers & Pages → Create → Pages**.
2. Connect the GitHub repository, or use direct upload.
3. For a plain static site, leave the build command empty and set the output directory to `/` or the repository root as requested by the dashboard.
4. Deploy.

## Before publishing
- Replace both `https://apps.microsoft.com/` links in `index.html` with the direct BoltGallery Microsoft Store product URL.
- Replace `hello@example.com` with a real support email.
- Confirm the privacy policy against the release build, including network requests, analytics, crash reporting and any future changes.
- The preview gallery uses decorative CSS artwork, not actual app screenshots. Replace it with screenshots of the released app when available.
- Check the Microsoft Store listing and test all links on desktop and mobile.

## Product facts used
This site is based on the supplied project README for Lumen/BoltGallery: Windows 10/11, month-grouped photo grid, keyboard/touchpad navigation, People face grouping, GPS-based Locations, local indexing/cache, read-only original photos, and OpenStreetMap place-name lookup. The current code stores app data under `%LOCALAPPDATA%\\Lumen`; update the wording if the product's internal name or storage path changes.
