# pronounce

Landing page and model distribution for **Pronounce** — the on-device pronunciation-practice app built for Pace University's International Academic Support (IAS) office.

Published at **https://pace-ias.github.io/pronounce/** via GitHub Pages (`main` branch, root).

## What's here

- `index.html` / `style.css` — the static download page (no build step, no dependencies).
- The speech model itself is **not** committed to this repository. At 339 MB it exceeds GitHub's file limits and cannot be served by GitHub Pages; it is published as a **GitHub Release asset** instead.

## Model

| | |
|---|---|
| File | `ias-model-0.1.0.onnx` |
| Size | 355,374,846 bytes (~339 MB) |
| SHA-256 | `e88bbad6cd890c193ba42c63f708383b8b646e0e7382db8d4392efbfe8e2edb0` |
| Download | https://github.com/Pace-IAS/pronounce/releases/latest/download/ias-model-0.1.0.onnx |

## Editing the page

It's plain static HTML/CSS. Edit and push to `main`; GitHub Pages redeploys automatically. `.nojekyll` disables Jekyll processing so files are served verbatim.

## Publishing a new model version

Cut a new GitHub Release and attach the `.onnx` asset. The page links to `releases/latest/download/…`, so the download button tracks the most recent (non-prerelease) release without an HTML edit — but update the version, size, and SHA-256 shown on the page and in this README.

---

For Pace University's International Academic Support office. All rights reserved.
