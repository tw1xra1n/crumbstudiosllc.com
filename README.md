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

Section 7 of the privacy policy covers Toast Clicker's Google AdMob rewarded ads. If the ad setup changes (new ad formats, asking for App Tracking Transparency, adding analytics), update that section first.

`app-ads.txt` authorizes Google AdMob (publisher `pub-7175044676473256`) to sell ads in Crumb Studios apps. AdMob finds it through the Marketing URL on the App Store listing, so keep it at the site root.

When you change a policy, update the "Effective date and last updated" line at the top of it.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)**.
The `CNAME` file sets the custom domain to `crumbstudiosllc.com`.
