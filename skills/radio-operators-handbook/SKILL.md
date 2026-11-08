# Radio Operator's Handbook

## Purpose

MCRP 3-40.3B (formerly MCRP 6-22C) *Radio Operator's Handbook* is the Marine Corps' field reference for the person who actually has to make radios work — the radio operator. It covers radio theory and propagation, single-channel HF/VHF/UHF equipment (principally SINCGARS), siting and grounding, antennas, interference, operations in unusual environments, electronic warfare, and the voice procedures (prowords, phonetic alphabet, message formats) that keep a net usable under stress. It is undated and 145 pages, and it is written to be carried: tables, checklists, and appendices dominate the back half.

Who it's for: anyone who must establish and maintain tactical voice/data communications in the field with manpack or vehicular radios — and, for the survival-LLM reader, anyone who needs to understand how far a radio really reaches, why a given frequency works at noon and fails at midnight, how to build a field-expedient antenna from wire, and how to talk on a net so the message gets through the first time. The core idea: communications is a system — transmitter, antenna, propagation path, receiver, operator — and the operator controls more of that system than the radio's specifications suggest. Antenna choice, siting, grounding, and procedure usually matter more than transmitter power.

## 1. Radio Principles — Theory and Propagation

A radio system has four basic components: transmitter, antenna (transmitting and receiving), the propagation medium (the air and the ionosphere), and receiver. The fundamental requirement is a reliable, secure, fast, and flexible communications network for the commander; the radio operator's job is to deliver it with the equipment on hand.

**Radio waves.** Radio waves are electromagnetic energy that travels at the speed of light (about 300,000 km/s). Two properties define any radio wave: frequency (cycles per second, hertz) and wavelength (the distance one cycle occupies). They are inversely related: wavelength in meters ≈ 300 ÷ frequency in MHz. A 30 MHz signal has a 10-meter wavelength; a 300 MHz signal has a 1-meter wavelength. This single relationship drives antenna length, propagation behavior, and equipment size — and it is the most useful formula in the whole handbook.

**Frequency bands and their characteristics.** The manual's Table 1-1 lays out what each band does:

| Band | Frequency | Behavior | Typical use |
|---|---|---|---|
| HF | 3–30 MHz | Sky wave reflects off the ionosphere; long range (hundreds to thousands of km); ground wave short range | Long-haul, beyond line of sight |
| VHF | 30–300 MHz | Line of sight plus limited ground wave; blocked by terrain | Tactical short-range (SINCGARS: 30–87.975 MHz) |
| UHF | 300–3,000 MHz | Line of sight only; highly directional; penetrates poorly | Air-ground, satellite, short-range data |

Higher frequency means shorter antenna, more bandwidth, and more dependence on line of sight. Lower frequency means longer range via the sky wave but bigger antennas and more atmospheric noise.

**Propagation modes.** Three ways a signal gets from transmitter to receiver:
- *Ground wave* — travels along the Earth's surface. Dominant at HF over short distances and at VHF/UHF only very close in. Range depends on frequency (lower is better), power, ground conductivity, and antenna height. Over seawater it goes far; over dry, rocky soil it dies quickly.
- *Sky wave* — radiates upward, reflects off ionized layers of the ionosphere, and returns to Earth far away. This is how HF reaches hundreds or thousands of kilometers. It depends on the ionosphere, which depends on the sun: the layers (D, E, F) change with time of day, season, and solar activity.
- *Line of sight (space wave)* — travels directly, or with a ground reflection, between antennas that can "see" each other. This is the VHF/UHF mode. Range is limited by the horizon: raising the antenna is the single most effective way to extend it. A manpack at ground level talks a few kilometers; the same radio on a hilltop or mast talks much farther.

