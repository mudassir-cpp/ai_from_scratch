# Project — Knowledge QA

**A chatbot over a corpus that cites sources. Retrieval quality is part of the grade.**

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## Corpus

Wikipedia dump slice, company handbook, or this repo’s month READMEs.

## Build

* [ ] Ingest + chunk + embed + index
* [ ] CLI or tiny web UI
* [ ] 15 eval questions with gold doc ids
* [ ] recall@5 (or hit rate) in `results/`
* [ ] Example Q&A log with citations
* [ ] README: how to index and how to ask

## Success

* [ ] Answers that aren’t in the corpus must refuse
* [ ] You measured retrieval, not only “it felt good”
