SPINWHEEL — GITHUB PAGES SETUP

The complete website is index.html. No installation, dependencies, account
inside the app, database, or build step is needed. You can also open index.html
in a browser on your computer before uploading it.

1. Extract spinwheel.zip.
2. Sign in at https://github.com (create a free account if necessary).
3. Open https://github.com/new.
4. Name your repository spinwheel, select Public, enable Add README,
   and click Create repository.
5. In the repository, choose Add file > Upload files.
6. Upload index.html from the extracted ZIP directly into the repository root.
   Upload the file itself, not the ZIP or its containing folder.
7. Click Commit changes; commit to main if prompted.
8. Open the repository's Settings > Pages.
9. Under Build and deployment, set Source to Deploy from a branch.
10. Select branch main and folder / (root), then Save.
11. Wait for deployment. Refresh Settings > Pages to find Visit site.
    Your address will normally be https://YOUR-USERNAME.github.io/spinwheel/.

If you get a 404, allow a few minutes, confirm index.html is at the repository
root, and check the Actions tab for the Pages deployment status.

To update the site, upload a replacement index.html to the same repository
and commit it. GitHub Pages republishes it automatically.

HOW THE WHEEL WORKS
Auto, Zubar, Palec and Soplik each have a 25% chance on every spin.
Outcomes are independent; the same option can win several times in a row.
The pointer and displayed result match. The button is disabled during a spin.
The page respects the device's reduced-motion preference.
All styles and scripts are inside index.html. There are no external requests,
tracking scripts, fonts, or libraries.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
