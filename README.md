# Icebook on Salt Creek

A scrolling story page for the 6 November 2026 Icebook drift on Salt Creek, Lincoln, Nebraska: the block's GPS track on satellite imagery, with the photographs it took placed along the track by capture time.

Static site, no build step. `index.html` loads `data/steps.json` (the ordered photo steps and captions), `data/track.geojson` (the GPS track), and `photos/` (web-size images). Map: MapLibre GL JS; imagery: Esri World Imagery.

Source of truth for the data and the captions is the Icebook project folder; this repository holds the published copy. To change a caption, edit `data/steps.json` and redeploy.
