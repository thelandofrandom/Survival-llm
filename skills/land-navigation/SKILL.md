# Land Navigation

## Purpose

FM 3-25.26, *Map Reading and Land Navigation* (U.S. Army, July 2001, 246 pages; formerly FM 21-26) — the Army's complete course in finding your way with a map and compass, and without them. This skill is for anyone who needs to navigate on foot or in a vehicle in terrain where GPS is unavailable, unreliable, or denied: a soldier, a hiker, a hunter, a search-and-rescue volunteer, or a civilian in a disaster where the phone is dead. It is the detailed navigation course behind the short navigation sections in the `survival` and `sere` skills.

The core idea: **navigation is a system of independent checks, not a single instrument.** A map, a compass, a pace count, the terrain, and the sky each give you a position; when two or more agree, you know where you are. When they disagree, you stop and resolve the disagreement before moving — the single most common navigation failure is walking farther into a mistake instead of stopping to fix it.

## 1. Maps — Reading the Ground on Paper

**1.1. The map of choice.** The standard military map is **1:50,000 scale** (one unit on the map equals 50,000 units on the ground); many areas are also mapped at **1:25,000**, and small-scale maps at 1:100,000 cover larger areas. At 1:50,000, 1 centimeter on the map is 500 meters on the ground; 1 inch is about 0.8 miles. Larger scale (1:25,000) means more detail and a smaller area; smaller scale (1:100,000) means less detail and a larger area.

**1.2. Marginal information.** The border of every military map carries the data that makes it usable: the sheet name and number, the series and edition, the **declination diagram** (the angular relationship between true north, grid north, and magnetic north), the scale bar, the contour interval, the grid zone designation, and notes on the datum. Read the margin before you read the map — a map used with the wrong declination or the wrong datum puts you in the wrong place with great confidence.

**1.3. Colors and symbols.** Military maps use standard colors: black for man-made features (buildings, roads, boundaries), brown for relief (contour lines), blue for water, green for vegetation, red for major roads and populated areas, and purple for updates. Symbols are standardized (Appendix A covers field sketching); learn the common ones — roads by class, railroads, bridges, power lines, water features, vegetation types, and built-up areas — before you need them under pressure.

**1.4. Contour lines and relief.** Contour lines join points of equal elevation. The **contour interval** — the vertical distance between adjacent lines — is printed in the margin (commonly 10 or 20 meters at 1:50,000). Closely spaced lines mean steep ground; widely spaced lines mean gentle ground; a V shape pointing uphill marks a valley or drainage; a V pointing downhill marks a ridge or spur. Index contours (every fifth line, drawn thicker) carry the elevation numbers. Relief is read from the pattern, not from any single line. → `references/maps-grids.md`

## 2. Grids — The Military Grid Reference System

**2.1. UTM and MGRS.** Military maps use the Universal Transverse Mercator (UTM) grid, expressed as a Military Grid Reference System (MGRS) coordinate. The system divides the world into 6°-wide zones; between 84°N and 80°S, each zone is covered by 100,000-meter squares identified by two letters. Inside a square, a coordinate is read **right, then up** — easting first, then northing — the same order as reading a graph.

**2.2. Reading a grid coordinate.** A coordinate has three parts: the grid zone designation (e.g., 16S), the 100,000-meter square letters (e.g., GJ), and the numbers (easting + northing). The number of digits sets the precision:

| Digits (each half) | Example | Precision |
|---|---|---|
| 4 (8-digit total) | 1234 5678 | 1,000 meters |
| 5 (10-digit total) | 12345 56789 | 100 meters |
| 6 (12-digit total) | 123456 567890 | 10 meters |

The standard for reporting a position in the field is the **8-digit grid (10-meter precision)**; a 6-digit grid (100-meter precision) is used when the exact point does not matter. Always state the precision you are using — a 6-digit grid and an 8-digit grid for the same place look alike and are not interchangeable.

**2.3. Plotting and reading with a protractor.** Use the military protractor (GTA 5-2-12) or the corner of the map: align the protractor with the grid lines, read the easting from the bottom scale and the northing from the side scale. Practice until the mechanical steps are automatic — under stress, the protractor is the part people fumble.

