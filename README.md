# Flag Master — Terms, Privacy & Support

Public legal and support pages for the mobile app **Flag Master / 국기의 주인**, in 14 languages.

Live: <https://taiji1368-ui.github.io/flag-master/>

| Page | URL | Used for |
| --- | --- | --- |
| Landing | `/` | Entry point |
| Terms of Use | `/terms.html` | EULA link on the purchase screen; store "License Agreement" |
| Privacy Policy | `/privacy.html` | App Store Connect · Google Play "Privacy Policy URL" |
| Support & FAQ | `/support.html` | App Store Connect "Support URL" |

Deep-link a language with a hash: `/privacy.html#ko`, `/support.html#ja`. `#all` shows every language.
The store toggle at the top switches the wording between App Store and Google Play.

## These files are generated — do not edit them by hand

The document text has a single source of truth: `world_flags/WebContent/legal.js` in the app
repository. A hand-edited copy here would silently drift from what the app itself shows, and the
copy people read would be the stale one.

To change a document, edit it in the app repository and regenerate:

```
node scripts/build_legal_site.mjs /Users/limhansoo/Documents/flag-master
```

Only the support/FAQ content is authored outside the app, in
`scripts/legal_site/support/<lang>.json` (also in the app repository).

## App

* iOS bundle `com.limhansoo.worldflags` · Android package `com.worldflags.app`
* Developer 임한수 (Hansoo Lim) · <ddontti_studio@outlook.kr>

No trackers, no analytics, no third-party fonts or scripts are loaded by these pages.
