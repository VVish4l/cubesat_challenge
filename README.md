# SEDS CubeSat Mission Challenge

A no-build, browser-based CubeSat design and survival game inspired by the supplied dashboard concept. It is a static site: open `index.html` locally or publish the repository with GitHub Pages.

## Features
- Component catalogue with click-to-add and drag-and-drop interaction
- Live budget, mass, power draw/generation, and data-capacity meters
- Installed hardware list and design specs
- 7-day mission simulation with power, payload, storage, and downlink trade-offs
- Random anomaly generator and recovery-plan prompts
- Mission timeline, objective meters, forecast chart, event log, and downloadable text report
- Responsive dark space-themed dashboard; no external dependencies or API keys

## Run locally
Double-click `index.html`, or serve the folder with any static server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Publish on GitHub Pages
1. Create a public GitHub repository named `cubesat-mission-challenge`.
2. Upload `index.html` and `README.md` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait for the Pages deployment link to appear.

## Note on the model
The simulator is an educational game model, not a flight-qualified engineering tool. Costs, masses, power, and anomaly effects are simplified for a short workshop and should be play-tested and tuned before a live event.
