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

Totals: 50 skills, 12,651 source pages, 164,843 distilled SKILL.md words, ~3.7M words of verbatim full text.


## Skills (25) — Expansion Wave 1: Fieldcraft Survival

| Skill | Publication | Title | Branch | Date | Pages | SKILL.md words | Full-text words |
|---|---|---|---|---|---|---|---|
| [fm-21-76-survival](skills/fm-21-76-survival/) | FM 21-76 | Survival | Army | Jun 1992 | 646 | 3,492 | 111,126 |
| [fm-21-76-1-survival-evasion-recovery](skills/fm-21-76-1-survival-evasion-recovery/) | FM 21-76-1 | Survival, Evasion, and Recovery | Army | Jan 1999 | 107 | 2,639 | 14,648 |
| [mcrp-3-02f-survival](skills/mcrp-3-02f-survival/) | MCRP 3-02F | Survival | Marine Corps | undated | 571 | 3,186 | 111,036 |
| [jp-3-50-personnel-recovery](skills/jp-3-50-personnel-recovery/) | JP 3-50 | Personnel Recovery | Joint | Jan 2015 | 280 | 2,731 | 87,360 |
| [fm-3-50-army-personnel-recovery](skills/fm-3-50-army-personnel-recovery/) | FM 3-50 | Army Personnel Recovery | Army | Sep 2014 | 104 | 2,707 | 44,140 |
| [jp-3-50-2-combat-search-rescue](skills/jp-3-50-2-combat-search-rescue/) | JP 3-50.2 | Doctrine for Joint Combat Search and Rescue | Joint | Jan 1996 | 117 | 4,207 | 33,726 |
| [jp-3-50-21-csar-ttps](skills/jp-3-50-21-csar-ttps/) | JP 3-50.21 | Joint TTPs for Combat Search and Rescue | Joint | Mar 1998 | 149 | 3,660 | 35,750 |
| [afdp-3-50-personnel-recovery](skills/afdp-3-50-personnel-recovery/) | AFDP 3-50 | Personnel Recovery | Air Force | Sep 2025 | 31 | 3,055 | 11,159 |
| [atp-3-90-96-arctic-cold-weather](skills/atp-3-90-96-arctic-cold-weather/) | ATP 3-90.96 C2 | Arctic and Extreme Cold Weather Operations | Army | Feb 2025 | 292 | 3,513 | 120,058 |
| [mctp-12-10e-arctic-cold-weather](skills/mctp-12-10e-arctic-cold-weather/) | MCTP 12-10E | Arctic and Extreme Cold Weather Operations | Marine Corps | Feb 2025 | 292 | 3,564 | 120,013 |
| [atp-3-21-50-mountain-cold-weather](skills/atp-3-21-50-mountain-cold-weather/) | ATP 3-21.50 | Infantry Small-Unit Mountain and Cold Weather Operations | Army | Jul 2025 | 200 | 3,504 | 94,243 |
| [atp-3-21-18-foot-marches](skills/atp-3-21-18-foot-marches/) | ATP 3-21.18 | Foot Marches | Army | Jul 2025 | 168 | 3,111 | 61,227 |
| [atp-3-90-97-mountain-cold-warfare](skills/atp-3-90-97-mountain-cold-warfare/) | ATP 3-90.97 | Mountain Warfare and Cold Weather Operations | Army | Apr 2016 | 156 | 2,906 | 69,890 |
| [mctp-12-10a-mountain-warfare](skills/mctp-12-10a-mountain-warfare/) | MCTP 12-10A | Mountain Warfare | Marine Corps | Jul 2024 | 174 | 2,569 | 68,231 |
| [mcrp-12-10a-1-mountain-warfare-leaders-guide](skills/mcrp-12-10a-1-mountain-warfare-leaders-guide/) | MCRP 12-10A.1 W/CH-1 | Small Unit Leader's Guide to Mountain Warfare | Marine Corps | May 2026 | 240 | 3,412 | 75,402 |
| [mcrp-12-10a-2-winter-mountain-leader](skills/mcrp-12-10a-2-winter-mountain-leader/) | MCRP 12-10A.2 | Winter Mountain Leader's Guide to Mountain Warfare | Marine Corps | May 2026 | 116 | 4,249 | 32,284 |
| [mcrp-12-10a-3-mountain-leaders-guide](skills/mcrp-12-10a-3-mountain-leaders-guide/) | MCRP 12-10A.3 | Mountain Leader's Guide to Mountain Warfare Operations | Marine Corps | Apr 2018 | 420 | 3,747 | 150,589 |
| [mctp-12-10d-desert-operations](skills/mctp-12-10d-desert-operations/) | MCTP 12-10D | Desert Operations | Marine Corps | Apr 2021 | 176 | 2,940 | 82,882 |
| [mctp-12-10c-jungle-operations](skills/mctp-12-10c-jungle-operations/) | MCTP 12-10C | Jungle Operations | Marine Corps | Sep 2020 | 208 | 3,352 | 101,626 |
| [fm-90-3-desert-operations](skills/fm-90-3-desert-operations/) | FM 90-3 | Desert Operations | Army | Jan 1993 | 221 | 3,019 | 61,871 |
| [fm-21-150-combatives](skills/fm-21-150-combatives/) | FM 21-150 | Combatives | Army | Jan 1992 | 232 | 2,922 | 30,003 |
| [fm-3-25-150-combatives](skills/fm-3-25-150-combatives/) | FM 3-25.150 | Combatives | Army | Jan 2002 | 265 | 2,665 | 36,389 |
| [summer-survival-course](skills/summer-survival-course/) | MWTC Summer Survival Course Handbook | Summer Survival Course Handbook | Marine Corps | Jan 2002 | 180 | 3,515 | 40,809 |
| [winter-survival-course](skills/winter-survival-course/) | MWTC Winter Survival Course Handbook | Winter Survival Course Handbook | Marine Corps | Jan 2002 | 187 | 3,291 | 41,950 |
| [atp-3-90-99-desert-operations](skills/atp-3-90-99-desert-operations/) | ATP 3-90.99 C1 | Desert Operations | Army | Apr 2021 | 180 | 3,253 | 82,745 |

Wave 1 totals: 25 skills, 5,712 source pages, 81,209 distilled SKILL.md words, 1,719,157 words of verbatim full text.

Notes: ATP 3-90.96 / MCTP 12-10E are the same joint Arctic publication under different Service numbers (Army- vs Marine-framed skills, cross-referenced). Same for ATP 3-90.99 / MCTP 12-10D Desert Operations (4,529 of ~7,000 text lines shared). FM 21-76 is superseded by ATP 3-50.21 as the current survival authority; the 1992/2002 combatives editions are superseded by TC 3-25.150 (2017).

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

The vault holds 3,513 manuals in total (crawled 2026-11-08). This repo now holds 50 skills: the 25 Recommended manuals plus 25 Fieldcraft Survival manuals (wave 1). Next: the remaining 45 Fieldcraft manuals, then Medical/TCCC (219), Small Unit Tactics (408), Comms Signal (567), Marksmanship Weapons (134). See BUILD_LOG.md for progress.
