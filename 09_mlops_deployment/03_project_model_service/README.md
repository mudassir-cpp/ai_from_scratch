# Project — Model service

**REST (or gRPC) around a trained model. Docker + CI.**

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## Build

* [ ] FastAPI: `POST /predict` + `GET /health`
* [ ] Input validation (pydantic)
* [ ] Dockerfile
* [ ] pytest for the handler (mock model ok)
* [ ] GitHub Actions workflow
* [ ] README: curl examples + image build
* [ ] Optional: k8s Deployment YAML

## Success

* [ ] Fresh clone → documented steps → 200 from `/health`
* [ ] Model version in logs
