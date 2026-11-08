# Equipment, Antennas, Siting, and Grounding (MCRP 3-40.3B, Chapters 2–4)

## Chapter outline

Ch. 2 Single-Channel Radio: equipment, HF, VHF, UHF, data communications. Ch. 3 Equipment Siting and Grounding: HF, VHF/UHF, grounding techniques. Ch. 4 Antennas: HF antennas, VHF antennas, antenna length.

## SINCGARS at a glance

| Item | Value |
|---|---|
| Band | VHF-FM, 30 to 87.975 MHz |
| Manpack | AN/PRC-119 |
| Vehicular | AN/VRC-87/88/89/90/91/92 (7 configurations total) |
| Modes | Single-channel (plain/secure) and frequency hopping |
| Range, manpack | ~8 km (5 mi) over average terrain, single-channel |
| Range, vehicular | ~20 km (12.4 mi) under normal field conditions |
| Key requirement | All stations share hopset, time, and TRANSEC key or they cannot communicate |

Frequency hopping: the radio hops across frequencies many times per second per a shared hopset. Hard to jam or intercept. Range in hopping mode is somewhat reduced. Time synchronization is mandatory.

## Antenna length formulas

- Half-wave dipole total length (feet) ≈ **468 ÷ frequency (MHz)**
- Quarter-wave leg (feet) ≈ **234 ÷ frequency (MHz)**
- Inverted-L: quarter-wave vertical with horizontal top section (Appendix N tables)
- Cut long, trim to resonance. SWR below 2:1 is acceptable; high SWR reflects power back into the radio and can destroy the final amplifier.
- Never transmit with no antenna or a broken antenna attached.

## Antenna types

| Antenna | Best for | Notes |
|---|---|---|
| Half-wave dipole (doublet) | HF, general purpose | Two equal wires, center-fed, as high as possible |
| Inverted-L | HF, limited space | Quarter-wave vertical + horizontal top; good ground wave |
| Long wire | HF, known distant station | Several wavelengths long, directional |
| Whip (quarter-wave vertical) | VHF, manpack | Omnidirectional, simple; standard 3-ft tape whip with matching network |
| OE-254 / mast antenna | VHF, command post | Broadband, on a mast; greatly extends range |
| Yagi (directional) | VHF, fixed link | Concentrates signal; must be aimed; hears only in its direction |

## Siting rules

**HF:** high ground, clear view toward the distant station; avoid valleys, dense forest, power lines, metal structures, other antennas. Low antennas + vertical polarization favor ground wave; horizontal dipole at ~half-wavelength height favors sky wave.

**VHF/UHF:** height dominates. Highest ground available, clear line to the other station. Avoid depressions, far side of ridges, dense vegetation. Keep antennas several meters from metal, vehicles, and other antennas.

**Grounding:**
- Drive a ground rod at least 1 m into moist earth; in dry/rocky soil, dig to moisture or use multiple rods.
- Ground leads short and thick. Bond all equipment to a common point. Never daisy-chain.
- Vehicles: bond radio to chassis; body is the ground plane.
- Dry conditions: wet the ground around the rod with salt water.
- Never ground to a pipe that may carry gas.

## Field-expedient antennas

Any wire works: WD-1 field wire, stripped cable, even fence wire in an emergency. Insulators improvised from plastic, wood, or glass. Hoist a wire into a tree in jungle — above the canopy beats a whip at ground level. A wire antenna cut to resonance beats a mismatched whip at the same power, every time.

## Data communications

- SINCGARS with data adapter, HF modems, dedicated data radios.
- Rates are low (hundreds to a few thousand bps on HF; higher on VHF/UHF) and fall with distance and interference.
- Keep data messages short; use the lowest rate the path supports; expect retries.