**2.4. The grid azimuth and the G-M angle.** Grid north and magnetic north are not the same. The **declination diagram** in the map margin shows the angular difference — the **G-M angle** — between grid north and magnetic north, and the margin notes give the conversion: when converting a grid azimuth to a magnetic azimuth, **add the G-M angle if it is easterly, subtract if it is westerly** (or use the diagram's printed rule, which is authoritative for that sheet). Declination changes over time — check the diagram's date. A 1° error is about 17 meters per kilometer walked; a 5° error puts you nearly 100 meters off per kilometer. → `references/maps-grids.md`

## 3. Direction — The Compass and the Sky

**3.1. The lensatic compass.** The standard military compass: a floating dial with a sighting wire, a lens for reading the dial, and a bezel ring that can be set to a desired azimuth. Hold it level, let the dial settle, and read the azimuth under the index line. Set the bezel to your azimuth and the luminous marks let you walk the bearing at night. Keep the compass away from metal objects, vehicles, power lines, and weapons — all of them deflect the needle.

**3.2. Azimuths and back azimuths.** An azimuth is a direction measured clockwise from north, 0°–360°. A **back azimuth** is the opposite direction — add 180° if the azimuth is under 180°, subtract 180° if it is over 180°. The back azimuth is how you return along a route and how you check your work: if the back azimuth from your destination does not point at your start, something is wrong.

**3.3. Converting azimuths.** Three norths exist on every map: true north (the North Pole), grid north (the map's grid lines), and magnetic north (where the compass points). The declination diagram shows all three and the angles between them. Convert with the diagram's rule, not from memory — the sign of the correction varies by location and by sheet.

**3.4. Field-expedient direction finding.** Shadow-stick method: mark the tip of a stick's shadow, wait 15–20 minutes, mark the new tip — the line between marks runs east–west (first mark is west). Watch method (northern hemisphere): point the hour hand at the sun; halve the angle between the hour hand and 12 o'clock — that line points south. At night, Polaris sits almost directly above true north; in the southern hemisphere, use the Southern Cross. Moss does not reliably grow on the north side of trees — do not trust it. → `references/compass-direction-distance.md`

## 4. Distance — Pace Count and Measurement

**4.1. Measuring distance on the map.** Use the graphic scale bar in the margin, a ruler, or the protractor's scale. On a 1:50,000 map, measure in centimeters and multiply by 500 for meters. For curved routes (roads, streams), use a strip of paper or a piece of string laid along the route, then straightened against the scale bar. Straight-line distance is always shorter than the distance you will walk — add for slope, vegetation, and detours.

**4.2. The pace count.** A **pace is one natural step, about 30 inches long**. To use it, you must know how many paces it takes you to walk 100 meters: walk a measured 100-meter course on flat terrain, count your paces, and repeat to get a reliable average. The manual's method for a longer calibration: walk a **600-meter course**, count the paces, divide by six to get your 100-meter pace count. Record it — write it on the map or in a notebook, and mark every 100 meters with a knot in a string or a tick in the notebook so you do not have to hold the whole count in your head.

**4.3. What changes your pace count.** Slope (uphill shortens the pace, downhill lengthens it at first, then shortens it as you brake), brush and rough ground, fatigue, load, and darkness all change it. The manual's rule of thumb: if it normally takes you **120 paces to walk 100 meters** on flat ground, allow more on difficult ground — and recheck your count whenever the terrain changes. A pace count is a personal number, not a standard one — calibrate your own.

**4.4. Estimating distance by eye.** Use the apparent size of known objects (a person is about 1.7 meters tall; a house about 8 meters wide), the clarity of detail (features become distinguishable at known ranges), and time × speed (a person walks about 4 km/h on flat ground, less on slopes or in brush). Combine methods — a single estimate is a guess; two that agree are a measurement. → `references/compass-direction-distance.md`

## 5. Navigation Methods — Dead Reckoning, Terrain Association, Resection

**5.1. Dead reckoning.** Navigate by compass bearing and pace count: shoot an azimuth to your destination, walk it, and count paces to know when you should arrive. Dead reckoning works in any visibility and any terrain, and it is the only method that works in featureless ground (desert, flat forest, fog). Its weakness is cumulative error — small mistakes in bearing or pace add up, so check your position at every opportunity.

**5.2. Terrain association.** Navigate by matching the ground you see to the map: identify the terrain features around you (hills, valleys, streams, roads, buildings) and your position relative to them. Terrain association is faster and more accurate than dead reckoning in distinctive terrain, and useless in featureless terrain. Use **handrails** (linear features you can follow — a river, a ridge, a road), **attack points** (an obvious feature near your destination from which you navigate the final leg), and **catching features** (a feature beyond your destination that tells you you have gone too far).

**5.3. Resection.** Find your own position by shooting azimuths to two or more known features, converting them to back azimuths, and plotting them on the map — where the lines cross is where you are. **Intersection** is the same technique used to locate a distant unknown point: shoot azimuths to it from two known positions. **Modified resection** uses one known feature plus a known direction or distance (for example, a single azimuth plus a road you know you are on). **Polar coordinates** locate a point by azimuth and distance from a known position. Resection needs two widely separated features for accuracy — features close together give a poor fix.

**5.4. Combining methods.** The manual's doctrine is to use dead reckoning and terrain association together: dead reckoning keeps you on a bearing, terrain association confirms where you are. When they disagree, stop — the disagreement is information, and walking on is how people get lost. → `references/navigation-methods-terrain.md`

## 6. Elevation, Terrain, and Movement

**6.1. Elevation and relief (Ch. 10).** Read the contour pattern to understand the ground before you walk it: ridges, valleys, saddles, depressions, draws, and spurs each have a signature contour shape. A saddle is the low point between two hills and the high point between two valleys — the natural crossing point. A draw is a shallow valley that may hold water and cover. Know the ground from the map before your feet find it the hard way.

**6.2. Terrain association (Ch. 11).** The field skill of matching map to ground: orient the map (align it with the terrain, using the compass or by matching features), identify five major terrain features, and confirm your position before moving. The manual's training method is progressive — start with obvious terrain, move to subtle terrain, then navigate at night and in bad weather.

**6.3. Mounted land navigation (Ch. 12).** Navigating from a vehicle: the driver drives, the navigator navigates — never combine the jobs. Use the vehicle's odometer for distance, the compass for direction, and the map for position; confirm at every stop. Vehicle navigation is faster but coarser than foot navigation, and the error per kilometer is larger.

**6.4. Navigation in different types of terrain (Ch. 13).** Desert (few features — dead reckoning and resection dominate; mirages and heat distort distance), jungle (limited visibility — short legs, frequent checks, pace count is unreliable in dense vegetation), mountains (elevation is your friend — contours are distinctive, but weather closes in fast), arctic (whiteout destroys terrain association — dead reckoning and GPS only), and urban terrain (streets are handrails, but street names and maps may be wrong or outdated). → `references/navigation-methods-terrain.md`

## 7. Overlays, Aerial Photographs, and GPS

**7.1. Overlays (Ch. 7).** A transparent sheet laid over the map carrying operational graphics — boundaries, routes, objectives, and control measures — registered to the map by at least two grid ticks. Overlays keep the base map clean and let graphics be shared, updated, and removed without damaging the map.

**7.2. Aerial photographs (Ch. 8).** Photographs show the ground as it is, not as the mapmaker drew it: they reveal vegetation, water, and structures the map may miss, and they go out of date more slowly than maps in some ways and faster in others (a photo is a snapshot; a map is a survey). The manual covers photo types, scale determination, indexing, orientation, the point designation grid, and stereovision (viewing overlapping photos in 3D to judge relief). A photo and a map used together are better than either alone.

**7.3. GPS (Appendices J and K).** The Global Positioning System gives position, speed, and direction anywhere on Earth — when it works. The manual's treatment is clear-eyed: GPS is a tool, not a crutch. Batteries die, signals are blocked by terrain and canopy, and GPS can be jammed or denied. The doctrine is to use GPS to confirm map-and-compass navigation, never to replace it, and to keep the map-and-compass skills current so a dead GPS is an inconvenience, not an emergency. The Precision Lightweight GPS Receiver (PLGR) appendix covers the military receiver; the principles apply to any receiver, including a phone.

**7.4. Unit sustainment and training (Ch. 14).** Land navigation is a perishable skill. The manual's training strategy (Ch. 1) is crawl-walk-run: classroom (map reading), practical exercises (pace count, resection, intersection), day courses, then night courses and adverse conditions. The appendices add field sketching, map folding, units of measure and conversion factors, joint operations graphics, orienteering, the M2 compass, and foreign maps. → `references/overlays-photos-gps.md`

## Output Contract

When asked a navigation question, answer in this order: (1) what to determine first (your position — never navigate from an unknown start), (2) the procedure with the numbers (scale, grid precision, G-M angle, pace count, azimuths), (3) the check that confirms you are right (a second independent method — resection, terrain association, or a catching feature), (4) what to do when the methods disagree (stop, re-plot, re-shoot — never walk on). Cite the chapter (e.g., "FM 3-25.26, Ch. 6 — Direction"). If the question is a survival situation (lost, no map, no compass), answer with the field-expedient methods here and point to the `survival` and `sere` skills for the rest of the survival problem.

## Operating Rules

1. **Know your position before you move.** Navigation from an unknown start is guessing.
2. **Two independent checks, always.** Dead reckoning plus terrain association; resection plus a catching feature. One method is a guess.
3. **When the methods disagree, stop.** Walk on and the error compounds; stop and the error is found.
4. **The declination diagram is authoritative for that sheet.** Convert with its rule, not from memory.
5. **Calibrate your own pace count.** It is personal, and it changes with slope, load, and fatigue.
6. **GPS confirms; it does not replace.** A dead GPS is an inconvenience only if the map-and-compass skills are current.
7. **Read the margin before the map.** Declination, datum, contour interval, and scale decide whether the map is telling the truth.

## References

- `references/maps-grids.md` — map scales and marginal information, colors and symbols, contour lines and relief, UTM/MGRS, grid coordinates and precision, G-M angle
- `references/compass-direction-distance.md` — lensatic compass, azimuths and back azimuths, converting between norths, field-expedient direction finding, measuring map distance, pace count calibration
- `references/navigation-methods-terrain.md` — dead reckoning, terrain association, resection/intersection/modified resection/polar coordinates, handrails, attack points, catching features, elevation, mounted navigation, navigation by terrain type
- `references/overlays-photos-gps.md` — map overlays, aerial photographs, GPS and PLGR, unit sustainment and training
- `references/full-text.md` — the complete verbatim extracted text of FM 3-25.26 (62,661 words by wc), public-domain source; SKILL.md stays distilled, this file is the verbatim reference

Source: FM 3-25.26, *Map Reading and Land Navigation*, Headquarters, Department of the Army, July 2001, 246 pages. PDF: https://files.trex-arms.com/pdf/army/legacy/fm/fm_3-25-26.pdf — Vault: https://www.trex-arms.com/field-manual-vault/fm-3-25-26-2001-07
