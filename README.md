# Brock McCloskey Portfolio Site

Version 3.0.4 — Documentation Engineering Edition

## What's new

- Replaced the reconstructed homepage SVG with the approved workflow artwork.
- Removed the duplicate name and title from the hero; the navigation brand remains.
- Preserved the `100+ reusable snippets` metric.
- Added optimized WebP and PNG versions of the hero artwork.

- Added the release-candidate homepage diagram with cleaner product-diagram alignment, AI assistance throughout, Publish directly above Customers, and a larger visual.
- Updated the metric to `100+ reusable snippets`.

- Refined the homepage workflow diagram so AI assists throughout the process and Publish feeds directly into Customers.

- Reframed the home page around documentation engineering and business outcomes.
- Added a custom documentation architecture illustration.
- Added dedicated case-study pages for Trintech, NextAxiom, and Equinix.
- Added a Documentation Health Check service page.
- Added a Resources library with four evergreen documentation engineering articles.
- Added stronger calls to action, metrics, and consulting-oriented language.
- Expanded SEO metadata and the sitemap for all public pages.
- Preserved the custom-domain `CNAME` file and added `.nojekyll`.

## Files that must remain in the repository root

- `CNAME`
- `.nojekyll`
- `index.html`
- `robots.txt`
- `sitemap.xml`

The `CNAME` file contains `brockmccloskey.com`. Do not remove it when replacing site files.

## Publishing to GitHub Pages

1. Back up or commit your current site.
2. Extract this ZIP directly into the root of the `brockmccloskey-site` repository.
3. Confirm that `CNAME` is still present before committing.
4. Commit and push.

```bash
git add .
git commit -m "Release site version 3.0: documentation engineering edition"
git push
```

## Smoke test after publishing

- Open `https://brockmccloskey.com/`
- Confirm the favicon appears.
- Open each navigation link.
- Confirm the three case studies load.
- Confirm the Documentation Health Check and Resources pages load.
- Confirm `https://brockmccloskey.com/robots.txt` loads.
- Confirm `https://brockmccloskey.com/sitemap.xml` loads.
- Confirm GitHub Pages still lists `brockmccloskey.com` as the custom domain.

## Google Analytics setup

The GA4 placeholder remains in each page.

1. Create or open the GA4 property.
2. Copy the Measurement ID, such as `G-XXXXXXXXXX`.
3. Replace both instances of `G-XXXXXXXXXX` in each HTML page.
4. Remove the surrounding HTML comment markers to enable the script.

A later release can centralize analytics injection through a build step, but this version remains framework-free and directly deployable.
