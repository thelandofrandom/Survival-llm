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
- Batch B: Ranger, Visual Signals, Combatives, Warrior Ethos, Cold Weather — DONE 2026-11-08 (SKILL.md 3,720 / 4,034 / 2,710 / 3,344 / 2,873 words; all 5 full-text byte-verified). Batch handoff arrived late (delivered after coordinator verification + push); its counts match the coordinator's disk verification exactly. Two self-corrections by the batch: M249/M240B cyclic rates fixed against source table; Visual Signals paragraph numbers fixed (contact left is 1-16, not 1-15).
- Batch C: Warfighting, Radio, Scouting/Patrolling, MOUT, Marine Rifle Squad — DONE 2026-11-08 (verified on disk: SKILL.md 4,011 / 4,245 / 4,493 / 4,056 / 3,641 words; full-text bodies byte-identical to source .txt).

## Coordinator verification — all 25 (2026-11-08)
- 25/25 SKILL.md present, 2,648–4,493 words each (83,634 total, all in target range).
- 25/25 skill.yaml, all parse, unique names and unique descriptions.
- 25/25 references/full-text.md present; byte comparison: every body ends exactly with its source .txt (header only prepended). Spot-checks (SERE, Survival, Cold Weather): head/middle/tail passages match source.
- No dangling reference links in any SKILL.md; no missing skill.yaml or full-text.
- Total local skills tree: 158 files, 17.58 MB — exceeds the 16 MiB single-snapshot limit, so pushing in 2 snapshots: (1) batches A+B + README/CHANGELOG/BUILD_LOG (~6.6 MB), (2) batches C+D+E (~11.0 MB). PDFs and text/ extraction intermediates are NOT pushed.

## Push record — v0.1.0, all 25 skills live (2026-11-08)
- First attempt (6.3 MB single snapshot) FAILED with HTTP 413 request body too large — the MCP transport caps well below the documented 16 MiB snapshot limit. Working chunk size found: ~1.0–2.0 MB per push (1.99 MB OK, 6.3 MB fails). Future pushes: keep each snapshot ≤ ~2 MB.
- 12 snapshot pushes, all confirmed, sync record at `~/workspace/survival-llm.muse-github-snapshot-sync.json` (12 entries, 161 paths total):
  1. 97df5ab7 README/CHANGELOG + Visual Signals, Survival Evasion Recovery, Warfighting, Radio, Cold Weather
  2. de7bd0df First Aid, Rifle/Carbine, Land Navigation, Sniper Training
  3. f92fea7b SF Operations, Survival, Marine Rifle Squad
  4. cdd2912f Warrior Ethos, MOUT
  5. 724c0e8b Combatives, Ranger Handbook
  6. ba639ce7 Holistic Health and Fitness, TCCC / Casualty Response
  7. 23f306aa Scouting and Patrolling, Ground Reconnaissance
  8. 14b08c75 Military Mountaineering + BUILD_LOG
  9. 46a3fc03 SERE Operations
  10. a8453d69 Infantry Rifle Platoon and Squad
  11. fb806ea2 SF Medical Handbook
  12. 25d7f32b Commander's Tactical Handbook — was missed in the first chunking pass; caught by a local-vs-remote path reconciliation (155 vs 161) and pushed separately.
