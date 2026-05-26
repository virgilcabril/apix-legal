# apix-legal

Static legal pages for **APIX Load**, served via GitHub Pages at
[https://legal.apix.services](https://legal.apix.services).

## Pages

| Path | URL | Purpose |
| --- | --- | --- |
| `index.html` | `/` | Landing page listing all legal docs |
| `privacy/index.html` | `/privacy/` | Privacy Policy (Google Play + Meta App Review) |
| `data-deletion/index.html` | `/data-deletion/` | Account deletion instructions (Google Play required field) |
| `terms/index.html` | `/terms/` | Terms of Service |

## Editing

Edit the HTML files directly. Each page is self-contained (inline CSS, no
build step, no dependencies). Push to `main` to deploy &mdash; GitHub Pages
rebuilds automatically.

## Custom domain

The `CNAME` file at the repo root pins the GitHub Pages site to
`legal.apix.services`. DNS for `apix.services` is at GoDaddy &mdash; a CNAME
record from `legal` points to `virgilcabril.github.io`.

## License

Content is owned by APIX Eloading Center. Not for reuse without permission.
