# Retired Elite Donor → PAC Crosswalk

This file maps the "Retired" industry donors (Icahn, Paulson, Wexner, Black, Schwartzman, etc.) onto the PAC network that funds Lindsey Graham, Mike Johnson, and their Israel/evangelical messaging. The goal is to treat the "Retired" label as a funnel rather than a mystery: once those individuals surface, we grab the PAC list they touched so we can trace the same money into the rest of the GOP/DNC infrastructure.

| Donor | Core "Retired" identity | Known PACs funded | Evidence / Source |
| --- | --- | --- | --- |
| Carl Icahn | Listed as "retired" investor. | Turning Point PAC, Buckeye Values PAC, NRSC coordination committees (via the donor stack referenced in `analysis/lindsey_graham_israel_tag_summary.md`). | The Israel crosswalk repeatedly calls out the same donor quartet (`analysis/lindsey_graham_israel_tag_summary.md`, entries 2003–2021) feeding the Turning Point/Buckeye/Early Vote stack. |
| John Paulson | Retirement + hedge fund manager. | Turning Point PAC, Early Vote Action PAC, American Action Network, and NRSC-linked super PACs that collected his money between 2015–2024. | Same crosswalk plus the microtrend dataset (`analysis/lindsey_graham_israel_overlap.csv`, rows 3–21) that ties these donors to the PAC-funded warhawk narrative. |
| Leslie Wexner | Wexner/Maxwell co-conspirator; FEC filings list him as "retired." | Buckeye Values PAC/Buckeye Leadership Fund, New Albany PAC, Limited Brands PAC, and the Ohio PAC ecosystem, all of which also feed the NRSC/(AAN) pipeline that shuttles the money toward Graham/Johnson. | `network/pacs/BUCKEYE_VALUES_PAC.md` collects the Cleveland & WOSU evidence; the Buckeye crosswalk calls the same donors in `analysis/mike_johnson_donor_timeline_crosswalk.md`. |
| Leon Black | "Retired" private equity giant. | Turning Point PAC, Early Vote Action PAC, and the same NRSC/Jack-booted super PAC network because the crosswalk notes the same four donors financing Graham’s hawk pushes (`analysis/lindsey_graham_israel_overlap.csv` entries for 2011–2025). | 
| Stephen Schwarzman | "Retired" due to his Blackstone resignation. | Buckeye Values PAC, American Action Network, NRSC donors (Schwartzman/Blackstone appear across the microtrend rows and the `analysis/mike_johnson_donor_timeline_crosswalk.md` top stack). |

## How to use this crosswalk
1. **Follow the donor names** in OpenSecrets or FollowTheMoney — they keep showing the same `Retired` classification but the PACs they fund are the ones listed above. Use that list to filter future Grafana/Neo4j queries (tag them `#RetiredElite`).
2. **Tag the related PACs** (#Buckeye, #TurningPoint, #EarlyVote, #NRSC, #AAN) inside the timeline/microtrend rows so the next query for "Retired donors" returns both the people and the PACs/recipients.
3. **Compare across parties** by checking how these donors show up on the DNC side (e.g., Wexner contributions to red/blue campaigns). When they do, look for the same PAC list so we can demonstrate the circuit from Buckeye to NRSC to whichever candidate is on the roster.

## Next actions
- Drop this file into the master reporting brief and mark the `#RetiredElite` tag so it surfaces when we ask "Which donors are in the retired bucket?"
- When new FEC releases land, add the PAC list from this crosswalk to the timeline row so we can say, "See? He still owes his donors a pro-Israel vote because they keep funding the same PAC stack." 
