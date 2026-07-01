# Knowledge Packs — Stunspot's Guide to Investigative News Intelligence

The `knowledge-packs/` directory contains the model-facing corpus. Use these files when loading the canon into AI Projects, RAG systems, long-context workspaces, agent memory, local search, or research notebooks.

The `docs/` directory is only navigation and usage guidance. The actual report corpus lives here.

## Recommended Default

Use the **compiled packs** unless you have a specific reason not to.

They preserve the canon’s volume structure, keep related concepts together, and reduce upload friction for tools that perform poorly with many separate files. The source-report directory also contains the individual A–M reports for precise report-level retrieval and editing.

## Pack Types

| Pack | Files | Location | Best Use |
|---|---:|---|---|
| Source reports | 13 | `knowledge-packs/by-report/` | Precise retrieval, selective upload, report-level citation, targeted editing. |
| Compiled packs | 4 | `knowledge-packs/compiled-packs/` | Recommended default: grouped coverage with lower file count and full A–M sequence. |
| Omnibus | 1 | `knowledge-packs/omnibus/` | One-file import, local archive, whole-canon search, or strong long-context/RAG systems. |

## Selection Guide

Choose **source reports** when:

- your RAG system needs narrow provenance and report-level citation;
- you are editing or auditing a specific report;
- you want to load only one conceptual area, such as signal judgment or information operations;
- your tool chunks each file cleanly and preserves headings in metadata.

Choose **compiled packs** when:

- you are uploading the canon into an AI Project or NotebookLM-style workspace;
- your tool has file-count limits;
- you want the model to see each volume as a coherent conceptual unit;
- you need the full A–M sequence without loading one large omnibus file.

Choose the **omnibus** when:

- your system handles large files well;
- you want one canonical archive artifact;
- you are doing local search, grep-style lookup, or whole-canon embedding;
- your long-context model benefits from seeing the entire sequence in one contiguous document.

## Source Reports

The source reports are the canonical individual A–M units.

- [A. Reality Models, Event Ontology & Public-Reality Mapping.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/a-reality-models-event-ontology-and-public-reality-mapping.md) — ground reality, public reality, event ontology, traces, evidence, silence, uncertainty, confidence, and reality projection.
- [B. Signal, Evidence & Confidence Architecture.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/b-signal-evidence-and-confidence-architecture.md) — signal as relational value, the judgment stack, evidence classes, confidence ceilings, corroboration, and false convergence.
- [C. Information Ecosystems, Source Topologies & Platform Behavior.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/c-information-ecosystems-source-topologies-and-platform-behavior.md) — source topology, routing, origin nodes, bridge nodes, platform affordances, amplification, stabilization, decay, and resurfacing.
- [D. Topic Discovery, Weak-Signal Detection & Story Emergence.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/d-topic-discovery-weak-signal-detection-and-story-emergence.md) — weak signals, anomaly detection, pre-narrative coherence, latent story objects, escalation thresholds, maturation windows, and kill criteria.
- [E. Narrative Divergence, Coverage Gaps & Missingness Analysis.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/e-narrative-divergence-coverage-gaps-and-missingness-analysis.md) — comparative rendering, expected-versus-observed visibility, missingness, strategic silence, selective omission, and divergence analysis.
- [F. Thread Following, Link Expansion, and Investigative Graph Construction.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/f-thread-following-link-expansion-and-investigative-graph-construction.md) — entrypoint nodes, expansion operators, typed relations, directional asymmetry, edge status, entity resolution, and graph integrity.
- [G. Temporal Dynamics, Trend Formation, and Story Evolution.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/g-temporal-dynamics-trend-formation-and-story-evolution.md) — four investigative clocks, trigger events, substrate development, temporal regimes, phase transitions, narrative pivots, and delayed confirmation.
- [H. Power, Incentives & Strategic Actor Analysis.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/h-power-incentives-and-strategic-actor-analysis.md) — actors as strategic nodes, incentives, leverage, dependency, influence, control, alignment, coordination, and power mapping.
- [I. Propaganda, Narrative Laundering & Information Operations.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/i-propaganda-narrative-laundering-and-information-operations.md) — operation analysis, narrative seeding/routing/uptake, credibility laundering, false plurality, agenda manipulation, and memetic weaponization.
- [J. Implied Reality, Causal Inference, and Unstated-Truth Extraction.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/j-implied-reality-causal-inference-and-unstated-truth-extraction.md) — causal pressure, bounded inference, hidden knowledge states, hidden dependencies, second-order implications, contradiction resolution, and null nodes.
- [K. Editorial Prioritization, Escalation Logic & Intervention Strategy.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/k-editorial-prioritization-escalation-logic-and-intervention-strategy.md) — editorial importance, scarce-attention governance, lead quality, escalation logic, intervention choices, and kill criteria.
- [L. Failure Modes, Hallucinated Patterns & Analytical Breakdown.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/l-failure-modes-hallucinated-patterns-and-analytical-breakdown.md) — repetition versus corroboration, salience versus significance, false coherence, analytical contamination, and failure diagnosis.
- [M. Analyst Workflows, Research Artifacts & Publication Systems.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/by-report/m-analyst-workflows-research-artifacts-and-publication-systems.md) — workflow architecture, durable research artifacts, handoffs, publication systems, and execution discipline.

## Compiled Packs

The compiled packs are the recommended operational upload set.

- [[KNOWLEDGE] - Investigative News Intelligence - Vol. 1 A-C Foundations of Reality, Signal, and Judgment.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/compiled-packs/knowledge-investigative-news-intelligence-vol-1-a-c-foundations-of-reality-signal-and-judgment.md)
- [[KNOWLEDGE] - Investigative News Intelligence - Vol. 2 D-G Discovery and Thread Expansion Domains.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/compiled-packs/knowledge-investigative-news-intelligence-vol-2-d-g-discovery-and-thread-expansion-domains.md)
- [[KNOWLEDGE] - Investigative News Intelligence - Vol. 3 H-J Interpretation and Adversarial Sensemaking.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/compiled-packs/knowledge-investigative-news-intelligence-vol-3-h-j-interpretation-and-adversarial-sensemaking.md)
- [[KNOWLEDGE] - Investigative News Intelligence - Vol. 4 K-M Editorial Control, Failure Diagnosis, and Execution.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/compiled-packs/knowledge-investigative-news-intelligence-vol-4-k-m-editorial-control-failure-diagnosis-and-execution.md)

## Omnibus

- [[KNOWLEDGE] - Investigative News Intelligence - Omnibus.md](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence/blob/main/knowledge-packs/omnibus/knowledge-investigative-news-intelligence-omnibus.md)

Use the omnibus when continuity matters more than modularity.
