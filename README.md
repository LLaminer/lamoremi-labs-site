# Lamoremi Labs website

A responsive, single-file static website for Lamoremi Labs. It has no build step, framework, external fonts, or paid services. It is ready to publish with GitHub Pages.

## Publish with GitHub Pages

1. Create a public GitHub repository named lamoremi-labs-site.
2. Choose Add file → Upload files, upload index.html, and commit it to the main branch.
3. Open Settings → Pages. Under Build and deployment, select Deploy from a branch, choose main and / (root), then save.
4. Wait for the Pages build. GitHub will show the temporary github.io address on that settings screen.
5. In the Pages screen, enter lamoremilabs.com under Custom domain and save. Add the exact DNS records GitHub displays to the domain DNS page at IONOS. Keep existing mail-related records such as MX, SPF, DKIM, and DMARC.
6. After DNS verifies and HTTPS is issued, turn on Enforce HTTPS.

Check GitHub's current documentation for its exact DNS values before changing records. DNS updates can take time to reach all networks.

## Editing the game lineup

Open index.html in a text editor. Search for Center It, Potion Sort, or Drop Zone to change the names and descriptions. When you have a public play link or TikTok Minis link, replace each card's current in-page link with that URL and change the link text.

## Before launch

- Confirm game descriptions and status labels.
- Add a contact or social link if you want visitors to reach you.
- Add a privacy page if your apps or game links collect personal information or require one for platform review.
- Check spelling, screenshots, and links on phone and desktop.
