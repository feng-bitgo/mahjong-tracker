# HK Mahjong Tracker

A static single-page Hong Kong Mahjong score tracker. The app lives entirely in
`index.html`, so it can be served directly by GitHub Pages without a build step.

## Publish on GitHub Pages

1. Create a GitHub repository and push this folder to it.
2. In the repository, open **Settings > Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push to `main`. The included workflow publishes the static site.

After the workflow finishes, the page will be available at:

```text
https://<github-username>.github.io/<repository-name>/
```

## Local Preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
