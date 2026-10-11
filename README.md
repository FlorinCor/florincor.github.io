# Florin Cordunianu — developer website

Live website: https://florincor.github.io/

A buildless, responsive portfolio for Heart Match, ColorPour, Perfect Fit, ColourFun,
Flow, Trick or Treat Adventure, The GIF Break, SlingShot, Slingshot Multiplayer, and Pizzeria.

## Editing and publishing

- Edit game descriptions and links in `index.html`.
- Adjust colours and layouts in `styles.css`.
- `favicon.svg` is the site's monogram; inline SVG drawings are decorative game illustrations.
- Keep `.nojekyll` so GitHub Pages serves the files directly.
- Commit changes to `main`. GitHub Pages publishes from the repository root.
- Preview locally with `python3 -m http.server 8000 --bind 127.0.0.1`.

Existing game privacy policies remain at their original URLs. Store links can be added
to the corresponding cards when each public listing URL is available.

## Shared app-ads.txt

Set **https://florincor.github.io/** as the developer website in each app's store listing.
AdMob discovers the shared file at **https://florincor.github.io/app-ads.txt**.

The existing entry is preserved:

```text
google.com, pub-8261276359594399, DIRECT, f08c47fec0942fa0
```

The publisher ID identifies the AdMob account, not an individual app or ad unit.
Games using this account can share this entry. Add the authorised seller entries
required by other ad networks or publisher accounts if those are introduced.
A game without advertising does not need an ad seller entry.

After changing the developer website or the file, allow at least 24 hours for AdMob
to discover it, then check each app's app-ads.txt status in AdMob.
Publishing the website does not itself change any app-store listing or verify AdMob ownership.

Official setup guidance: https://support.google.com/admob/answer/9363762?hl=en
