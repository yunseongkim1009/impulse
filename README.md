# Impulse

Landing page for Impulse: 3D-printed crushable lattice that forms a drone's propeller guards and underside, to soften crashes in the lowest few meters.

Single-file site (`index.html`). Three.js loads from unpkg via an import map, so serve it over HTTP rather than opening the file directly:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Placeholders still to fill: team names/photos, contact email, footage band, and the request form (not connected to an inbox yet).
