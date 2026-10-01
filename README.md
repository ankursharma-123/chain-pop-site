# Publish the Chain Pop website with GitHub Pages

This folder is a standalone static website. Publish only the files in this folder in a separate public GitHub repository; do not make the game/server repository public just to host these pages.

## Before publishing

1. Check every privacy statement against the build you are actually submitting. In particular, update this policy before configuring the optional Go/MongoDB API.
2. Check the site from a signed-out browser and confirm all three pages and links work.

## GitHub Pages steps

1. Create a new public repository on GitHub, for example `chain-pop-site`.
2. Upload the contents of this folder (`index.html`, `privacy.html`, `support.html`) to the repository root.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. Wait for GitHub Pages to publish. The URL will look like `https://YOUR-USERNAME.github.io/chain-pop-site/`.
5. In **Settings → Pages**, enable **Enforce HTTPS** when that option appears.
6. Test the home page and the direct policy URL `https://YOUR-USERNAME.github.io/chain-pop-site/privacy.html` in a private/incognito browser window.

In Meta, use the home page for the website field and the direct `privacy.html` URL for the privacy-policy field. If Meta asks for an owned/verified custom domain rather than a public website URL, follow that specific domain verification flow; a `github.io` URL may not meet it.
