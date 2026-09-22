# crumbstudiosllc.com

Static website for **Crumb Studios LLC**, hosted free on GitHub Pages at https://crumbstudiosllc.com.

Plain HTML/CSS/JS — no build step, no external fonts, scripts or trackers.

| Path | Page |
| --- | --- |
| `/` | Home |
| `/privacy/` | Toast Clicker Privacy Policy |
| `/support/` | Toast Clicker Support |
| `/terms/` | Terms of Use |

## Contact details

- Contact email: crumbstudios@proton.me (Privacy, Support and Terms pages)
- Governing law: New Jersey (Terms)

The privacy policy has two marked placeholder blocks (search for `placeholder`) for advertising and analytics services. Fill them in if either is ever added to Toast Clicker.

When you change a policy, update the "Effective date and last updated" line at the top of it.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)**.
The `CNAME` file sets the custom domain to `crumbstudiosllc.com`.