**The ionosphere and the skip zone.** The ionosphere's F layer (about 260 km up, ~170 miles) reflects HF signals back to Earth for long-range communication (over 2,400 km / 1,500 miles). The D and E layers absorb energy during the day and fade at night. Two key frequencies govern any HF sky-wave path:
- *MUF (maximum usable frequency)* — the highest frequency that will reflect back to Earth over a given path at a given hour. Above the MUF, the signal passes through the ionosphere into space. MUF is always higher than the critical frequency and varies with time of day.
- *LUF (lowest usable frequency)* — the lowest frequency that will arrive strong enough to override atmospheric and man-made noise. Below the LUF, the signal is absorbed or drowned out. LUF depends on transmitter power and noise conditions.
- *Skip zone (skip distance)* — the gap between the outer edge of usable ground-wave coverage and the nearest point where the sky wave returns. Inside the skip zone, neither mode reaches: too far for ground wave, too close for sky wave. The operator's job is to pick a frequency between LUF and MUF that lands the signal on the target — and to know that the right frequency at noon is the wrong frequency at midnight.
- *Sunrise and sunset* are the hardest times for HF: the ionosphere is changing fastest, and frequencies that worked an hour ago fail. Solar disturbances (flares, storms) can black out HF for hours to days over whole regions, with no warning.

**Modulation and single sideband (SSB).** Modulation is impressing information onto a radio carrier wave. AM (amplitude modulation) varies the carrier's amplitude; FM (frequency modulation) varies its frequency. FM gives clearer voice and better noise rejection but needs more bandwidth and is limited to line of sight — which is why tactical VHF radios are FM. SSB is a form of AM used on HF: it strips away the carrier and one sideband, putting all the transmitter's power into a single sideband. The result is longer range and narrower bandwidth for the same power — the reason HF long-haul voice is usually SSB (upper sideband in military practice). The trade-off: SSB requires precise tuning; a slightly mistuned SSB signal is unintelligible.

## 2. Single-Channel Radio Equipment

**HF radio.** HF sets (e.g., the AN/PRC-104 family and its successors) provide long-range, beyond-line-of-sight communications via sky wave, plus short-range ground wave. HF is the fallback when VHF line of sight is blocked by terrain and when satellite is unavailable. Its weaknesses are large antennas, slow data rates, dependence on ionospheric conditions, and susceptibility to atmospheric noise. The operator must know frequency prediction (Appendix L) and be able to select frequencies for the time of day.

**VHF radio and SINCGARS.** The SINCGARS family (Single Channel Ground and Airborne Radio System) is the standard VHF-FM tactical radio for the Marine Corps, replacing the AN/PRC-77 and the AN/VRC-12 family. Key facts:
- Frequency range: **30 to 87.975 MHz**, FM.
- Configurations: manpack **AN/PRC-119**, vehicular AN/VRC-87/88/89/90/91/92, airborne variants. Seven configurations in total, built from common modules.
- Modes: single-channel (plain or secure voice) and **frequency hopping** — the radio hops across frequencies many times per second according to a shared hopset, which makes it very hard to jam or intercept. All stations on a net must share the same hopset, time, and transmission security key (TRANSEC) or they cannot communicate at all.
- The SIP (System Improvement Program) and ASIP (Advanced SIP) versions add data capability and reduced size/weight; the ASIP retains compatibility with older mounts.
- Range: roughly **8 km (5 miles) manpack-to-manpack** over average terrain in single-channel mode, extending to about **20 km (12.4 miles) for vehicle-mounted sets** under normal field conditions; frequency-hopping mode reduces range somewhat, and terrain, antenna, and siting dominate the real number. A whip antenna at ground level in a valley will not achieve these figures; the same radio on high ground with a proper antenna will exceed them.
- Power settings matter: use the lowest power that works. High power drains batteries, increases your electronic signature, and makes you easier to direction-find. SINCGARS employment factors are frequency, mode (single-channel vs. hopping), and power setting.

**UHF radio.** UHF (225–400 MHz military band) is line-of-sight, used mainly for air-ground communications, satellite access, and short-range data. UHF antennas are small; UHF signals are easily blocked by terrain and vegetation. UHF is also where most satellite communications (SATCOM) lives for tactical users.

**Data communications.** Radios carry data as well as voice: SINCGARS with a data adapter, HF modems, and dedicated data radios. Data rates on tactical radios are low by civilian standards (hundreds to a few thousand bits per second on HF; higher on VHF/UHF) and fall sharply with distance and interference. The operator's rule: keep data messages short, use the lowest data rate that the path supports, and expect retries.

