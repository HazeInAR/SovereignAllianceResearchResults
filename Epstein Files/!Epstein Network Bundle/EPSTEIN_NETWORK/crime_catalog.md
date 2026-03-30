# Crime Catalog — Epstein Network Master Dossier

This file is the dedicated subdossier for the "greater Epstein network". It organizes the crimes we track into categories, points to the dossiers that document each bucket, and names the tags you should add to every associated file so the graph can link them later.

## Crime Categories & Reference Dossiers

### 1. Sex Trafficking / Exploitation (#sex-trafficking)
- **Core references:** `output/MISSING_PERSONS_BY_PROPERTY.md`, `EPSTEIN_NETWORK/zorro_dossier.md`, `VisaScheme/visa_scheme_dossier.md` (the Zorro visa/MC² pipeline sits here as the canonical representation of trafficking via the ranch and adjacent properties).
- **POIs to tag:** `network/pois/KALIN_JENNIFER.md`, `network/pois/KARYNA_SHULIAK.md`, `network/pois/RABUYO_LOUELLA.md`, `network/pois/KELLEN_SARAH.md`, `network/pois/GROFF_LESLEY.md` (add `#sex-trafficking`, `#visa-scheme`, `#zorro` when they appear together).
- **Why it matters:** The Zorro visa dossier demonstrates how victims were recruited, housed, and transported; it sits at the intersection of MC² housing control, the Zorro ranch logistics, and the transatlantic recruitment effort. Document the prey (West Mesa, NYC, USVI, Paris models) alongside the predators (Brunel, Maxwell, Epstein, Jennifer, Karyna) so we can pull a later graph that overlaps the same nodes with the same tags.

### 2. Visa Scam & Immigration Control (#visa-scheme)
- **Core references:** `VisaScheme/visa_scheme_dossier.md`, `VisaScheme/EINSTEIN_VISAS/MELANIA_ZAMPOLLI_CASE.md`, `output/louella_crispin_summary.md`, and `EPSTEIN_NETWORK/crime_catalog.md` itself as the map for these entries.
- **POIs to tag:** All visa beneficiaries (Karyna, Jennifer, Louella, Crispin, Verglas, Zampolli) plus the MC² housing units (301 E. 66th, 9 East 71st, 11P). Tag each file with `#visa-scheme`, `#ButterflyTrust`, `#MC2`, and `#zorro` as relevant to create the layered network.
- **Why it matters:** The visa scheme is the conveyor belt for trafficking victims. The new entries prove that trust-funded beneficiaries (Jennifer/Karyna) coordinated travel/logistics, that MC² housing served as the staging ground, and that the Zorro visa dossier sits inside the greater Epstein dossier as the narrative hub for this entire scam.

### 3. Money Laundering / Financial Gatekeepers (#money-laundering)
- **Core references:** Deutsche Bank compliance files (`EFTA00161594`, `EFTA00168866`, etc.), `EPSTEIN_NETWORK/epstein_network.md` (third-party network), the planned `output/DEUTSCHE_PIPELINE.md`, and the `Butterfly Trust` schedules (EFTA00064799, EFTA01387998, EFTA01363920).
- **POIs to tag:** Jennifer Kalin, Darren Indyke, Richard Kahn, Southern Trust Company, Ocean's Bridge, Caravaggio/Rubens shells, Donald Trump. Use `#money-laundering`, `#ButterflyTrust`, `#deutsche-bank`, `#Panama`, and `#EFTA01026813/14` tags so the ledger-style nodes overlap with the trafficking and visa nodes in the later graph.
- **Why it matters:** Epstein’s money managers hid payouts for visas, paid off staff, financed art laundering, and helped keep the Zorro ranch running—often via trophy purchases that Trump “rented his name” for, per the EFTA01026813/14 email. Documenting this completes the link between the money flows, the Panama Papers shellmasters, and the victims.
- **New Mexico Bridge:** Use `EPSTEIN_NETWORK/nm11_op-paperclip-summary.md` for the Bank Leumi branch 666/Southern Trust/Deutsche Bank wiring that feeds the JEGE/Jericho aviation hub so this category captures the PROMIS-era intelligence lineage.
- **Document note:** Add the Jan 15, 2019 email (EFTA01026813/14) to this crime catalog entry because it explicitly names Trump’s rental-name scheme, offshore guarantors (Xitrans), and the Panama Papers financiers, tying the same laundering architecture to the Deutsche/Southern Trust pipeline.

### 4. Intelligence / Influence Operations (#intelligence)
- **Core references:** `goy_series/GOY-06` (Intelligence Hypothesis), `network/pois/EPSTEIN_JEFFREY.md`, `analysis/aviation_recipient_crosswalk.md`. Tag these nodes with `#intelligence`, `#access-broker`, and `#intelligence-asset`.
- **POIs to tag:** Ghislaine Maxwell, Ehud Barak, Henry Kissinger, Alan Dershowitz, and the Zorro gatekeepers who connected them (e.g., Jennifer Kalin via the trust, Karyna via the trust). Add `#zorro` if they directly touched the ranch.
- **Why it matters:** Understanding Epstein’s intelligence/ geopolitical value is how the network can identify the overlords. The crime catalog gives these relationships a home and points to the graph-building work (we will overlay this with the sex trafficking tags later).

## The Zorro Visa Dossier & Tagging
- **Dossier:** `VisaScheme/visa_scheme_dossier.md` (also referenced by `EPSTEIN_NETWORK/zorro_dossier.md`). It sits in the master file as the `#visa-scheme` anchor for the MC²/Zorro intersection; tag it whenever you mention the ranch, MC², or visas in a person dossier.
- **Tags to include:** `#zorro`, `#visa-scheme`, `#sex-trafficking`, `#MC2`. The graph expects every mention of this dossier to present at least one of these tags so the later merge can align the nodes.

## Next Steps
1. Add these crime-category tags to the new POI files (Jennifer, Karyna, Louella) plus the existing ones we already maintain (Brunel, Maxwell, etc.).
2. When you create a longer person dossier, reference this crime catalog by pointing to the relevant category (e.g., “See Section 2 → Visa Scam for context”).
3. The planned graph extract will read the tags above—make sure every person or dossier referencing these crimes includes at least one of the tags in the YAML header (e.g., `Tags: #visa-scheme #zorro`).
4. This file will ultimately feed `NETWORK_GRAPH_OVERLAY.md` (TBD) where we pull the graph to see which people sit in multiple categories and who overlaps with the overlords.
