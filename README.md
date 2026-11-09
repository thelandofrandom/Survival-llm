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
| [scouting-patrolling](skills/scouting-patrolling/) | MCTP 3-01A | Scouting and Patrolling | Marine Corps | Jul 2020 | 314 | 4,499 | 109,286 |
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

## Skills (45) — Expansion Wave 2: Fieldcraft Survival (remaining 45)

| Skill | Publication | Title | Branch | Date | Pages | SKILL.md words | Full-text words |
|---|---|---|---|---|---|---|---|
| [fm-21-77-evasion-escape](skills/fm-21-77-evasion-escape/) | FM 21-77 | Evasion and Escape | Army | May 1958 | 176 | 4,500 | 35,054 |
| [fm-21-78-resistance-escape](skills/fm-21-78-resistance-escape/) | FM 21-78 | Resistance and Escape | Army | Jun 1989 | 4 | 949 | 647 |
| [call-winning-in-the-desert](skills/call-winning-in-the-desert/) | CALL Newsletter (ADA446544) | Winning in the Desert | Army | Aug 1990 | 32 | 1,645 | 14,191 |
| [call-combat-training-centers-desert-storm](skills/call-combat-training-centers-desert-storm/) | ARI Technical Report 970 | How Well Did the Combat Training Centers Prepare Units for Combat? | Army | Jan 1993 | 31 | 1,544 | 8,046 |
| [call-desert-storm-challenges](skills/call-desert-storm-challenges/) | ARI Research Report 1633 | Desert Storm Challenges: An Overview of Desert Storm Survey Responses | Army | Jan 1993 | 100 | 2,556 | 29,589 |
| [fm-21-22-watermanship](skills/fm-21-22-watermanship/) | FM 21-22 | Watermanship | Army | Apr 1944 | 156 | 3,995 | 28,512 |
| [fm-72-20-jungle-warfare](skills/fm-72-20-jungle-warfare/) | FM 72-20 | Jungle Warfare | Army | Oct 1944 | 146 | 3,150 | 36,525 |
| [fm-70-15-snow-extreme-cold](skills/fm-70-15-snow-extreme-cold/) | FM 70-15 | Operations in Snow and Extreme Cold | Army | Nov 1944 | 264 | 3,734 | 62,041 |
| [fm-70-10-mountain-operations-1944](skills/fm-70-10-mountain-operations-1944/) | FM 70-10 | Mountain Operations (1944) | Army | Dec 1944 | 253 | 3,690 | 53,502 |
| [fm-21-15-clothing-equipment](skills/fm-21-15-clothing-equipment/) | FM 21-15 | Individual Clothing and Equipment | Army | Apr 1945 | 93 | 3,560 | 14,185 |
| [fm-21-30-military-symbols](skills/fm-21-30-military-symbols/) | FM 21-30 | Military Symbols | Army | Nov 1941 | 70 | 2,834 | 10,100 |
| [fm-21-100-soldiers-handbook](skills/fm-21-100-soldiers-handbook/) | FM 21-100 | Soldier's Handbook | Army | Dec 1940 | 262 | 4,053 | 66,853 |
| [fm-20-15-tents](skills/fm-20-15-tents/) | FM 20-15 | Tents and Tent Pitching | Army | Feb 1945 | 81 | 4,500 | 28,012 |
| [fm-21-7-war-department-films](skills/fm-21-7-war-department-films/) | FM 21-7 | War Department Films | Army | Jan 1945 | 333 | 3,945 | 113,159 |
| [fm-21-18-foot-marches](skills/fm-21-18-foot-marches/) | FM 21-18 | Foot Marches | Army | Jun 1990 | 130 | 4,500 | 24,381 |
| [fm-3-97-6-mountain-operations](skills/fm-3-97-6-mountain-operations/) | FM 3-97.6 | Mountain Operations | Army | Nov 2000 | 140 | 2,814 | 51,016 |
| [fm-90-6-mountain-operations](skills/fm-90-6-mountain-operations/) | FM 90-6 | Mountain Operations | Army | Jun 1980 | 152 | 2,936 | 40,710 |
| [fm-31-70-basic-cold-weather](skills/fm-31-70-basic-cold-weather/) | FM 31-70 | Basic Cold Weather Manual | Army | Apr 1968 | 203 | 3,749 | 81,603 |
| [fm-31-71-northern-operations](skills/fm-31-71-northern-operations/) | FM 31-71 | Northern Operations | Army | Jun 1971 | 199 | 2,931 | 66,050 |
| [fm-31-72-mountain-operations](skills/fm-31-72-mountain-operations/) | FM 31-72 | Mountain Operations | Army | May 1964 | 160 | 3,222 | 74,067 |
| [fm-31-36-night-operations](skills/fm-31-36-night-operations/) | FM 31-36 (TEST) | Night Operations | Army | Apr 1968 | 280 | 2,867 | 97,909 |
| [fm-31-30-jungle-operations](skills/fm-31-30-jungle-operations/) | FM 31-30 | Jungle Training and Operations | Army | Sep 1965 | 232 | 3,388 | 85,751 |
| [fm-31-35-jungle-operations](skills/fm-31-35-jungle-operations/) | FM 31-35 | Jungle Operations | Army | Sep 1969 | 132 | 2,601 | 66,550 |
| [fm-90-5-jungle-operations](skills/fm-90-5-jungle-operations/) | FM 90-5 | Jungle Operations | Army | Aug 1982 | 191 | 2,783 | 59,904 |
| [fm-31-25-desert-operations](skills/fm-31-25-desert-operations/) | FM 31-25 | Desert Operations | Army | Feb 1972 | 88 | 2,830 | 43,011 |
| [fm-20-60-battlefield-illumination](skills/fm-20-60-battlefield-illumination/) | FM 20-60 | Battlefield Illumination | Army | Jan 1970 | 79 | 4,480 | 28,406 |
| [fm-20-32-mine-countermine](skills/fm-20-32-mine-countermine/) | FM 20-32 | Mine/Countermine Operations | Army | May 1998 | 520 | 4,499 | 136,573 |
| [tm-21-210-improvised-munitions](skills/tm-21-210-improvised-munitions/) | TM 21-210 | Improvised Munitions Handbook | Army | 1969 | 256 | 2,764 | 38,494 |
| [st-31-205-caching](skills/st-31-205-caching/) | ST 31-205 | Special Forces Caching Techniques | Army | undated | 39 | 3,270 | 13,951 |
| [fm-90-4-air-assault](skills/fm-90-4-air-assault/) | FM 90-4 | Air Assault Operations | Army | Mar 1987 | 223 | 2,602 | 58,566 |
| [assault-climbers-handbook](skills/assault-climbers-handbook/) | Assault Climbers Handbook | Assault Climbers Handbook | Marine Corps | Summer 2002 | 296 | 4,446 | 72,597 |
| [fm-3-97-61-military-mountaineering-2002](skills/fm-3-97-61-military-mountaineering-2002/) | FM 3-97.61 | Military Mountaineering (2002) | Army | Aug 2002 | 328 | 4,497 | 110,168 |
| [attp-3-97-11-cold-region-operations](skills/attp-3-97-11-cold-region-operations/) | ATTP 3-97.11 / MCRP 3-35.1D | Cold Region Operations | Army / Marine Corps | Jan 2011 | 114 | 4,058 | 47,600 |
| [fm-21-26-map-reading-land-navigation](skills/fm-21-26-map-reading-land-navigation/) | FM 21-26 | Map Reading and Land Navigation | Army | May 1993 | 176 | 4,486 | 60,447 |
| [fm-9-207-cold-weather-ordnance](skills/fm-9-207-cold-weather-ordnance/) | FM 9-207 / TO 36-1-40 | Cold Weather Ordnance | Army / Air Force | Mar 1998 | 113 | 4,489 | 35,190 |
| [mcrp-7-20b-water-survival](skills/mcrp-7-20b-water-survival/) | MCRP 7-20B | Marine Corps Water Survival | Marine Corps | 2016 | 122 | 4,453 | 21,429 |
| [mcrp-7-20b-5-water-survival](skills/mcrp-7-20b-5-water-survival/) | MCRP 7-20B.5 | Marine Corps Water Survival | Marine Corps | undated | 122 | 4,484 | 21,429 |
| [mcrp-3-02c-marine-combat-water-survival](skills/mcrp-3-02c-marine-combat-water-survival/) | MCRP 3-02C | Marine Combat Water Survival | Marine Corps | Jan 2003 | 145 | 4,484 | 20,507 |
| [mcrp-8-10b-6-water-survival](skills/mcrp-8-10b-6-water-survival/) | MCRP 8-10B.6 | Marine Corps Water Survival | Marine Corps | May 2016 | 118 | 4,483 | 21,216 |
| [mcrp-3-40d-13-base-camps](skills/mcrp-3-40d-13-base-camps/) | ATP 3-37.10 / MCRP 3-40D.13 | Base Camps | Army / Marine Corps | Jan 2017 | 190 | 4,110 | 81,735 |
| [fm-3-25-combatives](skills/fm-3-25-combatives/) | FM 3-25 (FM 3-25.150) | Combatives | Army | Jan 2002 | 265 | 2,795 | 36,466 |
| [marine-hand-to-hand-combat](skills/marine-hand-to-hand-combat/) | NAVMC 1146-403 | Marine Hand-to-Hand Combat | Marine Corps | undated | 18 | 2,817 | 4,002 |
| [tc-21-7-financial-readiness](skills/tc-21-7-financial-readiness/) | TC 21-7 | Personal Financial Readiness and Deployability Handbook | Army | Aug 2003 | 101 | 4,445 | 40,082 |
| [mcrp-12-10a-mountain-warfare-2013](skills/mcrp-12-10a-mountain-warfare-2013/) | MCRP 12-10A.1 | Small Unit Leader's Guide to Mountain Warfare Operations (2013) | Marine Corps | May 2013 | 228 | 4,057 | 98,949 |
| [mcwp-3-35-6-desert-operations](skills/mcwp-3-35-6-desert-operations/) | MCWP 3-35.6 | Desert Operations | Marine Corps | Sep 2004 | 223 | 2,779 | 62,359 |

