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

## 🔬 Specialists for therapeutic R&D

| Specialist | What it does |
|---|---|
| [**Therapeutic Program Architect**](https://github.com/ruthannepai-tech/therapeutic-program-architect) | End-to-end, human-in-the-loop drug-development pipeline — archetype-adaptive across common and genetic/rare disease. *(+ 8 skills)* |
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
