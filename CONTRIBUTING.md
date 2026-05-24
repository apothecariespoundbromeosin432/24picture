# Contributing to 24Picture Documentation

Thanks for stopping by. This repository is the **public documentation hub** for
[24picture.com](https://24picture.com) — a free, browser-based suite of 28 image tools
that runs entirely on your device.

The actual application source code is **not** in this repository. What lives here:

- [`README.md`](README.md) — overview of every tool, how the project works, and deep links to each tool page on 24picture.com
- [`LICENSE`](LICENSE) — Creative Commons Attribution 4.0 (CC BY 4.0) for the documentation text
- [`SECURITY.md`](SECURITY.md) — how to report security issues
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) — community standards
- [`CHANGELOG`](https://24picture.com/changelog.html) — released version history (kept on the live site)

---

## How You Can Contribute

### 1. 🐛 Report Bugs in the Web App

If a tool on [24picture.com](https://24picture.com) misbehaves (a converter outputs the wrong format,
a button is unresponsive, the language switcher fails, etc.), please **open an issue** in this repository.

Useful info to include:

- Which tool / URL (e.g. `https://24picture.com/tools/png-to-jpg.html`)
- Browser + OS (e.g. Chrome 138 on Windows 11, Safari 17 on iPhone 14)
- A small sample image that reproduces the issue (if relevant)
- What you expected vs what actually happened

### 2. 📝 Improve the Documentation

If you spot a typo, broken link, missing tool description, or outdated information in
[`README.md`](README.md) or any other doc file in this repository, **send a pull request**:

1. Fork the repo
2. Edit the markdown
3. Open a PR with a short description (e.g. "Fix typo in WebP description")

We aim to review and merge documentation PRs within a few days.

### 3. 🌍 Translation Suggestions

The site itself supports **English / 中文 / 日本語 / Español / Português**. If a translation in the
live web app sounds awkward in your native language, please open an issue with:

- The page URL
- The original (English) string
- The current (your language) string
- Your suggested replacement

We'll evaluate it and roll the fix out across the relevant `i18n.js` block.

### 4. 💡 Suggest a New Tool

We're always weighing what to build next. If there's a browser-doable image task that doesn't fit any
of the [28 existing tools](https://24picture.com), open an issue titled `[Tool Request] <name>` and
describe:

- The use case (who needs this, when)
- The input/output formats
- Whether it's pure-Canvas, needs a WASM library, or is browser-impossible
- A real-life example or link to a similar paid SaaS

We can't promise to build everything, but we read every request.

---

## What We Don't Accept Here

- **Source code pull requests** — the application code is not in this repository
- **Asset/binary uploads** — please don't attach executables, large videos, or non-text blobs to issues
- **Off-topic discussions** — keep threads focused on the website and its tools

For anything else (partnerships, press, listings), email **support@24picture.com**.

---

## Code of Conduct

By participating in this project you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
Please be kind, especially to non-native English speakers — this is a multilingual community.

---

Thank you for helping make browser-based image tooling more accessible. ✨