## 3. Equipment Siting and Grounding

Siting — where you put the radio and its antenna — is the highest-leverage decision an operator makes. A well-sited low-power radio outperforms a poorly-sited high-power one.

**HF siting.** HF antennas need space and height. Site on high ground with a clear view toward the distant station; avoid valleys, dense forest, and proximity to power lines, metal structures, and other antennas. Keep the antenna clear of obstructions in the direction of transmission. For ground wave, low antennas and vertical polarization favor short-range; for sky wave, a horizontal dipole at roughly a half-wavelength height favors the low takeoff angles that reach distant stations.

**VHF/UHF siting.** Line of sight is everything: height is the dominant factor. Site on the highest ground available, with a clear line to the other station. Avoid depressions, the far side of ridges, and dense vegetation. Keep the antenna away from metal objects, vehicles, and other antennas (at least several meters separation to avoid interference and desensing). Never site in a location where the antenna is masked by terrain in the direction of the net.

**Grounding techniques.** A good ground is a low-resistance path to earth. It protects the operator and the equipment from lightning and static, reduces noise, and (for some antennas) is part of the radiating system. Field grounding procedure:
- Drive a ground rod (metal stake, at least 1 meter) into moist earth; in dry or rocky soil, dig down to moist earth or use multiple rods connected together.
- Keep ground leads short and thick — long thin wires add resistance and inductance.
- Bond all equipment grounds to a common point; never daisy-chain grounds through other equipment.
- In vehicles, bond the radio to the vehicle chassis; the vehicle body is the ground plane.
- Wet the ground around the rod with salt water in dry conditions to lower resistance.
- Never ground to a water pipe that may carry gas, and never use a ground rod as an anchor.

**Data communications siting.** Data modes are more sensitive to interference and multipath than voice. Site data stations with the same care as voice, keep antenna separation from other transmitters, and use the lowest power that sustains the link.

## 4. Antennas

The antenna is the most important and most neglected part of the system. A resonant antenna of the right length radiates efficiently; a wrong-length antenna wastes most of the transmitter's power as heat in the radio.

**The length formulas (memorize these).** For a half-wave dipole:
- Length in feet ≈ **468 ÷ frequency in MHz** (total length, both legs).
- Each leg (quarter-wave) ≈ **234 ÷ frequency in MHz** feet.
- For an inverted-L (vertical wire with a horizontal top section), Appendix N gives the same quarter-wave lengths in tabular form.
- A 30 MHz quarter-wave is about 7.8 feet; a 7 MHz quarter-wave is about 33 feet; a 3.5 MHz quarter-wave is about 67 feet. HF antennas are big — that is the price of long range.
- Always cut long and trim: an antenna that is slightly long can be shortened; one cut short must be rebuilt. Measure the standing wave ratio (SWR) if a meter is available; an SWR below 2:1 is acceptable, and high SWR means the antenna is mismatched and power is being reflected back into the radio.

**HF antennas.** The horizontal half-wave dipole (doublet) is the standard field antenna: two equal wires, fed in the center, strung as high as possible (ideally a half-wavelength, practically as high as you can get it). The inverted-L is a quarter-wave vertical wire with a horizontal top section — good when you cannot get a full dipole up, and better for ground-wave work. A long-wire antenna (a wire several wavelengths long, fed at one end) is directional and effective for a known distant station. Field-expedient antennas can be built from any wire — WD-1 field wire, stripped cable, even fence wire in an emergency — with insulators improvised from plastic, wood, or glass.

**VHF antennas.** The standard is the whip: a quarter-wave vertical (about 2.4 feet at 30 MHz, about 0.85 feet at 88 MHz — the standard 3-foot tape whip covers the band with a matching network). The whip is omnidirectional and simple. The OE-254 (and similar) is a broadband VHF antenna on a mast that greatly extends range for a command post. A directional antenna (Yagi) concentrates the signal toward the other station and can double or triple effective range — but it must be aimed, and it hears only in its direction.

