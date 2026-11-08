# Ballistics and Range Estimation — FM 23-10

## Core Definitions

- **Muzzle velocity:** speed of the bullet as it leaves the barrel (fps). Varies with ammunition type/lot, temperature, humidity.
- **Minute of angle (MOA):** angular unit; 1 MOA ≈ 1.047 in at 100 yd (≈ 29 mm at 100 m). The M3A adjusts in 1-MOA clicks.
- **Zero:** sight setting putting the bullet on the point of aim at a given range.
- **Come-up:** elevation change between ranges. **Holdoff:** aiming off-target to compensate for wind or movement.
- **Slope dope:** elevation change applied to the telescope for angle firing.

## The Mil-Relation Formula (Primary Range Method)

Range (m) = target height (m) × 1,000 ÷ mils observed.

Worked examples (standard man ≈ 1.8 m tall):

| Target | Size | Mils | Range |
|---|---|---|---|
| Standing man | 1.8 m | 2.0 | 900 m |
| Standing man | 1.8 m | 3.0 | 600 m |
| Standing man | 1.8 m | 6.0 | 300 m |
| Vehicle (2.5 m high) | 2.5 m | 2.5 | 1,000 m |
| Doorway (2 m) | 2.0 m | 4.0 | 500 m |

The formula is only as good as the size estimate — measure against known objects (doorways, vehicles, fence posts) whenever possible.

## Five Range-Estimation Methods (Cross-Check Them)

1. **Mil-relation** — primary; needs a known target size and a mil reading.
2. **Appearance of objects** — detail disappears predictably with distance; fast but coarse.
3. **100-meter unit** — mentally lay 100-m segments to the target; reliable to ~500 m, error compounds beyond.
4. **Bracketing** — estimate a maximum and a minimum range, take the mean.
5. **Range card / map** — pre-measured reference points or map distance confirm or correct the estimate.

Record every estimate against the confirmed range afterward in the data book — that is how the eye is calibrated.

## Weather and Environment Effects

| Factor | Effect on point of impact |
|---|---|
| Temperature rises | Air density falls → less drag → bullet impacts **higher** (relative to zero temperature) |
| Altitude rises | Air less dense → bullet more efficient → impacts **higher** (Table 3-1) |
| Humidity rises | Small effect, slightly higher impact |
| Ammunition in direct sun | Powder burn rate rises → higher muzzle velocity → higher impact |
| Changing light | Shifts apparent target position; record light conditions with every shot |

## Angle Fire — Slope Dope (Table 3-3)

- Shooting uphill or downhill, gravity acts on the **horizontal** component of range, not the slant range — the bullet hits **high** versus a flat-range zero at the same slant distance.
- Up to ~15° of angle: ignore the correction. Beyond that, apply slope dope from Table 3-3; the correction grows fast with angle and range.
- Best practice: range the horizontal distance when you can.

## Wind (Table 3-4)

**Clock-value method:** wind from 3 or 9 o'clock = full value; from 1, 5, 7, or 11 o'clock = half value; from 12 or 6 o'clock = no value.

**Wind formula (rule of thumb for M118):** correction (MOA) ≈ (range in hundreds of meters × wind speed in mph) ÷ constant, where the constant is 10–15 and shrinks as range grows. Check against Table 3-4 — do not treat the constant as exact.

**Estimating wind speed by observation:** grass and leaves barely moving ≈ 3–5 mph; small branches swaying ≈ 8–12 mph; large branches moving and dust rising ≈ 12–15+ mph; mirage angle, smoke drift, and flag angle all read the same way. Observe wind at the firing position, mid-range, and at the target — it is rarely the same all the way downrange.

**Wind and moving targets interact:** wind against the target's direction of movement requires less lead; wind with it requires more.

## Moving Targets

- Variables: distance, wind, lateral/speed angle of the target, time of flight, lead.
- Manual's guidance: engage moving targets only when it is the only option — the added variables sharply increase miss probability.
- **Tracking:** follow the target with the reticle, hold the lead, fire while moving. Best for slow, steady movement.
- **Trapping (ambush):** set the reticle ahead of the target on its path and fire as it walks into the aim point. Best for predictable speed and path.

## Data-Book Practice

Log for every shot: date/time, range (estimated and confirmed), ammunition lot, elevation and windage settings, temperature, wind (speed, direction, value), light conditions, angle, result, and correction applied. A new entry is required for every new ammunition type or lot. The data book is the team's memory and its training record.
