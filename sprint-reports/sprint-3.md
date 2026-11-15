# Sprint 3 – Building: The Map and the Routes

*Moreux Camp Map – NASA Space Apps Challenge 2026*

**Goal:** Turn the data into one interactive map that a crew can use to plan a safe Marswalk.

## What we did

- Built the Moreux Camp Map as a web page in English and Turkish, with switchable backdrops and layers.
- Planned 4 rover routes from camp (South Wall, West Wall, East Wall and Central Peak) that go around the dunes, avoid slopes above 15° and never cross slopes above 25°.
- Added a route panel with distance, climb, steep sections, time, sols and radiation dose, plus a speed slider (4–20 km/h).
- Added a route profile and a close-up image with notes for each of the 13 stops.
- Added safety notes and distance rings (25, 50 and 100 km).

## Problems

The map was blank when the HTML file was opened outside its folder, a small code error stopped the page from loading, and the radiation value had no source.

## Solutions

We kept all the files together (and made a single-file version), fixed the code error and used the 0.64 mSv/day value measured by Curiosity's RAD instrument (Hassler et al. 2014).

## Result

A working map. The South Wall route is the safest first Marswalk: 77.9 km, only 0.7 km on foot and the lowest dose.
