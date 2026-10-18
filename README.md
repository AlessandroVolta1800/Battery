# NMC vs LFP Battery Chemistry Explorer

This is a static, bilingual website (English and Russian). No build tools, server, or dependencies are required.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `battery-research`).
2. Extract this ZIP on your computer.
3. Upload **the contents of this folder** to the repository's top level. The files `index.html`, `ru.html`, and `.nojekyll` must be at the root, not inside another folder.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait for GitHub Pages to publish the site. Open the URL shown on the Pages settings screen.

`index.html` is the English homepage. The language link opens `ru.html`; keep both HTML files together at the repository root.

## Use a custom domain

In **Settings → Pages**, enter your domain under **Custom domain** and save it. Configure the DNS records with the domain registrar according to GitHub's current documentation. For a `www` subdomain, the CNAME target is your GitHub Pages hostname (`YOUR-USERNAME.github.io`), not the repository path. If you change your GitHub username, update that DNS target.

Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
