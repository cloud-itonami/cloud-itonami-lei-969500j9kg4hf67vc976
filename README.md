# cloud-itonami-lei-969500j9kg4hf67vc976

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by RATP Developpement.**

This repository archives the publicly published legal notice / terms of use of
**RATP Developpement** (RATP Dev), the international public-transport operating
subsidiary of the RATP Group (Paris), with source-url and retrieval-date
provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: RATP Developpement
- **LEI (ISO 17442)**: [969500J9KG4HF67VC976](https://search.gleif.org/#/record/969500J9KG4HF67VC976) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: FR
- **Website**: https://www.ratpdev.com
- **Ticker**: unlisted (international operating subsidiary of the state-owned RATP Group)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived legal notice/terms of use documents.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

RATP Dev operates urban bus, tram and metro networks under contract to transit
authorities in many countries outside France. This vertical's *generic, forkable*
Open Business Blueprint counterpart in the `cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921; the cross-reference exists so a reader
researching real-world urban-transit operators for market/competitive context can
find both the real company's published terms and the corresponding generic
governed-actor blueprint from one place.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
