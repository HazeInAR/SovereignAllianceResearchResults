# River Vale Corridor Asset Linkage

**Purpose:** Document every property/address that couples with the River Vale/Suite 602 corridor so new filings (shells, deeds, invoices) can be matched immediately and the corridor map keeps growing.

## Asset nodes
| Address / asset | Notes / linkage | Reference |
| --- | --- | --- |
| **River Vale, NJ (mail drop)** | One of the earliest River Vale/Nanuet logistic handles tied to the Delray corridor. Appears in moving-company filings, River Vale corridor notes, and PACER via `neo4j_node_neighbors`. | `analysis/moving_companies.md`, `analysis/river_vale_suite602.md`, `neo4j_node_neighbors` output. |
| **102 Seville A, Unit 1020 (Delray condo)** | Repeated $10 nominee transfers (Basia McDonnell, Ornit Levinson-Suter, Sandra Messer, etc.) kept the Suite 602/Delray node within Southern Trust. Now cross-referenced to River Vale timeline and Jericho invoice crosswalk. | `casefiles/2001-9-11/summary-delray.md`, `casefiles/2001-9-11/hubs/Delray-dossier.md`, `analysis/jericho_delray_timeline.md`, `analysis/river_vale_suite602.md`. |
| **5300 W. Atlantic Ave, Suite 602 (Southern Trust)** | Official handler address that Indigo/Oldfield/Pinaks signed from; hosts Southern Trust compliance, Carbyne controlling-person threads, and the Jericho wiring instructions. | `analysis/carbyne_doc_brief.md`, `analysis/river_vale_suite602.md`, `analysis/jericho_delray_timeline.md`. |
| **119 Rockland Center, Suite 176, Nanuet, NY (UPS drop)** | Registered to 24/7 Anyday LLC (Dominik Suter) and repeated in the pseudonym watchlist; the mail-drop type expected for this corridor. | `EPSTEIN_NETWORK/moving_companies_docs.md`, `EPSTEIN_NETWORK/moving_companies.md`, `output/property_node_reference.md`. |
| **Wellington/other Florida mail drops** | Wellington and other Florida UPS centers share the same handler triad and show up on moving-company/corporate filings; they are likely secondary nodes for the corridor. | `EPSTEIN_NETWORK/moving_companies.md`, `analysis/river_vale_suite602.md`, `output/pseudonym_watchlist.md`. |
| **River Vale / Nanuet shared drop cluster** | Use this row as the master watchlist: any new registration using River Vale, 119 Rockland, or Suite 602 likely belongs to the corridor. | `output/pseudonym_watchlist.md`, `analysis/river_vale_suite602.md`, `EPSTEIN_NETWORK/moving_companies_docs.md`. |

## Watch instructions
1. When a new deed, LLC filing, or invoice mentions these addresses (especially 119 Rockland, River Vale, or Suite 602), add the document to `analysis/river_vale_suite602.md` and the `River Vale Corridor Timeline Overlay` so the asset map stays current.
2. If another mail drop appears in the dossier (new UPS suite, new Florida condo with a $10 transfer), treat it as a corridor extension and place it in this table with supporting docs.
3. Keep this note linked to the asset watchlist (`output/property_node_reference.md`, `output/pseudonym_watchlist.md`) so other analysts can cross-check before assuming a node is unrelated.
