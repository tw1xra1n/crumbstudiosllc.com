# crumbstudiosllc.com

Static website for **Crumb Studios LLC**, hosted free on GitHub Pages at https://crumbstudiosllc.com.

Plain HTML/CSS/JS — no build step, no external fonts, scripts or trackers.

| Path | Page |
| --- | --- |
| `/` | Home |
| `/privacy/` | Toast Clicker Privacy Policy |
| `/support/` | Toast Clicker Support |
| `/terms/` | Terms of Use |

## Before going live

Replace the highlighted placeholders (search the files for `placeholder`):

- `[CONTACT EMAIL]` in `privacy/index.html`, `support/index.html`, `terms/index.html`
- `[STATE WHERE CRUMB STUDIOS LLC IS REGISTERED]` in `terms/index.html`

To make the email a clickable link, replace each
`<span class="placeholder">[CONTACT EMAIL]</span>` with
`<a href="mailto:you@example.com">you@example.com</a>`.

Also confirm that section 4 of the privacy policy ("Information the App handles directly") matches what Toast Clicker actually does.

When you change a policy, update the "Effective date and last updated" line at the top of it.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)**.
The `CNAME` file sets the custom domain to `crumbstudiosllc.com`.
