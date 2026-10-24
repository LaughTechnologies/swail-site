# swail-site

Swail's public site, served by GitHub Pages at https://laughtechnologies.github.io/swail-site/.

- `release.json` — read by the app on launch (spec 024 in the Swail repository): per platform and release line, the newest build (`latestBuild`), the oldest version still allowed to run (`minimumVersion`) and where to get the app (`url`). CI in the Swail repository raises `latestBuild` after each build TestFlight accepts. **To force everyone off an old version, raise `minimumVersion` by hand.**
- `index.html` — the home page. The privacy policy will live here too.
