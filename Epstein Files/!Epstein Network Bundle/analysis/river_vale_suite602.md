# River Vale / Suite 602 Asset Graph \(River Vale Corridor\)

**Objective:** Capture the physical/logistical graph connecting River Vale (NJ), Suite 602 (Delray Beach), Southern Trust, and the handler triad so we can treat the corridor as a single asset node with multiple document edges.

## Known nodes & addresses
| Node | Description | Source / Evidence |
| --- | --- | --- |
| **River Vale (NJ)** | Mail drop / logistics name used by the Delray handler triad. Appears in the moving-company dossier and the Jericho timeline, plus the PACER graph node `pacer-loc-river_vale`. | `analysis/river_vale_suite602.md`, `analysis/moving_companies.md`, `neo4j_node_neighbors` output (referenced documents `pacer-doc-unknown`, `pacer-doc-10_20_...`).
| **102 Seville A, Unit 1020** | Delray condo with the persistent $10 transfer loop (Basia McDonnell / Ornit Levinson-Suter / Sandra Messer / Sandra Messer / Karen Cullen / Katherine Hanley). Part of the same Southern Trust/Suite 602 handler circle. | `casefiles/2001-9-11/summary-delray.md`, `EPSTEIN_NETWORK/moving_companies_docs.md`, `analysis/jericho_delray_timeline.md`.
| **5300 W. Atlantic Ave, Suite 602** | Southern Trust legal address used by Indyke/Oldfield & the handler triad. Indiana operations referencing this address appear in Carbyne/Reporty emails and Southern Trust invoices. | `casefiles/operation-paperclip/carbyne-delray-wireline.md`, `analysis/jericho_delray_timeline.md`, `analysis/carbyne_doc_brief.md`.
| **River Vale / Nanuet / Wellington mail drops** | Shared mail-drops across the moving-company dossier, pipeline watch, and 2013/2019 filings (24/7 Anyday LLC, ASL Logistics, Southern Trust compliance). | `EPSTEIN_NETWORK/moving_companies.md`, `EPSTEIN_NETWORK/moving_companies_docs.md`, `analysis/carbyne_doc_brief.md`.

## Handler triad
- **Darren K. Indyke** – Legal advisor identified in EFTA02634615, sits at Suite 602 and wires Carbyne controlling-person compliance.
- **Stewart Oldfield** – Southern Trust partner referenced in Carbyne updates and Jericho/Southern Trust invoice crosswalk; tied to River Vale/Suite 602 operations.
- **Emma Pinkas** – Listed with the same handler triad in Southern Trust compliance threads (EFTA02636758); tie-in with the Santa Fe/Southern Trust wires.

## Neo4j evidence
- `neo4j_search_graph_nodes("River Vale")` returned the node `pacer-loc-river_vale` (source_dataset `pacer-courtlistener`).
- `neo4j_node_neighbors` for that node loaded two documents (`pacer-doc-unknown`, `pacer-doc-10_20_ao_121_form...`) linked by `REFERENCED_LOCATION`, showing River Vale appears in PACER filings tied to Southern Trust litigation.

## Timeline cross-linking
- Jericho timeline row for **21 Jun 2013** now includes the same handler triad plus trustee payments to Santurce (wire_0619) referencing the River Vale corridor.
- Carbyne/docs timeline crosswalk now sits on the same row (Mar 2019) to illustrate the corridor’s continuity (Santa Fe science → Jericho aviation → Carbyne intelligence). 

## Watch instructions
1. Tag any new doc (EFTA, PACER, or house oversight) referencing River Vale, Suite 602, or the handler names as part of this corridor.
2. Update this note whenever new nodes appear in Neo4j (use `neo4j_search_graph_nodes` for `Suite 602` or `Southern Trust` and `neo4j_node_neighbors` to grab the document edges). 
3. When the API stabilizes, re-run the `document_search` for `River Vale` or `5300 W Atlantic` to capture additional doc IDs for this graph.
