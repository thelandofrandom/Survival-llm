# Propagation and Frequency Bands (MCRP 3-40.3B, Chapter 1)

## Chapter outline

Section I. Theory and Propagation: Basic Components of Radio Equipment — Radio Waves — Radio Wave Propagation. Section II. Modulation and Single Side Band Transmission: Modulation — Single Side Band Transmission.

## The wavelength formula

Wavelength (meters) ≈ 300 ÷ frequency (MHz). Examples:

| Frequency | Wavelength | Quarter-wave |
|---|---|---|
| 3.5 MHz (HF) | ~86 m | ~21 m (70 ft) |
| 7 MHz (HF) | ~43 m | ~11 m (35 ft) |
| 30 MHz (VHF low) | 10 m | 2.5 m (8.2 ft) |
| 50 MHz (VHF) | 6 m | 1.5 m (4.9 ft) |
| 88 MHz (VHF high) | 3.4 m | 0.85 m (2.8 ft) |
| 400 MHz (UHF) | 0.75 m | 0.19 m (0.6 ft) |

## Frequency band characteristics (Table 1-1, paraphrased)

| Band | Range | Propagation | Strengths | Weaknesses |
|---|---|---|---|---|
| HF 3–30 MHz | Long (sky wave) to 2,400+ km | Ground wave short; sky wave via ionosphere | Beyond line of sight; no relay needed | Big antennas; ionosphere-dependent; noisy; slow data |
| VHF 30–300 MHz | Short (line of sight) | Ground wave + space wave | Clear FM voice; small antennas; SINCGARS band | Blocked by terrain; short range |
| UHF 300–3,000 MHz | Short (line of sight) | Space wave only | Small antennas; air-ground; SATCOM | Easily blocked; poor penetration |

## The ionosphere

- **D layer** (lowest): absorbs HF energy during the day; fades at night. Causes daytime absorption of low HF frequencies.
- **E layer**: used during the day for HF transmission over moderate distances; fades at night.
- **F layer**: remains at ~260 km (170 miles); used for long-range HF (over 2,400 km / 1,500 miles). Persists at night, though weaker.
- **MUF** (maximum usable frequency): highest frequency that reflects back over a given path at a given hour. Above MUF, the signal escapes into space. MUF is always higher than the critical frequency.
- **LUF** (lowest usable frequency): lowest frequency that arrives strong enough to override noise. Depends on transmitter power and noise level.
- **Skip zone**: the gap between the end of ground-wave coverage and the nearest sky-wave return. Inside it, neither mode reaches. Choose a frequency between LUF and MUF that lands on the target.
- **Sunrise/sunset**: hardest times for HF — the ionosphere changes fastest. Solar flares and storms can black out HF for hours to days with no warning.

## Modulation

| Type | How it works | Use |
|---|---|---|
| AM | Varies carrier amplitude | HF broadcast; simple |
| FM | Varies carrier frequency | VHF tactical voice; clear, noise-resistant, needs more bandwidth |
| SSB | Strips carrier and one sideband; all power into one sideband | HF long-haul voice; longer range, narrower bandwidth, needs precise tuning |

## Practical frequency selection

1. Day: use higher HF frequencies (MUF is higher); night: use lower HF frequencies.
2. Short path (under ~100 km): ground wave or near-vertical sky wave (low frequency, high-angle antenna).
3. Long path (hundreds of km): sky wave, frequency just below the MUF.
4. Always have an alternate frequency planned. Propagation changes; the net must move together.
