# NFI Market Intelligence Dashboard - GitHub Pages package

This package is prepared for a simple GitHub Pages deployment.

## Files included
- `index.html`
- `.nojekyll`
- `README.md`

## What is included in this version
- Single-file dashboard deployment
- Updated NFI login intro experience
- Intro sequence customized to highlight:
  - globe / North America transition
  - Inland Empire, CA flyover
  - Lehigh Valley, PA flyover
- Login credentials carried over from the Maersk version
- Post-login choice between national view and submarket view

## Deploy to GitHub Pages
1. Create a new GitHub repository.
2. Upload all files in this package to the root of the repository.
3. In GitHub, go to **Settings > Pages**.
4. Under **Build and deployment**, select:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Save the settings.
6. Wait a minute or two for GitHub Pages to publish the site.

## Notes
- This dashboard is packaged as a single-file HTML deployment.
- The `.nojekyll` file helps GitHub Pages serve the site cleanly.
- The login is front-end only unless you later connect it to a real back-end authentication system.
