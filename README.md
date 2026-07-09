# Brock McCloskey Portfolio Site

Version 1.2

## What's new

- Stronger homepage positioning around documentation modernization.
- Added case studies for Trintech, NextAxiom, and Equinix.
- Added Technologies & Methods section.
- Added Google Analytics 4 placeholder.
- Added release notes section to demonstrate iterative documentation habits.

## Publishing to GitHub Pages

1. Copy these files into the root of your `brockmccloskey-site` repository.
2. Commit the changes.
3. Push to GitHub.
4. GitHub Pages should redeploy automatically.

```bash
git add .
git commit -m "Release site version 1.2"
git push
```

## Google Analytics setup

1. Create a GA4 property in Google Analytics.
2. Copy the Measurement ID, which looks like `G-XXXXXXXXXX`.
3. Open `index.html`.
4. Find the Google Analytics block in the `<head>`.
5. Replace both instances of `G-XXXXXXXXXX` with your Measurement ID.
6. Remove the surrounding HTML comment markers to enable the script.

## Notes before publishing

- Confirm the email address is the one you want public.
- Confirm the LinkedIn and GitHub links are correct.
- Add a resume PDF later if desired.
