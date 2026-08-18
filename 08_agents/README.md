# Month 8 — Agents (Mar 2027)

**Goal:** an LLM that *uses tools* and you can see each step when it fails.

**You ship:** [`03_project_task_agent`](03_project_task_agent/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Tools + ReAct-style loop
* [ ] Orchestration (LangChain / LlamaIndex / raw loop — pick one)
* [ ] Task agent with traces
* [ ] Project shipped

---

## What to learn

### Tools — [`01_tools_react`](01_tools_react/README.md)

* [ ] Tool schema: name, args, description
* [ ] ReAct: thought → action → observation
* [ ] Max steps, timeouts, bad JSON from the model

### Orchestration — [`02_orchestration`](02_orchestration/README.md)

* [ ] LangChain agents *or* a 80-line loop you own
* [ ] LlamaIndex when the job is “talk to my files”
* [ ] Tracing: print every tool call

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_tool_schemas`](deep_dive/01_tool_schemas/README.md)
* [ ] [`02_react_loop`](deep_dive/02_react_loop/README.md)
* [ ] [`03_memory`](deep_dive/03_memory/README.md)
* [ ] [`04_multi_tool_routing`](deep_dive/04_multi_tool_routing/README.md)
* [ ] [`05_traces_eval`](deep_dive/05_traces_eval/README.md)
* [ ] [`06_guardrails`](deep_dive/06_guardrails/README.md)

---

## 1% bar

* [ ] Calculator or search tool actually changes the answer
* [ ] 8 test tasks: pass/fail table
* [ ] One designed failure (tool down) handled

---

## Project

Task-planning agent — [`03_project_task_agent/README.md`](03_project_task_agent/README.md)

## Resources

* [ ] LangChain agents docs (current version)
* [ ] LlamaIndex tools docs

Open [`DAYS.md`](DAYS.md).
