# QuickMath GitHub Pages site

This is a static landing page for **QuickMath: Hide Photo & Video**. It uses only HTML, CSS, and the supplied images in `Assets/`.

## Publish with GitHub Pages

1. Push the contents of this `QuickMath` folder to the root of a GitHub repository. The repository root should contain `index.html`, `styles.css`, `CNAME`, and the `Assets/` folder.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing this site and the `/ (root)` folder, then save. The `CNAME` file configures `quickmath.jaidroid.com` for the site.

5. In the DNS settings for `jaidroid.com`, create a `CNAME` record with host/name `quickmath` pointing to `<your-GitHub-username>.github.io` (replace the placeholder with your GitHub username).

6. After DNS has propagated, return to **Settings → Pages** and enable **Enforce HTTPS** when available.

GitHub will show the published URL in the Pages settings once the first deployment finishes. No build step is needed.

## Before publishing

- Add a Google Play listing URL to the site when the app listing is available.
- Add a privacy policy page or link if your app distribution channel requires one. This landing page describes the security details provided for QuickMath and does not make claims about analytics, permissions, or other data handling that were not specified.
