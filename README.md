# solarrio-site

Hosted design bundle for **solarrio.com** (the "Light My Fuse" custom site),
loaded into Squarespace via jsDelivr CDN.

- `solarrio.bundle.js` — self-contained: React + all components + CSS + optimized
  logo/cover art. Referenced from Squarespace's Footer code injection.

Served at: `https://cdn.jsdelivr.net/gh/laurendarrah/solarrio-site@main/solarrio.bundle.js`

Rebuild source lives in `~/Solarrio Website/build` (`node build.mjs`). To update the
live site: rebuild, copy the new `solarrio.bundle.js` here, commit & push, then purge
the jsDelivr cache.
