# Month 6 — LLMs & fine-tuning (Jan 2027)

**Goal:** ship a domain chatbot with prompting first, LoRA only if data justifies it.

**You ship:** [`03_project_domain_chatbot`](03_project_domain_chatbot/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Prompting, system prompts, structured output
* [ ] Eval set of questions (you write it)
* [ ] LoRA/QLoRA or API fine-tune on a small domain set
* [ ] Chatbot demo + before/after examples

---

## What to learn

### Applied LLM — [`01_prompting_structured_output`](01_prompting_structured_output/README.md)

* [ ] System vs user vs assistant
* [ ] Temperature, max tokens, stop sequences
* [ ] JSON / tool-shaped output; parse failures
* [ ] Hallucination: when to retrieve instead of fine-tune (tease Month 7)

### Fine-tune — [`02_lora_qlora`](02_lora_qlora/README.md)

* [ ] Why full FT is expensive
* [ ] LoRA rank, alpha, target modules
* [ ] QLoRA: 4-bit + adapters
* [ ] Instruction format (Alpaca / chat template)

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_system_prompts`](deep_dive/01_system_prompts/README.md)
* [ ] [`02_few_shot_cot`](deep_dive/02_few_shot_cot/README.md)
* [ ] [`03_structured_output`](deep_dive/03_structured_output/README.md)
* [ ] [`04_eval_rubrics`](deep_dive/04_eval_rubrics/README.md)
* [ ] [`05_lora`](deep_dive/05_lora/README.md)
* [ ] [`06_qlora_inference`](deep_dive/06_qlora_inference/README.md)

---

## 1% bar

* [ ] 20 held-out questions scored (correct / partial / wrong)
* [ ] Show prompting-only vs fine-tuned on the same sheet
* [ ] Hardware + cost note in README (even if local CPU/colab)

---

## Project

Domain Q&A chatbot — [`03_project_domain_chatbot/README.md`](03_project_domain_chatbot/README.md)

## Resources

* [ ] [PEFT LoRA](https://huggingface.co/docs/peft)
* [ ] OpenAI / Anthropic prompting docs (or local llama.cpp)

Open [`DAYS.md`](DAYS.md).
