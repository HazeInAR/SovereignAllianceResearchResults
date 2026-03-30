# PAC Investigation Dossier Index

**Purpose:** Track the PACs that overlap with the AIPAC / United Democracy Project / DMFI donor cluster so we can treat each committee as its own intelligence node. Each PAC listed below now has a dedicated sub-dossier inside `network/political/pacs/` that catalogs its overlapping donors, the politicians it funds, and the narrative anchors (`#AIPAC`, `#Leadership`, `#ProIsrael`, etc.) that tie it back into the mega-file.

## 1. PACs we are profiling
| PAC | Priority | Notes | Sub-dossier |
| --- | --- | --- | --- |
| **AIPAC PAC** | High | Anchor Israel lobby PAC, overlaps with the donor list that also funds Schumer, Cornyn, Davis, and other foreign-agent politicians. | `network/political/pacs/aipac_pac.md` |
| **United Democracy Project (UDP)** | High | Super PAC that spent $2.8M supporting Rep. Don Davis via media placements in 2022—use as example of how outside spending gets packaged into the Israel timeline. | `network/political/pacs/udp.md` |
| **DMFI PAC** | Medium | Conservative PAC that shares donors with AIPAC/UDP (Rodan, Baker, Fuchs, etc.); likely another vehicle to keep pro-Israel and conservative defense messaging on the air. | `network/political/pacs/dmfi_pac.md` |
| **Republican Jewish Coalition PAC** | Medium | Political arm of GOP Jewish donors; overlapping donors (Satell, Rosman, Stern) show the same money cycling through Israel/defense spending. | `network/political/pacs/rjc_pac.md` |
| **NORPAC** | Medium | Classic pro-Israel PAC; overlapping donors like Lindenbaum give it a foothold in the same network that funds the others. | `network/political/pacs/norpac.md` |

## 2. How to use this index
1. Use the donor/amount tables in each sub-dossier to link back to the `PAC_AIPAC_contributions.csv` rows and to the new `network/political/aipac_donor_politician_crosswalk.md` entries.
2. Each sub-dossier includes a “Recipients” list that identifies the politicians the PAC has either directly funded or indirectly enabled via media/IE spending—tag the matching suspect in the mega-file with `#ForeignAgentPolitician` and `#PACCover`.
3. Add new PACs to this table with the same format whenever another committee surfaces; the `network/political/pacs/` folder is where their donors, expenditures, and narrative anchors live.

## 3. Next steps
- Extract the overlapping donors list into the graph so GOY queries can show the shared funding nodes across these committees.
- If a PAC shows up in new `PAC_AIPAC_contributions.csv` exports or media buys, update its sub-dossier and crosswalk row immediately.
- Use these PAC files as the source when we build timelines for Schumer, Cornyn, Davis, and other triage nodes to show the donor → PAC → politician chain.
