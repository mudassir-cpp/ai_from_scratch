# Month 11 — Cloud & scale (Jun 2027)

**Goal:** run an ML/LLM workload on one cloud with a cost number, not a screenshot of the console.

**You ship:** [`03_project_cloud_pipeline`](03_project_cloud_pipeline/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

Pick **one** provider (AWS, GCP, or Azure) and go deep. Breadth is a trap.

---

## Status

* [ ] One cloud’s ML + compute + object storage
* [ ] Cost / autoscaling notes
* [ ] Pipeline live or fully scripted
* [ ] Project shipped

---

## What to learn

### Services — [`01_cloud_ml_services`](01_cloud_ml_services/README.md)

* [ ] Object storage (S3 / GCS / Blob)
* [ ] Compute: VM, Cloud Run / Lambda, or SageMaker / Vertex endpoint
* [ ] Secrets: IAM roles, not keys in git
* [ ] Logs and one dashboard (CloudWatch / Cloud Logging)

### Cost — [`02_cost_autoscaling`](02_cost_autoscaling/README.md)

* [ ] On-demand vs spot
* [ ] Idle endpoints burn money
* [ ] Estimate: $/1k requests or $/train hour
* [ ] Autoscale idea: min 0 vs min 1

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_object_storage`](deep_dive/01_object_storage/README.md)
* [ ] [`02_compute_options`](deep_dive/02_compute_options/README.md)
* [ ] [`03_managed_endpoints`](deep_dive/03_managed_endpoints/README.md)
* [ ] [`04_iac`](deep_dive/04_iac/README.md)
* [ ] [`05_cost_autoscaling`](deep_dive/05_cost_autoscaling/README.md)

---

## 1% bar

* [ ] IaC or documented CLI that a clone can follow
* [ ] Cost table in README (even if $5)
* [ ] Tear down resources (no surprise bill)

Open [`DAYS.md`](DAYS.md).
