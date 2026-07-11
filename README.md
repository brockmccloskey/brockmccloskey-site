# Brock McCloskey Portfolio Site

Version 2.1.1

## What's new

- Updated the page title and meta description for search visibility.
- Added a canonical URL for `https://brockmccloskey.com/`.
- Added Open Graph metadata and a social preview image.
- Added a custom Documentation Architecture favicon.
- Added `robots.txt` and `sitemap.xml`.
- Added Schema.org `Person` structured data.

No visible page content was changed in this release.

## Publishing to GitHub Pages

1. Copy these files into the root of your `brockmccloskey-site` repository.
2. Commit the changes.
3. Push to GitHub.
4. GitHub Pages should redeploy automatically.

```bash
git add .
git commit -m "Release site version 2.1.1: documentation architecture favicon"
git push
```

## After publishing

- Confirm `https://brockmccloskey.com/robots.txt` loads.
- Confirm `https://brockmccloskey.com/sitemap.xml` loads.
- Submit the sitemap in Google Search Console.
- Use URL Inspection in Search Console to request indexing for the homepage.

## Google Analytics setup

1. Create a GA4 property in Google Analytics.
2. Copy the Measurement ID, which looks like `G-XXXXXXXXXX`.
3. Open `index.html`.
4. Find the Google Analytics block in the `<head>`.
5. Replace both instances of `G-XXXXXXXXXX` with your Measurement ID.
6. Remove the surrounding HTML comment markers to enable the script.