**Antenna rules of thumb.**
- Higher is better — for VHF/UHF, height dominates everything else.
- Keep the antenna clear of metal, vegetation, and people; a hand on the whip detunes it.
- Keep antennas separated from each other to avoid interference.
- A resonant wire antenna beats a mismatched whip at the same power, every time.
- Never transmit with no antenna or a broken antenna attached — reflected power can destroy the transmitter's final amplifier.

## 5. Interference

Interference is anything that degrades the signal. Sources, in the manual's order:
- *Natural* — atmospheric noise (lightning, static), solar noise, cosmic noise. Worst at HF, worst at low frequencies, worst in summer and in the tropics.
- *Manmade* — power lines, generators, vehicle ignition, other transmitters, fluorescent lights, computers. Manmade noise is usually worse than natural noise at a tactical site — and it is the operator's fault if the generator is parked next to the antenna.
- *Poor equipment condition and improper usage* — low batteries, corroded connectors, damaged cables, wrong settings, transmitting on the wrong frequency or with the wrong mode. The most common cause of "the radio doesn't work" is the operator, not the radio.
- *Frequency interference and intermodulation* — two transmitters mixing in a receiver or in a corroded metal joint to create a third frequency. Keep transmitters separated; keep connectors clean and tight.
- *Unauthorized frequencies* — transmitting off the assigned frequency interferes with other nets and violates the communications plan.
- *Frequency reuse* — the same frequency used by two nets that are far enough apart not to interfere under normal conditions — until propagation changes and they do.

Troubleshooting sequence: check power/battery, check antenna and connections, check frequency and mode, check siting, move the antenna, change frequency, reduce power if overloading a nearby receiver. Most interference is fixed by moving the antenna or the noise source, not by adding power.

## 6. Radio Operations Under Unusual Conditions

**Desert.** Heat, dust, and dry ground. Dust gets into connectors and switches — keep equipment covered when not in use and clean connectors daily. Dry ground is a poor conductor, so ground-wave range falls and grounding is harder; wet the ground around ground rods. Heat degrades batteries; keep them shaded and cool. Thermal layers in the air can bend VHF signals unpredictably (ducting) — sometimes extending range, sometimes creating dead spots. Static electricity is severe: ground yourself before handling equipment.

**Jungle.** Vegetation absorbs VHF/UHF signals; ranges fall sharply, especially when foliage is wet. HF ground wave is often better than VHF in jungle. Antennas must be above the canopy if possible — a wire antenna hoisted into a tree works far better than a whip at ground level. Humidity corrodes connectors and causes leakage; inspect and dry equipment daily. Noise from insects and rain on foliage can mask weak signals.

**Cold weather.** Batteries lose capacity dramatically in cold — keep them warm (inside clothing, in an insulated container) and carry spares. Metal becomes brittle; connectors and cables crack. Snow and ice load antennas and detune them; clear ice and snow from antennas. Frozen ground is a poor ground — drive rods deeper or use counterpoise wires laid on the surface. Condensation when bringing cold equipment into a warm shelter causes corrosion; let equipment warm gradually and dry it.

**Mountainous areas.** Terrain blocks line of sight and creates shadows. The answer is height and relay/retransmission: put a retransmission station on a peak between two stations that cannot hear each other. A retrans station receives on one frequency and retransmits on another, extending the net over the ridge. Plan retrans sites in advance — they are the difference between a net that works and one that does not. Be aware that signals reflect off rock faces, creating multipath and ghosting.

**Special environments.** Urban areas: buildings block and reflect signals; use height (rooftops) and retrans. Near the sea: salt water is an excellent ground-wave conductor — HF ground wave goes far over water. In rain: heavy rain attenuates UHF and above more than VHF. In all environments, the operator's first tool is siting, not power.

## 7. Electronic Warfare

Electronic warfare (EW) is the fight for the electromagnetic spectrum, in three parts:

