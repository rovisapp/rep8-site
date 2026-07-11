# rep8-site

Static site backing the public pages Apple requires for the Rep8 iOS app
submission: privacy policy, support page, landing page.

Hosted by GitHub Pages from the `main` branch's root. Markdown is rendered by
Jekyll automatically - no build step needed.

## Live URLs

- Landing: <https://rovisapp.github.io/rep8-site/>
- Privacy: <https://rovisapp.github.io/rep8-site/privacy.html>
- Support: <https://rovisapp.github.io/rep8-site/support.html>

## Editing

Just edit the relevant `.md` file and push to `main`. GitHub Pages rebuilds
within ~30 seconds.

## Files

- `index.md` - landing page (linked as Marketing URL on the App Store).
- `privacy.md` - Privacy Policy URL on the App Store.
- `support.md` - Support URL on the App Store.
- `_config.yml` - Jekyll config (theme, exclusions).
