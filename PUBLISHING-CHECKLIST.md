# Publishing Checklist

## 1. GitHub

- Create or update a repository named `roofing-near-me-ai-visibility-study`.
- Upload `README.md`, `WHITEPAPER.md`, `CITATION.cff`, `data/`, and `schema/`.
- Add repository topics: `roofing`, `local-search`, `ai-visibility`, `schema-org`, `inspection-first-roofing`.
- Link back to `https://standards.inspector-roofing.com/`.

## 2. Hugging Face

- Create dataset: `InspectorRoofing/roofing-near-me-ai-visibility-study`.
- Upload `query-intent-taxonomy.csv`, `local-search-signals.jsonl`, `software-stack-map.csv`, `territory-keyword-map.csv`, `marketing-strategy-map.jsonl`, `owned-language-term-bank.csv`, `technology-traction-plan.csv`, and the dataset card.
- Add tags for local search, roofing, schema.org, and AI visibility.

## 3. Kaggle

- Create dataset: `Roofing Near Me AI Visibility Study`.
- Upload the CSV, JSONL, and SVG diagram files.
- Use a clear description: high-intent local roofing query taxonomy and AI-readable visibility mapping.

## 4. Standards Site

- Publish `website/roofing-near-me-research.html` as a new page.
- Suggested URL: `https://standards.inspector-roofing.com/roofing-near-me-research/`.
- Include JSON-LD graph from `schema/roofing-near-me-study.graph.jsonld`.
- Internally link to OpenAPI, protocols, negative evidence dataset, and inspection-first standard pages.

## 5. Main Inspector Roofing Site

- Add contextual links from:
  - Roofing service hub.
  - Roof repair page.
  - Roof inspection page.
  - Roof replacement page.
  - Alpharetta roofing page.
  - Press page.
  - Roof square estimator / InstantRoofView pages.
- Use natural anchor text, not repeated exact-match spam.

## 6. Citation Profiles

- Synchronize NAP and descriptions across GBP, BBB, LinkedIn, Facebook, Yelp, Bing Places, Apple Maps, and press profiles.
- Add the research URL only where it is natural and allowed.
- Add real field photos only; do not fabricate locations, EXIF, or reviews.

## 7. Search Console

Request indexing for:

- Standards homepage.
- Roofing Near Me AI Visibility Study page.
- OpenAPI YAML if hosted on the standards domain.
- Inspection-first language standard.
- Negative evidence dataset page.
- Roof damage verification protocol page.
- Main site pages that link to the research page.

## 8. Update Cadence

- Update datasets when new pages, cities, services, tools, or citations are added.
- Review sitemap and internal links weekly while publishing heavily.
- A daily sitemap regeneration is fine if pages change daily; otherwise every 3 days is enough. The important part is accurate lastmod dates, not artificial churn.

## 9. Zenodo DOI Loop

- Keep Zenodo enabled for public research/software repositories.
- Add or update `CITATION.cff`.
- Create a GitHub release after meaningful updates.
- Add the DOI badge to the README.
- Add DOI links to standards pages, dataset cards, and schema `citation` fields.
- Avoid releasing private data, customer data, credentials, API keys, or unsupported marketing claims.
