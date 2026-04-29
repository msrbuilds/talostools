# Contributing to Talos.tools

Thanks for helping make Talos.tools better. The fastest path depends on what you want to do:

| What you want to do | Where to go |
| --- | --- |
| 🧩 Submit a new template | [New template issue](https://github.com/msrbuilds/talostools/issues/new?template=new-template.yml) |
| ✏️ Suggest an edit to an existing template | [Edit template issue](https://github.com/msrbuilds/talostools/issues/new?template=edit-template.yml) |
| 🐛 Report a bug | [Bug report issue](https://github.com/msrbuilds/talostools/issues/new?template=bug-report.yml) |
| 💡 Request a feature | [Feature request issue](https://github.com/msrbuilds/talostools/issues/new?template=feature-request.yml) |
| 🛡️ Report a security issue | Email **mian.shahzad.raza@gmail.com** privately — please do **not** open a public issue |

## Trusted contributor program

Templates are reviewed manually. After **3–5 accepted submissions** through GitHub issues we'll invite you as a **trusted contributor** with direct in-app submission access — no more GitHub round-trip. Trusted contributors get:

- A "Submit a template" button on `talos.tools/templates` that opens an in-app editor
- A verified contributor badge on every approved template
- A public profile page at `talos.tools/user/<handle>` linking back to your work

## Security rules

User-submitted code runs through a static safety scanner. Submissions containing any of the following are **auto-rejected**:

- `fetch(`, `XMLHttpRequest`, `navigator.sendBeacon`, `WebSocket`, `EventSource`
- `eval(`, `new Function(`, `setTimeout("…", 0)` with a string arg
- `document.cookie`, `localStorage`, `sessionStorage`, `indexedDB`
- `<input type="password">` (phishing risk)
- `<script src="https://…">` (external script tag)
- `<iframe>`, `<object>`, `<embed>`
- `@import url(http…)` or `expression(…)` in CSS

Templates are **inline-only**. Images may be loaded from a small allowlist of trusted hosts (Unsplash, Pravatar, Pexels, Cloudinary, jsDelivr, Google Fonts).

## Licensing

By submitting via GitHub or the in-app form, you agree your contribution is licensed under MIT-equivalent terms for use within the Talos.tools template library.
