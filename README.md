# pocketcaddi.com

Static website for PocketCaddi. No build step: every file in this folder is published as-is.

| File | What it is |
|---|---|
| `index.html` | The home page |
| `privacy.html` | Privacy policy (linked from the signup form) |
| `thanks.html` | Shown after signup if JavaScript is off |
| `404.html` | Page-not-found |
| `netlify.toml` | Netlify settings: security headers, pocketcaddi.com → www redirect |

## Hosting

Netlify, deployed automatically from the `main` branch on GitHub.
Early-access signups are collected by Netlify Forms (form name `early-access`):
Netlify dashboard → the site → Forms.

## Domain

Registered at GoDaddy; DNS stays at GoDaddy and points to Netlify.
