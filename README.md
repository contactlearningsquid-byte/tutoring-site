# Learning Squid website

A static one-page website designed for GitHub Pages or any basic HTML host.

## Files

- `index.html` — the entire website, styles, and JavaScript
- `assets/logo-mark.svg` — simple Learning Squid logo mark
- `assets/favicon.svg` — browser-tab icon
- `assets/project-based-tutoring.jpg` — optimized version of the real tutoring photo

## Before publishing

Open `index.html`, scroll to the `CONFIG` block near the bottom, and replace:

```js
email: "YOUR_EMAIL_HERE"
```

with the email address you want consultation requests sent to.

The contact form does not need a server. It opens the visitor's email app with their inquiry pre-filled. If you later want a true web form, replace it with Formspree, Basin, Netlify Forms, or another form backend.

## Deploy on GitHub Pages

1. Copy `index.html` and the `assets` folder into the root of your repository.
2. Commit and push.
3. In GitHub: **Settings → Pages**.
4. Choose **Deploy from a branch** and select your main branch/root folder.
5. Point your Squarespace domain's DNS records to GitHub Pages using GitHub's current custom-domain instructions.

## Main brand colors

- Deep navy: `#0B2D4A`
- Teal: `#0EA5A0`
- Turquoise: `#10B8C5`
- Seafoam: `#7ED6B7`
- Gold: `#F7A21B`
