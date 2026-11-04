# LKP Search Grid

A browser tool for building search segments around a last known point (LKP) and exporting them to ATAK.

- Drop the LKP on satellite imagery, USGS topo, or street maps (tap, type lat/long or MGRS, or use device GPS)
- 100 m inner circle (A) and 100–300 m band split into sectors (B1–B8) as the 25% zone
- Square grid (G-A01…) from the 300 m ring out past the subject category's 95% distance, with POA per square from the ring model
- 25 / 50 / 75 / 95% rings for the subject category drawn as outlines over the squares (can be hidden)
- Tap segments to assign them to drone, ground, or K9 teams; see acres and POA per team
- Export an ATAK data package (.zip) or a plain KML

Ring distances are approximate starting values. Confirm them against your Lost Person Behavior reference.

Hosted with GitHub Pages: it's a single `index.html` with no build step.
