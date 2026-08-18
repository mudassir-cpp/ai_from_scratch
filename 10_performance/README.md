# Month 10 — Performance (May 2027)

**Goal:** same quality, less latency or smaller artifact — with a before/after table.

**You ship:** [`03_project_optimized_inference`](03_project_optimized_inference/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Profiling
* [ ] Quantization / ONNX (or distillation)
* [ ] Benchmark README
* [ ] Project shipped

---

## What to learn

### Profile — [`01_profiling`](01_profiling/README.md)

* [ ] Batch size vs latency vs throughput
* [ ] GPU vs CPU; mixed precision train *or* infer
* [ ] PyTorch profiler or `time.perf_counter` the honest way

### Compress — [`02_quantization_onnx`](02_quantization_onnx/README.md)

* [ ] Export ONNX; ONNX Runtime
* [ ] Dynamic/static INT8 if it holds accuracy
* [ ] Know TensorRT exists (run it only if you have NVIDIA + time)

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should have notes + a small runnable demo.

* [ ] [`01_latency_profiling`](deep_dive/01_latency_profiling/README.md)
* [ ] [`02_batching`](deep_dive/02_batching/README.md)
* [ ] [`03_onnx_export`](deep_dive/03_onnx_export/README.md)
* [ ] [`04_quantization`](deep_dive/04_quantization/README.md)
* [ ] [`05_serving_runtimes`](deep_dive/05_serving_runtimes/README.md)

---

## 1% bar

* [ ] p50/p95 latency table
* [ ] Accuracy delta stated
* [ ] You did not “optimize” without a baseline number

Open [`DAYS.md`](DAYS.md).
