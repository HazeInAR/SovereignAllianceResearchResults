# Gratitude America → Aviation Shells Brief

**Purpose:** Capture the pilot/account overlap between the Gratitude America grant flow (BV70 money) and Epstein-linked aviation shells (Plan D/Hyperion/Freedom Air) for quick reference.

## Investigation summary (for newcomers)
- Gratitude America received the $10M BV70 LLC contribution and used it to fund scattered charitable recipients (2015–2018 990-PFs show few donors but multiple grants).
- The 2018 Schedule I (Schedule of Grants) lists twelve recipients; Manhattan and Los Angeles addresses dominate, mirroring where Epstein’s aviation shells operated.
- Plan D LLC, Hyperion Air, and Freedom Air Petroleum share the same pilot (Lawrence/Larry Visoski) and the same account team (Indyke/Kahn/Visoski) identified elsewhere in the DOJ documents (EFTA00104216 complaint and DOJ Exhibit A). Those pilots/execs manage the jets/helicopters cited in the same DOJ ledger that tracks Gratitude America payouts.
- The crosswalk file ties each shell to a subset of the 2018 recipients and flags the geographic overlap (NYC recipients ↔ Hyperion/Plan D, LA recipients ↔ Freedom Air). The USVI complaint (EFTA00104216) confirms the same corporate line-up (Plan D, Hyperion, Poplar, Nautilus). This is the pilot/account overlap we’re chasing.

## Current artifacts
1. `analysis/gratitude_2018_recipients.csv` — cleaned Schedule I data (name, amount, city, address) for each 2018 grant. Use it to trace downstream recipients.
2. `analysis/aviation_recipient_crosswalk.md` — narrative matrix linking the recipients to aircraft shells and highlighting what overlaps (pilot continuity, geography, next steps).
3. `analysis/gratitude_aviation_brief.md` — this newcomer-friendly summary.
4. DOJ complaint `EFTA00104216` (USVI v. estate): source for Plan D/Hyperion control by Visoski/Indyke/Kahn and the aircraft list (N212JE, N331JE, N722JE, GV-SP).

## Recent updates
- **Finance cross-check:** Handelsbanken memos EFTA01400438, EFTA01400751, EFTA01405104, and EFTA01411409 all call on Bella Klein to wire €3,000–€10,000 to Amar Siad (SWIFT HANDSESS, Stockholm IBAN). Those communications now live beside the Gratitude ledger so we can cite them when tracing the same Bella/Indyke/HBRK crew that funds the aviation shells Gratitude America backs.
- **Aircraft/crew overlap:** DOJ exhibit EFTA00021666 (and the linked entries through EFTA00021671) catalogs the Plan D/Hyperion tail numbers (N722JE, N415LM → N212JE, N908JE, N909JE) and the Visoski/Indyke/JEGE crew running them. The same tails appear in the Nov. 5–9 itinerary `UUQVDS` and the landing-permit rush (EFTA_R1_00025259), so the new doc payload `document_EFTA00021666.json` shows how the money (Handelsbanken → Amar Siad) converts into aircraft (Plan D/Hyperion jets) moving Epstein through Doha and Riyadh alone.

**Next steps:** use the crosswalk to find service providers/accounts that appear on both sides (e.g., shared addresses, banks, notaries) and document them for the channel.