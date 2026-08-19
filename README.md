## Alberto Folch

I build AI systems for regulated markets.

For the last three years I've been the engineer on **Reli.AI (Ulpia)**, a legal-research
and regulatory-screening platform for Mexico. It is closed-source, so what follows is a
description rather than a link — happy to walk through any of it in detail.

**What it does**
- Maps **2M+ Mexican legal documents** — federal, state and municipal — into a queryable
  RDF knowledge graph, exposed over MCP tooling so both lawyers and AI agents can query it.
- Runs **KYC/AML screening across ~200 sources**: SAT 69-B, CNBV, SFP, PEP registries,
  debarment lists and international sanctions, normalised into a single matching layer.
- Serves **200+ paying customers** — lawyers, students and small firms.

**The actually hard part**
Mexican legal sources do not cooperate. No APIs. No stable schemas. PDFs whose layout changes
without warning. Thirty-two states each publishing to a different standard, and municipal
sources that are effectively unindexed. Most of the engineering was ingestion and
normalisation, not retrieval — and because I also ran support, I was the one on the phone
when a screening match came back wrong.

**Stack:** Python · TypeScript/JavaScript · GCP · REST APIs · RAG & embeddings · RDF · MCP · Flutter · SQL

---

### Public work

**[MRGNT](https://github.com/albertofolch/MRGNT)** — Full-stack site for an independent music
festival. Firebase Hosting, Cloud Functions and Firestore, an Express JSON API, a custom design
system and an admin panel for a non-technical team. Built and maintained solo.

---

Economist by training (Universidad Panamericana), engineer by practice.
Based in Mexico City · open to relocation · Spanish and English.

📫 albertofolch@outlook.com · [LinkedIn](https://www.linkedin.com/in/alberto-folch-1a4a79159/)