Wave 2 totals: 45 skills, 7,584 source pages, 157,774 distilled SKILL.md words, 2,201,534 words of verbatim full text.

Notes: FM 21-78 is table-of-contents only (the vault PDF holds only the TOC of the classified 1989 manual) — its skill is an honest short map, not the manual. FM 31-36 is Night Operations, not Jungle Operations as the vault labels it. FM 3-25 (2002) is the same manual as the wave-1 FM 3-25.150 skill (byte-identical extracted text) under its FM 3-25 numbering; MCRP 7-20B and MCRP 7-20B.5 are byte-identical PDFs; MCRP 8-10B.6 is the 2016 original renumbered to MCRP 7-20B.5 by erratum — all kept as separate skills, cross-referenced, per the joint-publication policy. The three short CALL reports and FM 21-78 are below the usual 2,500-word SKILL.md range because their sources are short; every other wave-2 SKILL.md is 2,500–4,500 words. Word counts in this table and the wave-1 table are Python whitespace-token counts; the v0.1.0 table used `wc -w`, which reads ~1–2% lower.

Grand totals: 95 skills, 20,235 source pages, 324,278 distilled SKILL.md words, 5,965,905 words of verbatim full text.

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

The vault holds 3,513 manuals in total (crawled 2026-11-08). This repo now holds 95 skills: the 25 Recommended manuals plus all 70 Fieldcraft Survival manuals (waves 1 and 2 — Fieldcraft is complete). Next: Medical/TCCC (219), Small Unit Tactics (408), Comms Signal (567), Marksmanship Weapons (134). See BUILD_LOG.md for progress.
