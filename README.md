# Survival LLM

A vault of U.S. military field manuals as agent skills, built from the [T.REX ARMS Field Manual Vault](https://www.trex-arms.com/field-manual-vault). Every manual here is a U.S. government public-domain publication.

Each skill in `skills/<slug>/` has:
- `SKILL.md` — distilled core doctrine, procedures, numbers, and checklists (2,600–4,500 words), plus when-to-use, output contract, and operating rules.
- `skill.yaml` — name, title, and a distinct description with trigger phrases.
- `references/*.md` — distilled chapter detail, tables, and checklists.
- `references/full-text.md` — the complete verbatim extracted text of the source PDF (header notes source, extraction method, and date).

## Skills (25) — the vault's Recommended set

| Skill | Publication | Title | Branch | Date | Pages | SKILL.md words | Full-text words |
|---|---|---|---|---|---|---|---|
| [survival](skills/survival/) | ATP 3-50.21 | Survival | Army | Sep 2018 | 228 | 3,334 | 81,867 |
| [first-aid](skills/first-aid/) | FM 4-25.11 | First Aid | Army | Dec 2002 | 224 | 3,069 | 48,517 |
| [tccc-casualty-response](skills/tccc-casualty-response/) | ATP 4-02.11 | Casualty Response / TCCC and First Aid | Army | Mar 2026 | 254 | 2,812 | 99,709 |
| [sere](skills/sere/) | AFH 10-644 | SERE Operations | Air Force | Mar 2017 | 652 | 2,648 | 207,405 |
| [land-navigation](skills/land-navigation/) | FM 3-25.26 | Map Reading and Land Navigation | Army | Jul 2001 | 246 | 2,779 | 62,740 |
| [ranger-handbook](skills/ranger-handbook/) | TC 3-21.76 | Ranger Handbook | Army | Sep 2025 | 380 | 3,720 | 91,900 |
| [visual-signals](skills/visual-signals/) | TC 3-21.60 | Visual Signals | Army | Mar 2017 | 96 | 4,034 | 10,252 |
| [combatives](skills/combatives/) | TC 3-25.150 | Combatives | Army | Mar 2017 | 408 | 2,710 | 67,063 |
| [warrior-ethos](skills/warrior-ethos/) | TC 3-21.75 | The Warrior Ethos and Soldier Combat Skills | Army | Aug 2013 | 308 | 3,344 | 78,333 |
| [cold-weather-survival](skills/cold-weather-survival/) | TC 21-3 | Soldier's Handbook for Individual Operations and Survival in Cold-Weather Areas | Army | Sep 2025 | 136 | 2,873 | 37,635 |
| [warfighting](skills/warfighting/) | MCDP 1 | Warfighting | Marine Corps | Apr 2018 | 109 | 4,011 | 22,575 |
| [radio-operators-handbook](skills/radio-operators-handbook/) | MCRP 3-40.3B | Radio Operator's Handbook | Marine Corps | undated | 145 | 4,245 | 31,327 |
| [scouting-patrolling](skills/scouting-patrolling/) | MCTP 3-01A | Scouting and Patrolling | Marine Corps | Jul 2020 | 314 | 4,493 | 109,286 |
| [mout](skills/mout/) | MCRP 12-10B.1 | Military Operations on Urbanized Terrain (MOUT) | Marine Corps | Apr 2018 | 371 | 4,056 | 99,927 |
| [marine-rifle-squad](skills/marine-rifle-squad/) | MCRP 3-10A.4 | Marine Rifle Squad | Marine Corps | Aug 2020 | 284 | 3,641 | 80,510 |
| [sniper-training](skills/sniper-training/) | FM 23-10 | Sniper Training | Army | Aug 1994 | 329 | 3,688 | 71,985 |
| [sf-medical-handbook](skills/sf-medical-handbook/) | ST 31-91B | U.S. Army Special Forces Medical Handbook | Army | Mar 1982 | 210 | 3,143 | 126,518 |
| [infantry-platoon-squad](skills/infantry-platoon-squad/) | ATP 3-21.8 C1 | Infantry Rifle Platoon and Squad | Army | Jan 2024 | 598 | 3,170 | 188,745 |
| [survival-evasion-recovery](skills/survival-evasion-recovery/) | MCRP 3-02H | Survival Evasion and Recovery | Marine Corps | Jun 1999 | 107 | 2,675 | 14,648 |
| [holistic-health-fitness](skills/holistic-health-fitness/) | FM 7-22 C1 | Holistic Health and Fitness | Army | Oct 2020 | 240 | 2,984 | 96,263 |
| [military-mountaineering](skills/military-mountaineering/) | TC 3-97.61 | Military Mountaineering | Army | Nov 2025 | 432 | 4,293 | 136,717 |
| [sf-operations](skills/sf-operations/) | FM 31-21 | Special Forces Operations | Army | Feb 1969 | 142 | 2,789 | 49,516 |
| [ground-reconnaissance](skills/ground-reconnaissance/) | MCRP 2-10A.6 | Ground Reconnaissance Operations | Marine Corps | Apr 2018 | 407 | 3,144 | 114,659 |
| [commanders-tactical-handbook](skills/commanders-tactical-handbook/) | MCRP 3-11.1A | Commander's Tactical Handbook | Marine Corps | Jul 1988 | 287 | 2,750 | 41,467 |
| [rifle-carbine](skills/rifle-carbine/) | TC 3-22.9 C3 | Rifle and Carbine | Army | May 2016 | 252 | 3,229 | 48,939 |

Totals: 25 skills, 6,939 source pages, 83,634 distilled SKILL.md words, ~2.0M words of verbatim full text.

## Notes and warnings

- **TCCC is current; older first aid is not.** ATP 4-02.11 (Mar 2026) is the current casualty-response / TCCC standard. Where FM 4-25.11 (2002) conflicts with it, the 2026 ATP wins. The TCCC skill contains no TXA/ketamine/fentanyl/morphine doses — those terms do not appear in the extracted ATP text.
- **ST 31-91B (1982) is dated medicine.** The SF Medical Handbook skill carries a prominent warning, quotes no 1982 drug dosages, and defers to current TCCC on any conflict. Its durable value is field diagnosis, austere care, and disease/field hygiene.
- **FM 31-21 (1969) is historic doctrine.** Vietnam-era unconventional-warfare organization; principles and organization are durable, TTPs and structures are not current.
- **Combatives numbering:** the vault lists TC 3-25.150; the manual text itself is TC 3-22.150.
- **Rifle and Carbine:** vault lists TC 3-22.9 C3 (2016); the C3 change is dated Nov 2019.

## Sources

- Vault: https://www.trex-arms.com/field-manual-vault
- PDFs: https://files.trex-arms.com/pdf/... (per-skill URLs are in each SKILL.md Source line and each full-text.md header)
- Extraction: `pdftotext -layout`, 2026-11-08. All 25 PDFs had a real text layer; no OCR was needed.
- Build log: [BUILD_LOG.md](BUILD_LOG.md). Full-vault inventory (3,513 manuals): `full_inventory.json` (local only, not pushed).

## Scope

The vault holds 3,513 manuals in total (crawled 2026-11-08). This repo starts with the 25 Recommended manuals; expansion proceeds by category — Fieldcraft Survival (77), Medical/TCCC (219), Small Unit Tactics (408), Comms Signal (567), Marksmanship Weapons (134) — in that order. See BUILD_LOG.md for progress.
