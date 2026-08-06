# committobe.com

Single-page static site. Introduces the commitment to stay human in an AI-driven world and links to [daretobehuman.global](https://www.daretobehuman.global).

One file, `index.html`. No build step, no external assets: system fonts, inline SVG, inline CSS/JS.

Push to `main` deploys `index.html` to business-webhosting.eu (user `sarahrapp`) via GitHub Actions. Deploy key exists only as the repo secret `DEPLOY_SSH_KEY`.

Serve locally:

```sh
python3 -m http.server 8000
```
