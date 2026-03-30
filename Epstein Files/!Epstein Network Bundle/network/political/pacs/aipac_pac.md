# AIPAC PAC — Israeli Lobby Anchor Dossier

**Purpose:** Treat the AIPAC PAC as the primary money conduit inside the donor cluster. This dossier focuses on the 32 overlapping donors who feed both AIPAC PAC and the other committees we are tracking (UDP, DMFI, Republican Jewish Coalition, NORPAC), and logs the politicians who consistently receive the PAC’s support so we can trace the foreign influence timeline.

## 1. Overlapping donors
| Donor | State | Amount (from combined disclosures) | Other committees | Notes |
| --- | --- | --- | --- | --- |
| **Rodan, Amnon** | CA | $749K | United Democracy Project | Largest overlapping donor; flows through AIPAC PAC while simultaneously funding UDP media buys.
| **Greenberg, Lawrence** | MA | $305K | United Democracy Project | Shows the same dual-channel pattern that keeps UDP/Super PAC messaging consistent.
| **Baker, Paul** | AZ | $247K | DMFI PAC, United Democracy Project | Adds a DMFI tie to the AIPAC network, reinforcing conservative/Israel alignment.
| **Pava, Ann** | CT | $187K | DMFI PAC | Scales the same donor across DMFI/AIPAC multiple times.
| **Sandberg, Adele** | FL | $138K | DMFI PAC | Florida contributor bridging DMFI/AIPAC.
| **Snyder, Jeffrey** | FL | $125K | DMFI PAC, United Democracy Project | Triple overlap; this is the kind of donor to watch for new Super PAC activity.
| **Masor, Harold** | CA | $110K | United Democracy Project | East Coast/California connector.
| **Sternberg, Donna** | LA | $110K | United Democracy Project | Deep South donor allied with UDP.
| **Fain, Richard** | FL | $107K | United Democracy Project | Another Florida/UDP connection.
| **Platt, Julie** | CA | $80K | DMFI PAC | California DMFI inflow.
| **Rudy, Deborah** | TX | $64K | DMFI PAC, United Democracy Project | Texas donor mixing UDP and DMFI.
| **Meyers, Sara** | GA | $60K | United Democracy Project | Southeastern donor for UDP.
| **Fuchs, Russell** | FL | $57K | United Democracy Project | Propels Florida/Israel messaging.
| **Davis, Ann** | GA | $55K | United Democracy Project | Georgia tie (likely replicates broader GOP-Blue bridging). 
| **Dalezman, Jone** | MA | $50K | DMFI PAC, United Democracy Project | Northeast donor mixing DMFI/UDP.
| **Baker, Alice** | AZ | $37K | DMFI PAC | Adds to the DMFI sub-cluster.
| **Bassuk, Richard** | NY | $32K | DMFI PAC | New York presence overlapping political donors in our graph.
| **Langerman, Peter** | NJ | $30K | United Democracy Project | Adds the Atlantic corridor to UDP.
| **Silverman, Barry** | FL | $30K | United Democracy Project | Another Florida / UDP donor.
| **Ruby, Kenneth** | CA | $30K | United Democracy Project | California repeated investor.
| **Kohn, Lisa** | CA | $26K | DMFI PAC | DMFI contributor connecting to the Israel network.
| **Lindenbaum, Shari** | NJ | $26K | NORPAC | Bridges to traditional pro-Israel PACs.
| **Meyers, Stuart** | GA | $23K | United Democracy Project | Southeastern donor.
| **Fromer, Robert** | FL | $20K | United Democracy Project | Florida/UDP link.
| **Rosman, Martin** | VA | $17K | Republican Jewish Coalition PAC | Ties to RJC.
| **Rayant, Garry** | CA | $17K | DMFI PAC | Additional California donor.
| **Alterman, Ken** | WA | $15K | United Democracy Project | Adds West Coast coverage.
| **Rohr, Pamela** | NY | $15K | DMFI PAC | New York DMFI contributor.
| **Pincus, Robert** | DE | $10K | United Democracy Project | Delaware involvement.
| **Stern, Elizabeth** | NY | $10K | Republican Jewish Coalition PAC | RJC tie.
| **Marks, Leonard** | FL | $10K | United Democracy Project | Florida contributor.

> **Note:** these donors populate multiple PACs in the same narrative lane. Use this table as the canonical overlapping-donor reference when building GOY graph edges between AIPAC PAC and the other committees.

## 2. Who the PAC funds (key recipients)
- **Sen. Chuck Schumer (D-NY):** Leadership-level Israel/defense funding—AIPAC PAC ensures the leadership can shepherd Israel aid. (`network/political/schumer_aipac_mo.md`)
- **Sen. John Cornyn (R-TX):** GOP whip whose defense/border messaging matches AIPAC agendas and keeps the Senate coalition intact. (`network/political/cornyn_aipac_mo.md`)
- **Rep. Don Davis (NC):** UDP/IE coverage uses the same donor cluster; AIPAC PAC shares the `#ProIsrael` buy-in that keeps UDP media aligned with his messaging. (`network/political/don_davis_aipac_mo.md`)
- **Other `#ForeignAgentPolitician` suspects (Graham, Cruz, Johnson, Brown, Kasich, Clinton):** These politicians appear in the crosswalk because AIPAC PAC keeps them on message through donor coverage and IE work. Refer to `network/political/aipac_donor_politician_crosswalk.md` for the complete linking table.

## 3. PAC timeline + narrative nodes
- **2022–2023:** Donor contributions align with the first CHIPS/IRA push and the 2024 Israel supplemental planning cycles—every large gift from the table above hits in the same 2022–2024 window, meaning the PAC uses these same donors to keep the leadership pipeline afloat.
- **2024:** The November spike (post-Hamas/Israel escalation) is when many of these donors doubled down on AIPAC PAC, matching the procedure Schumer used to keep the Israel supplemental afloat even when border riders were a risk.
- **2025:** Even as Schumer loses the majority, AIPAC PAC remains the hedge that keeps him committed to Israel/Ukraine defense narratives; donors rely on the PAC to deliver the `#ConflictSpike` messaging in both chambers.

## 4. Next steps
1. Pull the AIPAC PAC contributions from `PAC_AIPAC_contributions.csv` into GOY nodes and tag each donor with `#Leadership`/`#LobbyCover` so queries reveal the repeated pattern.
2. Watch for new UDP/DMFI filings that include these donors—if any contributor disappears from AIPAC but shows up under a sibling PAC, flag the new file immediately.
3. Feed the crosswalk into the master political node so future investigations can follow the donor → PAC → politician path without re-parsing every CSV.
4. If new donors appear on the list, add them to this table with the same format and a precise note on what committees they are joining.
