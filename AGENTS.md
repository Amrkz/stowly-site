# Stowly site

These are the public pages for Stowly PDF Compressor, a Mac app. The site is plain HTML. GitHub Pages serves this repository as it is. There is no build step.

## Paths that must keep working

App Store Connect already lists these addresses. Do not rename or remove them.

- `index.html` — home
- `support.html` — the Support URL
- `privacy.html` — the Privacy Policy URL
- `privacy-policy.html` — an old link that now sends people to `privacy.html`

Keep `.nojekyll` in the folder so GitHub Pages does not run the files through Jekyll.

## Leave these as they are

- App name: Stowly PDF Compressor
- Purchase name: Stowly Unlimited
- Free limit: five files a day
- Contact email: amroqazzaz@gmail.com
- The meaning of the privacy policy. If a sentence looks wrong, say so in the pull request. Do not quietly rewrite the policy.

## How to change the site

- Edit the HTML files and `styles.css`. Do not add outside fonts, scripts, or tracking.
- Do not commit passwords, tokens, or keys.
- Do not push to `main` and do not deploy. The live site may be served from `main`. Open a pull request instead.
