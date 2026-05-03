# GitHub Pages Guide

## Goal

Publish the privacy policy from this project to a public URL for Google Play.

## Files Ready

- `docs/index.html` - public privacy policy page
- `docs/app-ads.txt.template` - template for AdMob app-ads.txt
- `privacy-policy.html` - local copy outside of GitHub Pages setup

## Recommended GitHub Setup

1. Create a new GitHub repository named:
   - `CryptoTPSLCalculator`
2. Upload the whole project or at minimum:
   - `docs/index.html`
   - `docs/.nojekyll`
   - `docs/app-ads.txt.template`
3. Open repository `Settings`
4. Go to `Pages`
5. Under `Build and deployment`:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/docs`
6. Save

## Final Privacy Policy URL

After GitHub Pages is enabled, the privacy policy should be available at:

`https://YOUR_GITHUB_USERNAME.github.io/CryptoTPSLCalculator/`

## app-ads.txt Later

When your AdMob publisher ID is ready:

1. Rename `docs/app-ads.txt.template` to `docs/app-ads.txt`
2. Replace the placeholder publisher ID
3. Push the change to GitHub

The file will then be available at:

`https://YOUR_GITHUB_USERNAME.github.io/CryptoTPSLCalculator/app-ads.txt`

## What to Send Me Later

When you get to GitHub, send me:

- your GitHub username
- a screenshot of the repo page after creation
- a screenshot of `Settings > Pages`

Then I will help you verify the exact final URL and the next Play Console step.
