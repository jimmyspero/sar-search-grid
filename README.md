# LKP Search Grid

A browser tool for building search segments around a last known point (LKP) and exporting them to ATAK.

- Drop the LKP on satellite imagery, USGS topo, or street maps (tap, type lat/long or MGRS, or use device GPS)
- 25 / 50 / 75 / 95% distance rings by subject category, split into sectors (A, B1–B8, C1–C8, D1–D8)
- Square grid (G-A01…) beyond the 95% ring, clipped to the ring edge
- Tap segments to assign them to drone, ground, or K9 teams; see acres and POA per team
- Export an ATAK data package (.zip) or a plain KML

Ring distances are approximate starting values. Confirm them against your Lost Person Behavior reference.

Hosted with GitHub Pages: it's a single `index.html` with no build step.
