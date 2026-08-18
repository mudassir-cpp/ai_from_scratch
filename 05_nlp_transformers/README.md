# Month 5 — NLP & transformers (Dec 2026)

**Goal:** tokenize, fine-tune a Hugging Face model, and evaluate text like a product metric.

**You ship:** [`04_project_text_classifier`](04_project_text_classifier/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Tokenization + embeddings
* [ ] Attention / transformer block (intuition + shapes)
* [ ] Hugging Face Trainer or custom loop
* [ ] Text classifier ≥80% (or stated metric)

---

## What to learn

### Tokens — [`01_tokenization_embeddings`](01_tokenization_embeddings/README.md)

* [ ] BPE / WordPiece: why we don’t split on space only
* [ ] `input_ids`, attention mask, padding, truncation
* [ ] Embedding lookup as a table

### Transformers — [`02_attention_transformers`](02_attention_transformers/README.md)

* [ ] Q, K, V, scaled dot-product attention
* [ ] Multi-head, residual, LayerNorm
* [ ] Encoder (BERT) vs decoder (GPT) vs encoder-decoder
* [ ] Read *Attention Is All You Need* sections 3–4 (not the whole paper twice)

### Hugging Face — [`03_huggingface`](03_huggingface/README.md)

* [ ] `AutoTokenizer`, `AutoModelForSequenceClassification`
* [ ] Datasets library, `Trainer` or `accelerate`
* [ ] Push or save locally; don’t leak API keys

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_tokenization`](deep_dive/01_tokenization/README.md)
* [ ] [`02_embeddings`](deep_dive/02_embeddings/README.md)
* [ ] [`03_self_attention`](deep_dive/03_self_attention/README.md)
* [ ] [`04_transformer_block`](deep_dive/04_transformer_block/README.md)
* [ ] [`05_bert_finetune`](deep_dive/05_bert_finetune/README.md)
* [ ] [`06_hf_trainer`](deep_dive/06_hf_trainer/README.md)

---

## 1% bar

* [ ] Explain attention as “weighted sum of values”
* [ ] Fine-tune BERT-family on a classification set
* [ ] Show 10 errors that are labeling noise vs model failure

---

## Project

Text classification — [`04_project_text_classifier/README.md`](04_project_text_classifier/README.md)

## Resources

* [ ] [HF NLP course](https://huggingface.co/learn/nlp-course)
* [ ] [Transformers docs](https://huggingface.co/docs/transformers)

Open [`DAYS.md`](DAYS.md).
