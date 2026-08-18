# Month 7 — RAG (Feb 2027)

**Goal:** answers grounded in *your* docs, with retrieval you can measure.

**You ship:** [`04_project_knowledge_qa`](04_project_knowledge_qa/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Chunking + embeddings
* [ ] Vector DB index + query
* [ ] Generate with citations
* [ ] Knowledge QA project shipped

---

## What to learn

### Chunk + embed — [`01_chunking_embeddings`](01_chunking_embeddings/README.md)

* [ ] Chunk size/overlap vs lost context
* [ ] Sentence-transformers (or API embeddings)
* [ ] Metadata: source, page, title

### Index — [`02_vector_db`](02_vector_db/README.md)

* [ ] Chroma or Qdrant locally (Pinecone optional later)
* [ ] Top-k, similarity metric (cosine)
* [ ] Hybrid search idea (keyword + vector) — know it exists

### Generate — [`03_generation_citations`](03_generation_citations/README.md)

* [ ] Stuff retrieved chunks into the prompt
* [ ] “Answer only from context; else say I don’t know”
* [ ] Cite chunk ids; hit rate on a gold question set

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_chunking`](deep_dive/01_chunking/README.md)
* [ ] [`02_embeddings`](deep_dive/02_embeddings/README.md)
* [ ] [`03_vector_search`](deep_dive/03_vector_search/README.md)
* [ ] [`04_reranking`](deep_dive/04_reranking/README.md)
* [ ] [`05_prompt_grounding`](deep_dive/05_prompt_grounding/README.md)
* [ ] [`06_rag_metrics`](deep_dive/06_rag_metrics/README.md)

---

## 1% bar

* [ ] 15 questions with labeled relevant chunks (retrieval recall@k)
* [ ] Answer faithfulness: no citation = fail
* [ ] Change chunk size once and show metric move

---

## Project

Knowledge QA — [`04_project_knowledge_qa/README.md`](04_project_knowledge_qa/README.md)

## Resources

* [ ] [sentence-transformers](https://www.sbert.net/)
* [ ] Qdrant or Chroma docs
* [ ] Lewis et al. RAG (2020) — skim the idea, then build

Open [`DAYS.md`](DAYS.md).
