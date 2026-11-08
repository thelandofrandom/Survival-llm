# Survival LLM — Build Log

Started 2026-11-08. Source: T.REX ARMS Field Manual Vault (https://www.trex-arms.com/field-manual-vault).
All 25 manuals are US government public-domain publications. Distill, do not reproduce verbatim in full.

## Inventory — all 25 PDF URLs found, all downloaded

| # | Publication | Title | Branch | Date | Pages | PDF |
|---|---|---|---|---|---|---|
| 1 | TC 3-21.76 | Ranger Handbook | Army | 2025-09 | 380 | https://files.trex-arms.com/pdf/army/tc/tc_3-21-76_2025-09.pdf |
| 2 | ATP 3-50.21 | Survival | Army | 2018-09 | 228 | https://files.trex-arms.com/pdf/army/atp/atp_3-50-21_2018-09.pdf |
| 3 | FM 4-25.11 | First Aid | Army | 2002-12 | 224 | https://files.trex-arms.com/pdf/army/legacy/fm/fm_4-25-11_2002-01_2.pdf |
| 4 | MCDP 1 | Warfighting | Marine Corps | 2018-04 | 109 | https://files.trex-arms.com/pdf/usmc/mcdp/mcdp_1_undated.pdf |
| 5 | AFH 10-644 | SERE Operations | Air Force | 2017-03 | 652 | https://files.trex-arms.com/pdf/af/afh/afh_10-644_2017-03.pdf |
| 6 | MCRP 3-40.3B | Radio Operator's Handbook | Marine Corps | undated | 145 | https://files.trex-arms.com/pdf/usmc/mcrp/mcrp_3-40-3b_undated.pdf |
| 7 | FM 3-25.26 | Map Reading and Land Navigation | Army | 2001-07 | 246 | https://files.trex-arms.com/pdf/army/legacy/fm/fm_3-25-26.pdf |
| 8 | ATP 4-02.11 | Casualty Response / TCCC and First Aid | Army | 2026-03 | 254 | https://files.trex-arms.com/pdf/army/atp/atp_4-02-11_2026-03.pdf |
| 9 | MCTP 3-01A | Scouting and Patrolling | Marine Corps | 2020-07 | 314 | https://files.trex-arms.com/pdf/usmc/mctp/mctp_3-01a_undated.pdf |
| 10 | MCRP 12-10B.1 | MOUT | Marine Corps | 2018-04 | 371 | https://files.trex-arms.com/pdf/usmc/mcrp/mcrp_12-10b-1_undated.pdf |
| 11 | FM 23-10 | Sniper Training | Army | 1994-08 | 329 | https://files.trex-arms.com/pdf/army/legacy/fm/fm_23-10.pdf |
| 12 | MCRP 3-10A.4 | Marine Rifle Squad | Marine Corps | 2020-08 | 284 | https://files.trex-arms.com/pdf/usmc/mcrp/mcrp_3-10a-4_undated.pdf |
| 13 | TC 3-21.60 | Visual Signals | Army | 2017-03 | 96 | https://files.trex-arms.com/pdf/army/tc/tc_3-21-60_2017-03.pdf |
| 14 | TC 3-25.150 | Combatives (text: TC 3-22.150) | Army | 2017-03 | 408 | https://files.trex-arms.com/pdf/army/tc/tc_3-25-150_2017-03.pdf |
| 15 | ST 31-91B | U.S. Army Special Forces Medical Handbook | Army | 1982-03 | 210 | https://files.trex-arms.com/pdf/army/legacy/st/st_31-91b-.pdf |
| 16 | ATP 3-21.8 C1 | Infantry Rifle Platoon and Squad | Army | 2024-01 | 598 | https://files.trex-arms.com/pdf/army/atp/atp_3-21-8_2024-01_C1.pdf |
| 17 | MCRP 3-02H | Survival Evasion and Recovery | Marine Corps | 1999-06 | 107 | https://files.trex-arms.com/pdf/usmc/legacy/mcrp/mcrp_3-02h.pdf |
| 18 | FM 7-22 C1 | Holistic Health and Fitness | Army | 2020-10 | 240 | https://files.trex-arms.com/pdf/army/fm/fm_7-22_2020-10_C1.pdf |
| 19 | TC 3-21.75 | The Warrior Ethos and Soldier Combat Skills | Army | 2013-08 | 308 | https://files.trex-arms.com/pdf/army/tc/tc_3-21-75_2013-08.pdf |
| 20 | TC 21-3 | Soldier's Handbook for Individual Operations and Survival in Cold-Weather Areas | Army | 2025-09 | 136 | https://files.trex-arms.com/pdf/army/tc/tc_21-3_2025-09.pdf |
| 21 | TC 3-97.61 | Military Mountaineering | Army | 2025-11 | 432 | https://files.trex-arms.com/pdf/army/tc/tc_3-97-61_2025-11.pdf |
| 22 | FM 31-21 | Special Forces Operations | Army | 1969-02 | 142 | https://files.trex-arms.com/pdf/army/legacy/fm/fm_31-21_1969-01.pdf |
| 23 | MCRP 2-10A.6 | Ground Reconnaissance Operations | Marine Corps | 2018-04 | 407 | https://files.trex-arms.com/pdf/usmc/mcrp/mcrp_2-10a-6_undated.pdf |
| 24 | MCRP 3-11.1A | Commander's Tactical Handbook | Marine Corps | 1988-07 | 287 | https://files.trex-arms.com/pdf/usmc/legacy/mcrp/mcrp_3-11-1a.pdf |
| 25 | TC 3-22.9 C3 | Rifle and Carbine | Army | 2016-05 | 252 | https://files.trex-arms.com/pdf/army/tc/tc_3-22-9_2016-05_C3.pdf |

Total: 6,939 pages (vault lists ~6,500; pdfinfo counts above sum to 6,939 — use pdfinfo counts).
Extracted text: 2,016,554 words across all 25 (`~/workspace/survival-llm/text/*.txt`, via pdftotext -layout). All 25 have a real text layer; no OCR needed.
PDFs: `~/workspace/survival-llm/sources/*.pdf` (461 MB). Full inventory JSON: `inventory.json`.

## Progress
- 2026-11-08: Inventory complete, all 25 PDFs downloaded + text extracted. 5 batch subagents spawned (A–E, 5 manuals each).
- Batch A (priority): Survival, First Aid, TCCC, SERE, Land Navigation — DONE 2026-11-08 (verified on disk: SKILL.md 3,334 / 3,069 / 2,812 / 2,648 / 2,779 words; full-text bodies verified byte-identical to source .txt). TCCC note: no TXA/ketamine/fentanyl/morphine doses in the extracted ATP 4-02.11 text — skill covers what the manual contains, no CoTCCC doses imported.
- Batch B: Ranger, Visual Signals, Combatives, Warrior Ethos, Cold Weather — DONE 2026-11-08 (coordinator-verified on disk; batch handoff not yet received: SKILL.md 3,720 / 4,034 / 2,710 / 3,344 / 2,873 words; all 5 full-text byte-verified).
- Batch C: Warfighting, Radio, Scouting/Patrolling, MOUT, Marine Rifle Squad — DONE 2026-11-08 (verified on disk: SKILL.md 4,011 / 4,245 / 4,493 / 4,056 / 3,641 words; full-text bodies byte-identical to source .txt).

## Coordinator verification — all 25 (2026-11-08)
- 25/25 SKILL.md present, 2,648–4,493 words each (83,634 total, all in target range).
- 25/25 skill.yaml, all parse, unique names and unique descriptions.
- 25/25 references/full-text.md present; byte comparison: every body ends exactly with its source .txt (header only prepended). Spot-checks (SERE, Survival, Cold Weather): head/middle/tail passages match source.
- No dangling reference links in any SKILL.md; no missing skill.yaml or full-text.
- Total local skills tree: 158 files, 17.58 MB — exceeds the 16 MiB single-snapshot limit, so pushing in 2 snapshots: (1) batches A+B + README/CHANGELOG/BUILD_LOG (~6.6 MB), (2) batches C+D+E (~11.0 MB). PDFs and text/ extraction intermediates are NOT pushed.
- Batch D: Sniper, SF Medical, Infantry Platoon/Squad, Survival Evasion Recovery, H2F — DONE 2026-11-08 (verified on disk: SKILL.md 3,688 / 3,143 / 3,170 / 2,675 / 2,984 words; full-text.md present in all 5, word counts match source .txt modulo header). SF Medical carries prominent dated-medicine warning, no 1982 dosages, defers to ATP 4-02.11 (2026) TCCC. Sniper wind-formula constant hedged 10–15 (range-dependent).
- Batch E: Mountaineering, SF Operations, Ground Recon, Commanders Tactical, Rifle/Carbine — DONE 2026-11-08 (verified on disk: SKILL.md 4,293 / 2,789 / 3,144 / 2,750 / 3,229 words). CORRECTION to batch report: its claimed full-text word counts were inflated (e.g. mountaineering claimed 137,869, actual 136,717) — coordinator re-verified by byte comparison: all 5 full-text bodies end exactly with the source .txt (header only prepended), so files are correct; the report numbers were wrong, not the files. SF Operations carries prominent 1969 historic-doctrine flag. Rifle/Carbine: C3 dated Nov 2019 per skill (vault lists 2016 base).
- Full-text audit (coordinator, 2026-11-08): 24/25 full-text.md files present and byte-verified (body == source .txt + header). Only cold-weather-survival missing (Batch B still running).

## Full-vault crawl (2026-11-08, complete)
Crawled every category page (?fn=<cat>&page=N) at trex-arms.com/field-manual-vault. Categories are disjoint; counts match the vault's browse counts exactly.
- TOTAL UNIQUE MANUALS: **3,513** (full list: `full_inventory.json`, slugs + category + vault URL per item)
- By category: Sustainment 602, Comms Signal 567, Small Unit Tactics 408, Engineering 331, Fires 256, Medical/TCCC 219, Doctrine Philosophy 192, Leadership Training 184, Recon Intel 170, Aviation 158, Marksmanship Weapons 134, CBRN 129, Other 84, Fieldcraft Survival 77, Uncategorized 2
- The "602 publications" on the vault page is the Sustainment count only, not the vault total.
- Realistic scope for this run: the 25 recommended first, then Fieldcraft Survival (77), Medical/TCCC, Small Unit Tactics, Comms, Marksmanship in that order. 3,513 full skills is not feasible in a single run — report exact done/remaining counts, do not fake completion.
- Next step after the 25: fetch each additional manual's vault page for its PDF URL (same pattern as inventory.json), download + pdftotext, then build skills in batches of 5.

## Constraints / updates from David
- PUBLIC IS FINE (confirmed 2026-11-08). "Do not push" is LIFTED: push verified batches to thelandofrandom/Survival-llm as they complete (snapshot-push guide, verify on remote after). Push in batches — snapshot limit is 16 MiB / 2,000 files per push, and only UTF-8 text files (no PDFs/binaries in the push).
- EXPANDED SCOPE (2026-11-08): scrape as many vault manuals as you can, beyond the 25 recommended. Priority after the 25: Fieldcraft Survival, Medical/TCCC, Small Unit Tactics, Comms, Marksmanship. Full-vault crawl in progress (see below) — category counts sum to far more than 602; the "602" is just the Sustainment category count.
- VERBATIM FULL TEXT (2026-11-08, overrides earlier "do not reproduce verbatim"): every skill must include the raw extracted PDF text word-for-word in references/full-text.md (SKILL.md stays distilled, with a pointer). Header on full-text.md notes source publication, number, date, source URL, extraction method/date. Keep original PDFs under sources/ locally (do NOT push PDFs). Scanned PDFs with no text layer: OCR whole document (rapidocr pipeline), flag low-confidence/failed pages in this log. A skill is not complete without its full-text file, verified present/non-empty with length/pages roughly matching the PDF.
