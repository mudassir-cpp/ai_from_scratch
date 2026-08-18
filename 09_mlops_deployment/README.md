# Month 9 — MLOps & deployment (Apr 2027)

**Goal:** someone else can run your model as an API from a README and CI stays green.

**You ship:** [`03_project_model_service`](03_project_model_service/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Docker
* [ ] CI + experiment tracking
* [ ] FastAPI (or similar) model service
* [ ] Project shipped

---

## What to learn

### Containers — [`01_docker`](01_docker/README.md)

* [ ] Dockerfile, image vs container
* [ ] `.dockerignore`, non-root if you can
* [ ] Compose optional for DB + API

### CI + tracking — [`02_cicd_tracking`](02_cicd_tracking/README.md)

* [ ] GitHub Actions: lint/test/build
* [ ] MLflow or JSON logs: params, metrics, artifact path
* [ ] Pin image tags; never `:latest` in prod notes

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_fastapi`](deep_dive/01_fastapi/README.md)
* [ ] [`02_docker`](deep_dive/02_docker/README.md)
* [ ] [`03_github_actions`](deep_dive/03_github_actions/README.md)
* [ ] [`04_mlflow`](deep_dive/04_mlflow/README.md)
* [ ] [`05_kubernetes_basics`](deep_dive/05_kubernetes_basics/README.md)

---

## 1% bar

* [ ] `docker build` + `curl` the predict endpoint
* [ ] CI runs pytest on push
* [ ] One paragraph: how you would roll back a bad model

---

## Project

Model service — [`03_project_model_service/README.md`](03_project_model_service/README.md)

Reuse Month 4/5 model if you want. K8s YAML is bonus, not required to finish the month.

Open [`DAYS.md`](DAYS.md).
