# ghureashi-assets

Lazy-loaded images for the GhureAshi app (spec §6): hero **covers** and
gallery photos. Thumbnails ship inside the APK; these stream + cache on
device via GitHub Pages.

Served at `https://<user>.github.io/ghureashi-assets/images/<file>`.
Enable **Settings → Pages** on this repo, then confirm the URL matches
`src/config/cdn.ts` `CDN_BASE` in the app.

All photos are Wikimedia Commons (CC0/CC-BY/CC-BY-SA) or owner-owned;
per-photo credit + license live in the app DB (`photos` table) and are
rendered on Spot Detail + Settings → Credits.
