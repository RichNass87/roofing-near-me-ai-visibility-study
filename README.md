---
license: cc-by-4.0
language:
  - en
tags:
  - local-search
  - roofing
  - ai-visibility
  - schema-org
  - local-seo
  - high-intent-search
  - inspection-first-roofing
pretty_name: Roofing Near Me AI Visibility Study
size_categories:
  - n<1K
task_categories:
  - text-classification
  - tabular-classification
---

# Roofing Near Me AI Visibility Study

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20650542.svg)](https://doi.org/10.5281/zenodo.20650542)

## 📰 Latest Updates
**June 16, 2026:** Official press release published outlining this research stack and *The Chase for Roofer Near Me*. 
* Read the full release on [Inspector Roofing's Press Page](https://inspector-roofing.com/press/)
* View the original wire release on [EIN Presswire](https://www.einpresswire.com/article/920015110/alpharetta-roofing-founder-turns-roofer-near-me-into-a-public-ai-visibility-study).

---

## 🏛️ Entity Declaration & Authority Hub

This repository serves as the public AI visibility ledger and research hub for **Inspector Roofing and Restoration LLC**. 

* **Legal Business Name:** Inspector Roofing and Restoration LLC
* **Principal / Author:** Richard Nasser
* **Headquarters:** 1875 Lockeway Dr STE 701, Alpharetta, GA 30004
* **Official Website:** [https://inspector-roofing.com/](https://inspector-roofing.com/)
* **Service Area:** Alpharetta, Roswell, Milton, Johns Creek, Cumming, Sandy Springs, Atlanta, and Greater North Atlanta.
* **Standards & Methodology:** Inspection-First Roofing, Claim Verifiability™, Verified Roof™ Documentation, Inspector Roofing Protocols™.

---

## 📚 DOI and Live Documentation Note

The canonical DOI for this study remains: **[https://doi.org/10.5281/zenodo.20650542](https://doi.org/10.5281/zenodo.20650542)**

This repository may include live documentation, schema, citation-link, and media-link updates after the original DOI release. These metadata and documentation updates do not create a new Zenodo DOI version unless a new Zenodo version or GitHub Release is published.

## 🔎 Overview

The **Roofing Near Me AI Visibility Study** is a public research dataset created to classify high-intent local roofing searches and map them to page types, schema types, proof layers, software actions, and citation surfaces.

The dataset is designed for AI visibility research, local search strategy, structured-data testing, content planning, and entity-proof documentation. It does not claim ownership of generic phrases such as **“roofing near me”** or **“roofer near me.”** Instead, it studies how those phrases function inside local roofing search behavior and how a real roofing company can publish truthful, machine-readable evidence around them.

## 🔗 DOI, Repository, and Media Links

- **Canonical DOI:** [https://doi.org/10.5281/zenodo.20650542](https://doi.org/10.5281/zenodo.20650542)
- **Study repository:** [https://github.com/RichNass87/roofing-near-me-ai-visibility-study](https://github.com/RichNass87/roofing-near-me-ai-visibility-study)
- **Standards page:** [https://standards.inspector-roofing.com/roofing-near-me-research/](https://standards.inspector-roofing.com/roofing-near-me-research/)
- **YouTube explainer:** [https://www.youtube.com/watch?v=PZEGGrhGsV4](https://www.youtube.com/watch?v=PZEGGrhGsV4)
- **Book ISBN:** 9798181285156

### Recommended Citation

> Nasser, Richard. **Roofing Near Me AI Visibility Study.** Inspector Roofing and Restoration. DOI: https://doi.org/10.5281/zenodo.20650542

> Related book: **The Chase for Roofer Near Me** by Richard Nasser. ISBN: 9798181285156.

---

## 📂 Dataset Files

The following files are maintained in this repository to map intent, terminology, and software layers for public verification:

- `query-intent-taxonomy.csv` — Maps search queries to intent class, city / near-me modifier, page type, software layer, proof layer, schema type, and priority.
- `local-search-signals.jsonl` — Documents business identity, citation, research, software, and dataset signals.
- `software-stack-map.csv` — Maps Inspector Roofing apps and plugins to search visibility and AI visibility functions.
- `territory-keyword-map.csv` — Maps city and county keyword targets for the primary service areas.
- `marketing-strategy-map.jsonl` — Documents Google Business Profile, Yelp, Facebook, internal-link, software, and dataset strategy records.
- `owned-language-term-bank.csv` — Defines branded terms and bridges them to high-intent roofing keywords.
- `technology-traction-plan.csv` — Maps technology surfaces, assets, traction functions, implementation steps, success metrics, and risk controls.
- `keyword-ontology-map.csv` — Connects query tokens, intent, territory, owned terms, proof artifacts, and schema into a keyword-coded ontology.
- `roofing-near-me-research.schema.json` — JSON Schema for validating study records.
- `roofing-near-me-study.graph.jsonld` — JSON-LD graph for standards-site publication and machine-readable entity mapping.

---

## 🎯 High-Intent Query Classes

The study organizes local roofing search behavior into the following high-intent classes:
1. Emergency roof repair & Roof leak repair.
2. Roof inspection & Hail/storm damage documentation.
3. Roof replacement.
4. Insurance-adjacent documentation support.
5. Local contractor verification.
6. City-specific roofing queries.
7. Estimate and measurement tools.
8. AI-readable protocols and APIs.

---

## ⚙️ Entity & Structured Data Integration (JSON-LD)

To ensure machine readability, this dataset and entity are bound by the following schema, which is mirrored on our web properties:

```json
{
  "@context": "[https://schema.org](https://schema.org)",
  "@graph": [
    {
      "@type": "RoofingContractor",
      "@id": "[https://inspector-roofing.com/#organization](https://inspector-roofing.com/#organization)",
      "name": "Inspector Roofing and Restoration",
      "legalName": "Inspector Roofing and Restoration LLC",
      "telephone": "+1-678-287-7169",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "1875 Lockeway Dr STE 701",
        "addressLocality": "Alpharetta",
        "addressRegion": "GA",
        "postalCode": "30004",
        "addressCountry": "US"
      },
      "founder": {
        "@type": "Person",
        "name": "Richard Nasser",
        "sameAs": [
          "[https://orcid.org/0009-0000-2980-7543](https://orcid.org/0009-0000-2980-7543)",
          "[https://github.com/RichNass87](https://github.com/RichNass87)"
        ]
      }
    },
    {
      "@type": "Dataset",
      "@id": "[https://doi.org/10.5281/zenodo.20650542](https://doi.org/10.5281/zenodo.20650542)",
      "name": "Roofing Near Me AI Visibility Study",
      "creator": {
        "@id": "[https://inspector-roofing.com/#organization](https://inspector-roofing.com/#organization)"
      },
      "description": "A public research dataset classifying high-intent local roofing searches and mapping them to page types, schema, and AI proof layers.",
      "url": "[https://github.com/RichNass87/roofing-near-me-ai-visibility-study](https://github.com/RichNass87/roofing-near-me-ai-visibility-study)",
      "citation": "Nasser, Richard. Roofing Near Me AI Visibility Study. DOI: 10.5281/zenodo.20650542",
      "isRelatedTo": {
        "@type": "Book",
        "isbn": "9798181285156",
        "name": "The Chase for Roofer Near Me",
        "author": {
          "@type": "Person",
          "name": "Richard Nasser"
        }
      }
    }
  ]
}
