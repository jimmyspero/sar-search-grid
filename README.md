# LKP Search Grid

A browser tool for building search segments around a last known point (LKP) and exporting them to ATAK.

- Drop the LKP on satellite imagery, USGS topo, or street maps (tap, type lat/long or MGRS, or use device GPS)
- Three rings around the LKP (100 / 300 / 500 m by default, editable): inner circle A, then sectors B1–B8 and C1–C8
- POA per segment from the subject category's 25 / 50 / 75 / 95% distances
- 25 / 50 / 75 / 95% rings for the subject category drawn as outlines (can be hidden)
- Tap segments to assign them to drone, ground, or K9 teams; see acres and POA per team
- Export an ATAK data package (.zip) or a plain KML

Ring distances are approximate starting values. Confirm them against your Lost Person Behavior reference.

Hosted with GitHub Pages: it's a single `index.html` with no build step.
