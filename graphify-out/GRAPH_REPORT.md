# Graph Report - C:\Users\hass-\Desktop\workspace\claude_workspace\legal  (2026-06-21)

## Corpus Check
- Corpus is ~1,937 words - fits in a single context window. You may not need a graph.

## Summary
- 11 nodes · 14 edges · 3 communities (2 shown, 1 thin omitted)
- Extraction: 71% EXTRACTED · 29% INFERRED · 0% AMBIGUOUS · INFERRED: 4 edges (avg confidence: 0.85)
- Token cost: 61,400 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Datenschutzerklärung (Privacy Policy, GDPR Art. 13)|Datenschutzerklärung (Privacy Policy, GDPR Art. 13)]]
- [[_COMMUNITY_No Data Collection  No Cookies or Tracking|No Data Collection / No Cookies or Tracking]]
- [[_COMMUNITY_Impressum & Datenschutz  Legal Notice & Privacy Page|Impressum & Datenschutz / Legal Notice & Privacy Page]]

## God Nodes (most connected - your core abstractions)
1. `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)` - 7 edges
2. `Impressum & Datenschutz / Legal Notice & Privacy Page` - 4 edges
3. `Impressum (Legal Notice, § 5 DDG)` - 3 edges
4. `No Data Collection / No Cookies or Tracking` - 3 edges
5. `Self-Hosted Fonts (DM Sans / DM Serif Display)` - 3 edges
6. `Alexander Hass (Operator / Data Controller)` - 2 edges
7. `DSGVO Compliance Design Choices` - 2 edges
8. `GitHub Pages Hosting (US transfer, DPF + SCC)` - 1 edges
9. `Sales via Etsy (Etsy Ireland UC)` - 1 edges
10. `Data Subject Rights (GDPR Art. 15-21)` - 1 edges

## Surprising Connections (you probably didn't know these)
- `Impressum & Datenschutz / Legal Notice & Privacy Page` --references--> `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)`  [EXTRACTED]
  legal/index.html → legal/index.html  _Bridges community 2 → community 0_
- `Impressum & Datenschutz / Legal Notice & Privacy Page` --references--> `Self-Hosted Fonts (DM Sans / DM Serif Display)`  [EXTRACTED]
  legal/index.html → legal/index.html  _Bridges community 2 → community 1_
- `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)` --references--> `No Data Collection / No Cookies or Tracking`  [EXTRACTED]
  legal/index.html → legal/index.html  _Bridges community 0 → community 1_

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Third-party data processors disclosed (US/EU transfer chain)** — index_datenschutz, index_github_pages_hosting, index_etsy_sales [INFERRED 0.85]

## Communities (3 total, 1 thin omitted)

### Community 0 - "Datenschutzerklärung (Privacy Policy, GDPR Art. 13)"
Cohesion: 0.40
Nodes (6): Alexander Hass (Operator / Data Controller), Data Subject Rights (GDPR Art. 15-21), Datenschutzerklärung (Privacy Policy, GDPR Art. 13), Sales via Etsy (Etsy Ireland UC), GitHub Pages Hosting (US transfer, DPF + SCC), Impressum (Legal Notice, § 5 DDG)

### Community 1 - "No Data Collection / No Cookies or Tracking"
Cohesion: 1.00
Nodes (3): DSGVO Compliance Design Choices, No Data Collection / No Cookies or Tracking, Self-Hosted Fonts (DM Sans / DM Serif Display)

## Knowledge Gaps
- **4 isolated node(s):** `GitHub Pages Hosting (US transfer, DPF + SCC)`, `Sales via Etsy (Etsy Ireland UC)`, `Data Subject Rights (GDPR Art. 15-21)`, `Bilingual Language Toggle (DE/EN)`
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)` connect `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)` to `No Data Collection / No Cookies or Tracking`, `Impressum & Datenschutz / Legal Notice & Privacy Page`?**
  _High betweenness centrality (0.670) - this node is a cross-community bridge._
- **Why does `Impressum & Datenschutz / Legal Notice & Privacy Page` connect `Impressum & Datenschutz / Legal Notice & Privacy Page` to `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)`, `No Data Collection / No Cookies or Tracking`?**
  _High betweenness centrality (0.293) - this node is a cross-community bridge._
- **Why does `No Data Collection / No Cookies or Tracking` connect `No Data Collection / No Cookies or Tracking` to `Datenschutzerklärung (Privacy Policy, GDPR Art. 13)`?**
  _High betweenness centrality (0.174) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `No Data Collection / No Cookies or Tracking` (e.g. with `DSGVO Compliance Design Choices` and `Self-Hosted Fonts (DM Sans / DM Serif Display)`) actually correct?**
  _`No Data Collection / No Cookies or Tracking` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Self-Hosted Fonts (DM Sans / DM Serif Display)` (e.g. with `DSGVO Compliance Design Choices` and `No Data Collection / No Cookies or Tracking`) actually correct?**
  _`Self-Hosted Fonts (DM Sans / DM Serif Display)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `GitHub Pages Hosting (US transfer, DPF + SCC)`, `Sales via Etsy (Etsy Ireland UC)`, `Data Subject Rights (GDPR Art. 15-21)` to the rest of the system?**
  _4 weakly-connected nodes found - possible documentation gaps or missing edges._