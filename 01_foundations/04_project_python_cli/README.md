# Project — Python CLI data tool

**Ship a command-line app that a teammate can run from the README.**

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## What to build

A CLI that:

1. Reads a CSV (`data/`)
2. Prints shape, dtypes, missing counts, numeric describe
3. Writes `results/report.json` (and optionally a simple plot)

Example: expense tracker, log analyzer, or Titanic EDA — pick one and finish it.

## Deliverables

* [ ] `src/` with argparse entrypoint
* [ ] `tests/` with pytest (happy path + missing file)
* [ ] `data/` sample CSV (small, committed)
* [ ] `requirements.txt`
* [ ] This README: how to install, how to run, what the output looks like

## Success

* [ ] `python -m src.main data/sample.csv` works
* [ ] `pytest` is green
* [ ] README has copy-paste commands

## Layout

```text
04_project_python_cli/
  src/
  tests/
  data/
  results/          gitignore heavy dumps; keep one example
  README.md
  requirements.txt
```