**Electronic attack (EA).** Actions to deny the enemy use of the spectrum: jamming (transmitting noise or false signals on his frequencies), deception (imitative deception — sending false traffic as if you were him; manipulative deception — altering your own emissions to mislead), and destruction of his electronic equipment. Jamming is most effective against fixed-frequency single-channel radios and least effective against frequency-hopping systems like SINCGARS, which is exactly why frequency hopping exists. If you are being jammed: reduce power (you may be jamming yourself via a nearby transmitter), change frequency, switch to an alternate net, move the antenna, use a directional antenna, or switch to an alternate means (messenger, wire).

**Electronic protection (EP).** Actions to protect your own use of the spectrum: frequency hopping, low power, short transmissions, directional antennas, emission control (EMCON — limiting or ceasing transmissions to avoid detection), proper siting, and good procedure. The most powerful EP measures are procedural: transmit only when necessary, keep transmissions short, use brevity codes and prowords, never transmit your location in the clear, and never chatter. A radio operator who talks too much is a beacon for direction-finding.

**Electronic warfare support (ES).** Actions to search for, intercept, identify, and locate enemy emissions — direction finding (DF) and intercept. The enemy does this to you. Assume every transmission is intercepted and located: that assumption drives good procedure. The manual's standing warning is that a radio net that transmits continuously, at high power, from a fixed location, will be found, jammed, and targeted.

**Anti-jam checklist.**
- [ ] Confirm it is jamming, not interference or equipment failure (check another frequency, another radio)
- [ ] Reduce power; move the antenna; change antenna polarization or type
- [ ] Switch to the alternate frequency or alternate net per the communications plan
- [ ] Switch to frequency-hopping mode if in single-channel
- [ ] Use a directional antenna aimed at the distant station
- [ ] Shorten transmissions; use brevity codes
- [ ] If still jammed, use an alternate means (messenger, wire, visual signals) and report the jamming up the chain

## 8. Voice Procedure — The Discipline That Makes Nets Work

Voice procedure exists because radio is a shared, half-duplex, noisy medium: only one station can transmit at a time, everyone hears everything, and the signal may be weak. The rules are simple and non-negotiable.

**The phonetic alphabet (Appendix D).** Alfa, Bravo, Charlie, Delta, Echo, Foxtrot, Golf, Hotel, India, Juliett, Kilo, Lima, Mike, November, Oscar, Papa, Quebec, Romeo, Sierra, Tango, Uniform, Victor, Whiskey, X-ray, Yankee, Zulu. Use it for any letter that could be confused — call signs, grid coordinates, names. Pronounce numbers digit by digit (Appendix E): "tree" for 3, "fower" for 4, "fife" for 5, "niner" for 9, "zero" for 0. Say "decimal" for a decimal point, "minus" for negative.

**Key prowords (Appendix C).** The vocabulary of the net:
- **OVER** — my transmission is ended and I expect a response.
- **OUT** — my transmission is ended and I expect no response. Never say "over and out" — it is a contradiction.
- **ROGER** — I have received your transmission satisfactorily. It does not mean "yes" or "I will comply."
- **WILCO** — I have received your message, understand it, and will comply. (Implies ROGER.)
- **SAY AGAIN** — repeat your last transmission (optionally: "say again all before/after [word]").
- **I SAY AGAIN** — I am repeating my transmission.
- **CORRECTION** — an error has been made; the correct version follows.
- **WAIT** / **WAIT OUT** — I must pause (seconds / longer); do not transmit.
- **BREAK** — I am separating portions of a message.
- **I SPELL** — I will spell the next word phonetically.
- **FIGURES** — numbers follow.
- **MESSAGE** — a message follows (formal traffic).
- **READ BACK** — repeat this entire transmission back to me exactly.
- **WRONG** — your last transmission was incorrect; the correct version is…
- **DISREGARD THIS TRANSMISSION** — cancel it; ignore what I just sent.
- **AUTHENTICATE** — challenge/response authentication is required (Appendix J).
- **RADIO CHECK** — requesting a signal-strength report; reply with readability and strength ("Lima Charlie" — loud and clear — or "weak but readable").
- **SILENCE / SILENCE LIFTED** — cease transmissions / resume (imposed by the net control station).

