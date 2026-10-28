Astro Market Calendar — Android PWA package

Files:
- index.html: responsive calendar app
- manifest.json: install metadata
- sw.js: offline cache service worker
- icon-192.png / icon-512.png: app icons

IMPORTANT:
This is a Progressive Web App package. To install as an app on Samsung Galaxy S24 Ultra:
1. Host these files over HTTPS (for example GitHub Pages or another static web host).
2. Open the hosted URL in Chrome or Samsung Internet.
3. Choose Install app, or menu > Add to Home screen.
A local ZIP opened directly from Downloads will not install as a PWA with offline caching.

Calendar includes degree targets and starter Amavasya/Purnima dates that should be verified against Mumbai Panchang. Other event categories are added through Settings > Add dates or CSV/JSON import. Planetary conjunctions/transits are not automatically calculated in this offline version.
