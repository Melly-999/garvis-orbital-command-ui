# GARVIS Orbital Command UI

A cinematic, single-file sci-fi command interface inspired by orbital HUDs and holographic control systems.

## Features

- Procedural Three.js deep-space scene, nebulae, orbit rings, particles, and animated core
- Interactive system gauges, live telemetry, module tiles, radial menu, and detailed views
- Mouse, touch, and keyboard interactions with a responsive tablet layout
- Simulated command terminal, scan/analyze/engage flows, sound effects, and shutdown sequence
- No backend, accounts, API keys, or external image assets

## Run locally

Open `index.html` in a modern browser, or serve the directory:

```bash
python -m http.server 4173
```

Then visit [http://127.0.0.1:4173](http://127.0.0.1:4173).

Internet access is required for the Three.js, Tailwind, and font CDNs.

## Safety and data

All telemetry and AI output are simulated demo data generated locally in the browser.

## License

[MIT](LICENSE)