**Calling procedure.** Call the station you want, then identify yourself: "Alpha Two, this is Alpha One, over." The called station answers: "Alpha One, this is Alpha Two, over." Keep calls short. The net control station (NCS) controls the net: stations transmit only when called or when they have traffic, and the NCS resolves conflicts. If two stations transmit at once, both are garbled — wait and try again.

**Message format (Appendix G).** Field messages are written on the standard message form in block capitals, with precedence and classification assigned from the table, the originating organization in the FROM block, addressees in the TO block, and a date-time group entered by communications personnel. Draft messages briefly but clearly — the drafter is responsible for clarity, and a long message on a bad circuit will be garbled and must be repeated. Classified messages go by secure voice or encrypted means only — never in the clear.

**The radio log (Appendix H).** The operator keeps a log of every transmission: time, stations involved, traffic summary. The log is the record of what was said and when — it resolves disputes, supports debriefing, and is a legal record. Keep it current; a log written from memory hours later is unreliable.

**Authentication (Appendix J).** Authentication proves you are who you claim to be. It uses challenge-and-response codes from the authentication tables: the challenger sends a challenge, the challenged station replies with the correct response. Authenticate when a station is unknown, when a message is suspicious, or when directed. Never authenticate with the same challenge twice, and never reveal the tables.

**The operator's checklist (Appendix P).** Before going on the air: battery charged and spare carried; antenna correct, intact, and connected; frequency, mode, and hopset verified against the communications plan; time synchronized (frequency hopping requires all stations on the same time); call signs and prowords known; message blanks and log ready; ground connected; siting checked for line of sight. After operations: log complete; batteries recharged; equipment cleaned, dried, and inspected; antenna stowed; report any faults.

## Output Contract

When answering from this skill, give numbers: frequency, wavelength, antenna length, expected range — with the conditions attached (terrain, height, mode, power). Recommend the lowest power that works and the highest antenna you can get. For any procedure question, give the prowords verbatim and the message format in order. When a user asks why a radio "doesn't work," run the troubleshooting sequence (power → antenna/connections → frequency/mode → siting → interference) before suggesting new equipment. Never assume satellite or cellular is available; default to the field-expedient answer. Cite chapter and appendix (e.g., "MCRP 3-40.3B, Ch. 4 — 468/f formula").

## Operating Rules

1. **The antenna is the radio.** A resonant antenna beats more power, every time. Cut long, trim to resonance, check SWR.
2. **Height is range.** For VHF/UHF, raising the antenna is worth more than raising the power.
3. **Lowest power that works.** High power drains batteries, increases your signature, and invites direction-finding.
4. **Short transmissions, good procedure.** Transmit only when necessary; use prowords; never chatter; assume you are being intercepted and located.
5. **Frequency is a function of time.** The HF frequency that works at noon fails at midnight. Know LUF and MUF; plan alternate frequencies.
6. **Siting before power.** Move the antenna or the station before adding power.
7. **Troubleshoot in order.** Power → antenna → frequency/mode → siting → interference. The operator is the most common failure.
8. **Frequency hopping only works if everyone shares the hopset, time, and key.** One station out of sync is off the net.

## References

- `references/propagation-bands.md` — radio wave theory, frequency band characteristics, propagation modes, ionosphere, MUF/LUF/skip zone, modulation and SSB
- `references/equipment-antennas.md` — SINCGARS and HF/UHF equipment, ranges, siting and grounding, antenna types and length formulas, field-expedient antennas
- `references/procedures-ew.md` — interference sources and troubleshooting, unusual environments, electronic warfare (attack, protection, support), voice procedure, phonetic alphabet, prowords, message format, authentication, radio log
- `references/full-text.md` — complete verbatim extracted text of MCRP 3-40.3B (pdftotext -layout, 2026-11-08); see header block for source details

Source: MCRP 3-40.3B *Radio Operator's Handbook*, U.S. Marine Corps, undated, 145 pages. PDF: https://files.trex-arms.com/pdf/usmc/mcrp/mcrp_3-40-3b_undated.pdf — Vault: https://www.trex-arms.com/field-manual-vault/mcrp-3-40-3b
