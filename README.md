# Valtira

**Pokémon TCG collection management, portfolio tracking, and collector progression — a software engineering portfolio project.**

Valtira is an evolving web application designed to help Pokémon Trading Card Game collectors organize their cards, explore sets, follow collection value, and track collecting milestones.

> **Portfolio showcase:** This repository documents the product and engineering work. The full application source code is maintained in a separate private repository.

## Project overview

Collectors often need several different tools to manage a binder, look up a card, check prices, and track set completion. Valtira brings those workflows together in a unified experience designed for desktop and mobile browsers.

### Product capabilities

| Area | What it does |
| --- | --- |
| **Collection management** | Organize owned cards and track additions across a personal collection. |
| **Card & set exploration** | Browse a structured Pokémon TCG catalog and locate specific cards or sets. |
| **Pokédex tracking** | Connect card ownership with Pokémon species and collection-completion progress. |
| **Portfolio & pricing** | Aggregate collection valuation, refresh market prices, and store daily market snapshots. |
| **Collector achievements** | Reward progress with unlockable achievements, including hidden milestones. |
| **Watchlists & discovery** | Help collectors follow cards and explore releases. |
| **Collector profiles** | Support personal collector identity and evolving social features. |

Some features are actively being expanded and refined as development continues.

## Engineering highlights

**Accurate identity mapping.** The collection and Pokédex workflows distinguish individual card identities from Pokémon species so that owning one card does not incorrectly imply owning every card of that species.

**Catalog data pipeline.** The project uses versioned Pokémon TCG catalog artifacts derived from TCGdex. Publicly inspectable artifacts include provenance, source revision metadata, and checksum manifests.

**Resilient price workflows.** Market price refreshes are organized to handle batches of collectibles, while daily snapshots support a historical record separate from live prices.

**Iterative product development.** The project has grown through feature implementation, UI refinement, bug reproduction, regression checks, and publishing/testing cycles.

## Technology

- **Frontend:** React, JavaScript/TypeScript tooling, Vite, Tailwind CSS
- **Interface:** Component-based UI, React Router, responsive layouts
- **Data & backend integration:** Base44 SDK and application services
- **Catalog:** TCGdex-based generated data artifacts
- **Workflow:** Git/GitHub, local development, incremental testing

This is a **Base44-assisted application** with ongoing custom development and debugging, rather than a claim that every library or backend service was built from scratch.

## Public technical work

The [Valtira TCGdex Catalog](https://github.com/siqligit74/valtira-tcgdex-catalog) repository contains publicly available generated catalog artifacts and documents their provenance, normalization, and integrity checks.

The production application code remains private to protect the project while it is under active development.

## Screenshots and demo

Screenshots of the dashboard, collection, Pokédex, portfolio, and achievement experience will be added here.

A public demo link can also be added when the app is ready to be shown to prospective employers.

## Current focus

- Continue polishing card details, search, sorting, and filters
- Expand collector profiles and social workflows
- Improve regional card and sealed-product coverage
- Strengthen reliability and security around collection and market data
- Refine usability and accessibility for a broader collector audience

## Why I built it

This project combines two interests: collecting Pokémon cards and building practical software. It is an opportunity to work on a real product with interconnected features, external data, responsive interfaces, debugging challenges, and a long-term roadmap.

**Developer:** [siqligit74](https://github.com/siqligit74)

---

*Valtira is an independent fan-oriented software project and is not affiliated with, sponsored by, or endorsed by Nintendo, The Pokémon Company, or their partners. Pokémon and related marks belong to their respective owners.*
