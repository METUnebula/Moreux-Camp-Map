# Moreux Camp Map – MarsWalk planning display

**Live map:** https://stupendous-pithivier-f91637.netlify.app

A NASA Space Apps Challenge 2026 project. An interactive map that a Mars crew could use inside their habitat to plan Marswalks around Moreux crater in Protonilus Mensae, Mars, next to NASA's proposed Protonilus Mensae human exploration zone.

## What it shows
- **Three data types, layered:** optical (MRO CTX), thermal (Mars Odyssey THEMIS day and night infrared) and topographic (MGS MOLA and Mars Express HRSC elevation), with adjustable overlay opacity.
- **Science targets:** glacier-like forms (water ice), supraglacial and proglacial valleys, gullies, hydrous minerals and aqueous minerals (clay and silica).
- **Safety:** mapped dune fields (rover no-go), slope classes, dusty ground from the night thermal layer, line-of-sight warnings, distance rings from camp and a rough radiation dose per route.
- **Four rover routes** with elevation and thermal profiles, walking segments, and CTX close-ups of each stop.
- English and Turkish interface.

## How to run
Open `index.html` in a web browser. Keep `data.js` and all `.jpg` files in the same folder.

## Data sources
All layers were read from NASA/JPL Mars Trek data services (https://trek.nasa.gov/mars/): MRO CTX global mosaic (Caltech Murray Lab), Mars Odyssey THEMIS IR mosaics, MGS MOLA–Mars Express HRSC blended DEM, Glacier-like forms (Souness et al. 2012), Supraglacial and proglacial valleys (Fassett et al. 2010), Gullies (Harrison et al. 2015), Hydrous minerals (Carter et al. 2013), Aqueous minerals (Ehlmann and Edwards 2014), Mars Global Digital Dune Database (Hayward et al. 2007), and NASA's 2015 Exploration Zones (proposal 1053). Radiation dose uses the 0.64 mSv/day surface average measured by Curiosity's RAD instrument (Hassler et al. 2014).

## Limits
Slopes come from a 200 m elevation model, so real slopes can be steeper. Thermal brightness is a relative index, not a temperature. Routes are least-cost planning paths, not rover specifications.