- Remote verified: 13 commits on main (12 mine + provider "Initial commit" 6992c529 generated on first upload, per the snapshot guide's warning). Spot-checked remote files: README.md, skills/commanders-tactical-handbook/SKILL.md, skills/sere/references/full-text.md (1,322,169 bytes) all present.
- Repo: https://github.com/thelandofrandom/Survival-llm (public, per David 2026-11-08)

## Expansion Wave 1 — Fieldcraft Survival (in progress, 2026-11-08)
- Fieldcraft category: 77 manuals; 7 overlap the 25 (Survival, SERE, Land Nav, Cold Weather, Mountaineering, Survival Evasion Recovery, +1), leaving 70 new. All 70 vault pages fetched — every one has a PDF URL (`fieldcraft_inventory.json`).
- Wave 1 = 25 manuals (5 batches x 5), PDFs downloaded + text extracted, all with real text layers (137–489 words/page; figure-heavy older manuals at the low end, no OCR needed):
  - Survival core: FM 21-76 Survival (646p), MCRP 3-02F Survival (571p), FM 21-76-1 Survival Evasion and Recovery (107p)
  - Personnel recovery: JP 3-50 (280p), FM 3-50 (104p), JP 3-50.2 (117p), JP 3-50.21 (149p), AFDP 3-50 (31p)
  - Arctic/cold/mountain: ATP 3-90.96 C2 (292p), MCTP 12-10E (292p), ATP 3-21.50 (200p), ATP 3-21.18 Foot Marches (168p), ATP 3-90.97 (156p), MCTP 12-10A (174p), MCRP 12-10A.1 W/CH-1 (240p), MCRP 12-10A.2 (116p), MCRP 12-10A.3 (420p)
  - Desert/jungle: ATP 3-90.99 C1 (180p), MCTP 12-10D (176p), MCTP 12-10C (208p), FM 90-3 (221p)
  - Combatives (older editions; TC 3-25.150/2017 stays current): FM 21-150 (232p), FM 3-25.150 (265p)
  - MWTC survival courses: Summer (180p), Winter (187p)
- Wave 2 (45 remaining Fieldcraft): CALL Desert Storm reports (3), 1940s manuals (Watermanship, Jungle Warfare, Snow/Extreme Cold, Mountain Ops, Tents, Clothing, Symbols, Soldier's Handbook, List of Films), older editions (FM 3-97.6, FM 3-97.61 2002, FM 21-18, FM 21-26, FM 21-77, FM 21-78, FM 31-25/30/35/36/70/71/72, FM 90-4/5/6, FM 70-10, FM 20-15/32/60, FM 21-7/15/30/100, FM 9-207, TM 21-210 Improvised Munitions, ST 31-205 Caching, TC 21-7 Finance, MCRP 7-20B/7-20B.5/8-10B.6 Water Survival, MCRP 3-02C, MCRP 3-40D.13 Base Camps, MCRP 12-10A, MCWP 3-35.6, Marine Hand-to-Hand Combat (18p).

## Wave 1 progress
- Batch C (mountain/cold/foot marches) DONE 2026-11-08, coordinator-verified: ATP 3-21.50 (3,449), ATP 3-21.18 Foot Marches (3,068), ATP 3-90.97 (2,854), MCTP 12-10A Mountain Warfare (2,518), MCRP 12-10A.1 (3,353). All 5 full-text bodies byte-verified (endswith source .txt). NOTE: batch's reported full-text word counts were again inflated vs disk (e.g. 94,911 claimed vs 94,243 on disk incl. header; source is 94,137) — files are correct, report numbers were wrong. Do not trust batch-reported full-text counts; always re-verify by byte comparison.
- Batch B (CSAR/Arctic) DONE 2026-11-08, coordinator-verified: JP 3-50.2 (4,157), JP 3-50.21 (3,593), AFDP 3-50 (3,013), ATP 3-90.96 Arctic (3,450), MCTP 12-10E Arctic (3,501). All 5 full-text byte-verified. Note: ATP 3-90.96 / MCTP 12-10E are the same joint publication under different Service numbers (texts differ only in front matter, ~46 words); skills are deliberately Army- vs Marine-framed and cross-reference each other. Batch-reported SKILL.md counts ran ~50–65 words high vs disk (tokenizer difference); disk counts are the true ones.
- Batch A (survival core) DONE 2026-11-08, coordinator-verified: FM 21-76 Survival (3,411), FM 21-76-1 (2,576), MCRP 3-02F Survival (3,116), JP 3-50 Personnel Recovery (2,681), FM 3-50 Army Personnel Recovery (2,662). All 5 full-text byte-verified. Notes: FM 21-76 carries explicit supersession note (ATP 3-50.21 is current authority); MCRP 3-02F is the Marine edition of the FM 21-76 lineage (document headed "FM 21-76/MCRP 3-02F"); FM 21-76-1 overlaps the existing survival-evasion-recovery skill (MCRP 3-02H, same multiservice publication) and is framed by chapter procedures.
- Batch D (mountain/desert/jungle) DONE 2026-11-08, coordinator-verified: MCRP 12-10A.2 Winter Mountain Leader (4,198), MCRP 12-10A.3 Mountain Leader's Guide (3,700), MCTP 12-10D Desert (2,885), MCTP 12-10C Jungle (3,298), FM 90-3 Desert (2,970). All 5 full-text byte-verified. Note: the two desert skills overlap on WBGT/water discipline — MCTP 12-10D is current joint doctrine, FM 90-3 is the deeper 1993 treatment with different water figures; each SKILL.md notes which is current where they differ.
- Batch E (combatives/MWTC/desert) DONE 2026-11-08, coordinator-verified: FM 21-150 Combatives (2,854), FM 3-25.150 Combatives (2,597), Summer Survival Course (3,424), Winter Survival Course (3,201), ATP 3-90.99 Desert Operations (3,188). All 5 full-text byte-verified. Both combatives skills carry supersession flags (TC 3-25.150/2017 current); FM 3-25.150 skill includes a three-editions comparison (1992 → 2002 → 2017).
- WAVE 1 COMPLETE 2026-11-08: 25/25 skills. Coordinator full sweep over all 50 skill dirs: no duplicate skill.yaml names/descriptions, no dangling reference links, no SKILL.md out of range, all 25 wave-1 full-texts byte-verified. README/CHANGELOG updated to v0.2.0 (50 skills, 12,651 pages, 164,843 SKILL.md words, ~3.7M full-text words).
- DUPLICATION DECISION (coordinator): ATP 3-90.99 / MCTP 12-10D are the same joint Desert Operations publication (4,529 of ~7,000 text lines shared) — kept as two separate skills, same as the Arctic pair (ATP 3-90.96 / MCTP 12-10E), Army- vs Marine-framed and cross-referenced. Same logic applies to any future joint-pub pairs.

## Push record — v0.2.0, wave 1 live (2026-11-08)
- 10 snapshot pushes, chunks ≤1.8 MB (w1-1 … w1-10), all confirmed. Sync record now 22 entries, 322 paths total. Local-vs-remote reconciliation: 322/322, nothing missing.
- Commits: addd2746 (FM 21-76, FM 21-76-1, MCRP 3-02F + docs), f3c91012, f7ec7d3e, cac1ab04, a328ddc5, a82b908a, 1f188123, 71cec8ab, 9e4e9baf, a576dd89 (ATP 3-90.99, completes wave 1). Remote: 23 commits on main (22 mine + provider Initial commit).
- Incident: one push call was accidentally dispatched twice in the same turn and the service restarted mid-run; the push had landed exactly once (verified by head SHA before any retry — no duplicate commit). Lesson: never dispatch the same push twice in one turn.
- Remote spot-check: skills/fm-21-76-survival/SKILL.md readable on remote.
- Repo now holds 50 skills. Remaining: 45 Fieldcraft (wave 2), then Medical/TCCC 219, Small Unit Tactics 408, Comms 567, Marksmanship 134 — 3,463 manuals still to go of 3,513.
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
