# Hi, I'm Ruth-Anne Pai 👋

I build **open-source [Claude Science](https://www.anthropic.com) specialists and
skills** that give **patient-led nonprofits** — most often rare-disease
organizations — real scientific capacity: the ability to understand their disease
landscape, engage their community, work with the FDA, and help accelerate research
and therapeutic development.

Every specialist below is **discovery-first and non-prescriptive** — it does the
homework and lays out **tiered options to review**, and the leader decides.
Deliverables carry their sources, an assumption ledger, and honest caveats;
AI-generated analysis is always labeled as computational, never as a clinical or
validated result.

Each specialist repo is self-contained (`agent/` profile + `skills/` + a one-shot
`install.py`) and installs into a Claude Science workspace via the `repl` tool:

```python
exec(open("install.py").read())
```

## 🧭 Specialists for patient organizations & science capacity

| Specialist | What it does |
|---|---|
| [**EL-PFDD Navigator**](https://github.com/ruthannepai-tech/el-pfdd-navigator) | Plan and run an Externally-Led Patient-Focused Drug Development (EL-PFDD) meeting with the FDA — readiness → Letter of Intent → plan/budget → funding → meeting design → speaker support → patient-voice analysis → the Voice of the Patient report. *(+ 9 skills)* |
| [**Patient Organization Navigator**](https://github.com/ruthannepai-tech/patient-organization-navigator) | Understand where a disease area stands and where the gaps are — disease-landscape timelines, patient-journey gap maps, and capacity-building options tiered by cost. *(+ 3 skills)* |
| [**Stakeholder Landscaper**](https://github.com/ruthannepai-tech/stakeholder-landscaper) | Map the researchers, clinicians, patient orgs, nonprofits, and funders in a disease area into a filterable workbook + an interactive 3D network, with source/confidence tags on every row. |
| [**Research Infrastructure Architect**](https://github.com/ruthannepai-tech/research-infrastructure-architect) | Stand up the research **data infrastructure** — consent & data governance, patient registry, natural-history study, biobank, cross-source data linkage, research models — as designs the org owns and procures, with PII screened on arrival and consent as a gate. *(+ 6 skills)* |
| [**Regulatory & Trials Navigator**](https://github.com/ruthannepai-tech/regulatory-and-trials-navigator) | Navigate the **regulatory & clinical-trial** landscape — FDA-approval precedent, FDA engagement, recruitment feasibility, trial accessibility — grounded in retrieved records, never inventing an NCT/date/endpoint, never drafting a submission. *(+ 4 skills)* |
| [**Data & ML Strategist**](https://github.com/ruthannepai-tech/data-and-ml-strategist) | Make honest, **advisory** data & ML decisions — harmonize scattered org-owned data, assess ML-readiness, decide whether/when clinical ML is warranted — every model output labeled in-silico, never a clinical tool. *(+ 3 skills)* |
| [**Sustainability & Partnerships Strategist**](https://github.com/ruthannepai-tech/sustainability-and-partnerships-strategist) | Build **sustainability & partnerships** — community engagement, venture-philanthropy literacy, industry-partnership readiness, a Centers-of-Excellence footprint, scientific communications — as grounded, tiered options. *(+ 5 skills)* |
| [**Research Program Officer**](https://github.com/ruthannepai-tech/research-program-officer) | Run the **science-funder** side — grant-making program, Scientific Advisory Board, outcome-measure development, data-commons governance — with grantmaking (giving money out) behind an explicit scope gate. *(+ 4 skills)* |
| [**Nonprofit Capacity Strategist**](https://github.com/ruthannepai-tech/nonprofit-capacity-strategist) | Build **organizational capacity** — governance & board, legal-entity & compliance options, strategic plan & theory of change, staffing/volunteer scaling — as educational options to review with counsel, never legal advice. *(+ 4 skills)* |
| [**Development & Revenue Officer**](https://github.com/ruthannepai-tech/development-and-revenue-officer) | Build the **revenue engine** — fundraising operations, financial-sustainability modeling, brand & digital presence, a vendor-neutral CRM primer, a review of the org's existing donor data — from the org's own numbers, never invented figures. *(+ 5 skills)* |
| [**Policy & Field Strategist**](https://github.com/ruthannepai-tech/policy-and-field-strategist) | Grow **field-level influence** — coalitions & consortia, policy & advocacy (within nonprofit lobbying limits), newborn-screening / diagnostic-odyssey navigation, consensus clinical-care standards — as tiered options. *(+ 4 skills)* |

## 🔬 Specialists for therapeutic R&D

| Specialist | What it does |
|---|---|
| [**Therapeutic Program Architect**](https://github.com/ruthannepai-tech/therapeutic-program-architect) | End-to-end, human-in-the-loop drug-development pipeline — archetype-adaptive across common and genetic/rare disease, now including a `drug-repurposing-scout` for approved-drug repurposing signals. *(+ 9 skills)* |
| [**Inflammatory Target Analyst**](https://github.com/ruthannepai-tech/inflammatory-target-analyst) | Computational target discovery + antigen-specific therapeutic design for inflammatory/immune disorders (EGIDs, celiac, IBD, autoimmune). *(+ 3 skills)* |
| [**Protein Engineer**](https://github.com/ruthannepai-tech/protein-engineer) | In-silico protein-design bench: from a target + epitope to structurally validated, developable binders and multivalent scaffolds. *(+ 5 skills)* |
| [**Manuscript Architect**](https://github.com/ruthannepai-tech/manuscript-architect-agent) | Turn a completed program dossier into a bioRxiv-style preprint, run it through two rounds of synthetic peer review, and produce four bundled deliverables. |

## 🧩 Reusable skills & pipelines

Disease-agnostic building blocks the specialists compose — usable on their own:

- [**omics-target-mining**](https://github.com/ruthannepai-tech/omics-target-mining) — reproducible pipeline for mining public omics datasets (GEO, ARCHS4, and more).
- [**antigen-epitope-pipeline**](https://github.com/ruthannepai-tech/antigen-epitope-pipeline) — map antigen proteins to HLA-restricted epitopes.
- [**patient-centered-market-and-survey**](https://github.com/ruthannepai-tech/patient-centered-market-and-survey) — patient-centered therapeutic market reports + survey design.
- [**synthetic-peer-review**](https://github.com/ruthannepai-tech/synthetic-peer-review) — run a mock peer-review panel (editor + reviewers, multi-round) on a manuscript.
- [**project-archive-site**](https://github.com/ruthannepai-tech/project-archive-site) — package a project's chats and artifacts into a browsable static website.
- [**podcast-debrief-skill**](https://github.com/ruthannepai-tech/podcast-debrief-skill) — turn a project's artifacts into a fact-checked audio debrief.
- [**claude_science_videos**](https://github.com/ruthannepai-tech/claude_science_videos) — reusable skills for molecular & cell-scale scientific animation.

## ⚕️ Principles

- **The leader leads.** Outputs are resources to review, tiered by cost/effort/horizon — never a prescription.
- **Sourced, not invented.** No fabricated dates, costs, citations, or statistics; computational results stay labeled as such.
- **Honest framing.** No inflated hope about a prognosis or a therapy timeline; patient privacy and consent are protected.
- **Not** medical, legal, or financial advice.

*Built with [Claude Science](https://www.anthropic.com). All skills MIT-licensed.*
