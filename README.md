### Hi, I'm Kartike

**Applied AI engineer. I build retrieval systems that cite their sources.**

Four and a half years turning document corpora into systems people can actually ask questions of:
parsing, evidence blocks, hybrid retrieval, and answers that point back to the exact passage they
came from.

**Now** — Data Scientist II at SUCH AI Technologies (Shapoorji Pallonji group), building a
multi-tenant knowledge service that ingests 16 document families and answers at 93-95% accuracy over
a graded evaluation set of 10,000 queries.

---

#### How I think about retrieval

- **One route is always wrong somewhere.** I run dense, sparse, exact-identifier, entity, structural
  and metadata routes, then fuse them by weighted reciprocal rank.
- **An answer without provenance is a guess.** Every answer binds to a box-level citation over an
  immutable evidence block, so a reader can verify it rather than trust it.
- **Generation is the cheap part.** Answers are gated through NLI entailment and an LLM judge, then
  repaired and re-validated before anything ships.
- **A model you haven't measured is a rumour.** I benchmark providers and score answers against a
  graded rubric, not by eye.

#### Tools I reach for

`Python` · `RAG` · `hybrid retrieval (dense + BM25 + RRF)` · `reranking` · `NLI validation`
`LoRA / PEFT` · `FastAPI` · `PostgreSQL` · `Neo4j` · `Qdrant` · `Docker` · `AWS`

---

**Elsewhere:** [LinkedIn](https://www.linkedin.com/in/kartike-kumar/)
