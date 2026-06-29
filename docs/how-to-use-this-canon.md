# How to Use This Canon

This repository is built for model-facing use first. Human readers can read it directly, but its strongest use is as doctrine loaded into an AI workspace, retrieval corpus, project knowledge base, long-context session, or investigative research assistant.

The governing idea is simple: give the model a disciplined investigative ontology before asking it to evaluate public information. The canon helps the model preserve distinctions that ordinary summaries collapse: event versus claim, signal versus salience, evidence versus repetition, source proximity versus prestige, narrative operation versus mere spread, and inference versus speculation.

## Recommended Starting Point

For most AI/RAG systems, start with the **compiled packs** in `knowledge-packs/compiled-packs/`.

| Format | Path | Best For |
|---|---|---|
| Source reports | `knowledge-packs/by-report/` | Precise retrieval, selective upload, source-report citation, targeted editing. |
| Compiled packs | `knowledge-packs/compiled-packs/` | Recommended default for most AI projects and RAG systems. |
| Omnibus | `knowledge-packs/omnibus/` | One-file import, local archive, whole-canon search, strong long-context/RAG systems. |

## For AI Projects and Custom GPT-Style Knowledge

Upload the compiled packs unless your tool strongly prefers one file. The four-pack structure keeps conceptual boundaries intact while avoiding the overhead of ten separate source files plus the large omnibus.

After upload, instruct the model to treat the files as a **doctrine layer**, not as a live news database. The canon does not contain current event data. It teaches the reasoning architecture for handling current event data, public claims, evidence fragments, omissions, actor behavior, and narrative operations.

Useful instruction seed:

```text
Use Stunspot's Guide to Investigative News Intelligence as a reasoning doctrine for investigative analysis. When evaluating public information, distinguish events, claims, evidence, traces, signal, salience, source topology, narrative operations, actor incentives, and bounded inference. Preserve uncertainty and provenance. Do not treat repetition, virality, prestige, or moral intensity as corroboration. Prefer upstream sources, orthogonal evidence, typed relations, explicit confidence, and rival explanations.
```

## For RAG Pipelines

Use the source reports or compiled packs depending on your retrieval strategy.

Choose **source reports** when you want report-level provenance and narrower chunks. This is best for systems that cite specific retrieved passages or route questions to particular conceptual modules.

Choose **compiled packs** when you want fewer files and strong continuity across related reports. This is usually the best default for project knowledge systems, NotebookLM-style workflows, and multi-file RAG tools with moderate file-count limits.

Choose the **omnibus** only when your stack handles large single-file corpora well. It is useful for archival search, whole-canon embeddings, local grep-style lookup, or long-context model sessions where preserving the entire sequence matters more than file granularity.

Suggested chunking policy for RAG systems:

- Preserve headings and report letters in metadata.
- Keep tables intact when possible; many tables encode the operational ontology.
- Store file path, report code, report title, volume label, and heading path with each chunk.
- Avoid chunking so aggressively that a concept is separated from its contrast class or failure mode.
- Treat source-report chunks as higher-provenance units than downstream summaries you generate from them.

## For Human Readers

Enter through the problem you are trying to solve.

If you need **basic epistemic discipline**, start with A and B.

If you need **source and platform analysis**, read C.

If you need **lead discovery or early-warning logic**, read D.

If you need **coverage-gap or omission analysis**, read E.

If you need **investigative graph expansion**, read F.

If you need **story evolution and timing logic**, read G.

If you need **actor incentives and power mapping**, read H.

If you need **propaganda or information-operation analysis**, read I.

If you need **bounded inference from incomplete evidence**, read J.

If you need **editorial triage, failure diagnosis, or workflow artifacts**, use the Vol. 4 compiled pack or the omnibus for K–M.

## For Prompt Engineers and Agent Builders

This canon is especially useful as a behavioral substrate for investigative personas, editorial copilots, OSINT assistants, misinformation analysts, and research agents.

A strong agent should use the canon to enforce these habits:

- Separate observable artifacts from claims about those artifacts.
- Track source position before source prestige.
- Demand orthogonal corroboration before raising confidence.
- Preserve weak leads without prematurely publishing them as facts.
- Treat missingness as a diagnostic question, not automatic evidence of suppression.
- Encode graph edges by type, direction, evidence, and confidence.
- Distinguish alignment from coordination.
- Ask what must also be true if a proposed explanation is true.
- Maintain explicit rival hypotheses and revision conditions.
- Kill or cool leads when maturation windows expire without corroboration.

## For Current-Events Work

This repo is not a live news source. Use it as the reasoning layer beneath fresh reporting, databases, public records, local sources, platform data, and primary documents.

When working with current events, pair the canon with live source collection and make the model cite the current sources separately. The canon should shape the questions, distinctions, and confidence logic; it should not substitute for current evidence.

## What Not To Do

Do not upload only a few isolated sections and expect the model to retain the whole epistemic posture. The doctrine works best when the model sees the surrounding contrast classes, failure modes, and workflow logic.

Do not treat the corpus as a claim database about any specific real-world event. It is a reasoning canon.

Do not let the model convert high public visibility into factual confidence. That is one of the main failure modes this canon exists to prevent.
