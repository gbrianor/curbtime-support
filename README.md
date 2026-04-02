# CurbTime — Support

This repository hosts the **public support page** for [CurbTime](https://github.com/gbrianor/curbtime) on the App Store.

## App Store Support URL

After you enable **GitHub Pages** (Settings → Pages → Deploy from branch `main`, folder `/ (root)`), your support link will be:

**`https://gbrianor.github.io/curbtime-support/`**

Paste that URL into App Store Connect as the **Support URL**.

If your GitHub username or repo name differs, replace them in the URL above.

## Before you submit

1. **Edit `index.html`** — Replace `YOUR_EMAIL@example.com` (both the visible text and the `mailto:` link) with your real support email.
2. **Privacy policy** — If Apple asks for a Privacy Policy URL, add a `privacy.html` (or host it elsewhere) and link it from `index.html` in the Privacy section.
3. **Push this folder** to the `curbtime-support` repository on GitHub, then turn on Pages.

## Repo structure

| File        | Purpose |
|------------|---------|
| `index.html` | Support page shown at your GitHub Pages URL |
| `README.md`  | Notes for you (this file); optional for visitors |

## Local preview

Open `index.html` in a browser, or run a quick server:

```bash
cd curbtime-support && python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
