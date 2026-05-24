# Security Policy

## Project Scope

This repository contains **documentation only** for [24picture.com](https://24picture.com).
The actual application source code is private and not included here.

The 24Picture web app runs **entirely in your browser** — your images never leave your device,
so most server-side attack surfaces simply do not exist for image processing.

## Reporting a Vulnerability

If you discover a security issue affecting [24picture.com](https://24picture.com), the PWA, or anything
referenced from this documentation, please report it **privately**:

📧 **support@24picture.com**

Please include:

- A clear description of the issue
- Steps to reproduce (URL, browser, OS, expected vs actual behavior)
- Any proof-of-concept HTML / JavaScript / network request you used
- Whether you would like to be credited publicly when the fix ships

We aim to:

- **Acknowledge** your report within **48 hours**
- **Triage** and assign severity within **5 business days**
- **Patch** critical issues and roll out a Service Worker version bump within **7–14 days**
- **Disclose** the issue in the [public changelog](https://24picture.com/changelog.html) after the fix is live

## Out of Scope

Because everything is browser-side, the following are explicitly **not** vulnerabilities for this project:

- "Files are processed in the browser" — yes, this is the intended privacy model
- "I can open browser DevTools and see the JavaScript" — yes, all client code is publicly viewable
- "I can use the tools without an account" — yes, this is intentional
- Reports from automated scanners with no working PoC

## Supported Versions

Only the **currently deployed** version of [24picture.com](https://24picture.com) is supported.
The Service Worker version published in [`/changelog.html`](https://24picture.com/changelog.html) is the
authoritative live version.

## Hall of Fame

Confirmed reporters who allow public credit will be listed in the
[changelog page](https://24picture.com/changelog.html) for the version that ships the fix.

Thank you for helping keep 24Picture safe and private.
