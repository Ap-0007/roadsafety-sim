---
title: Road Safety Simulation AI
emoji: 🚦
colorFrom: orange
colorTo: red
sdk: docker
app_port: 8000
pinned: false
---

# Road Safety Simulation + AI Detection

Real-time simulation of 100 city buses across Delhi routes with live
YOLOv8 road-hazard detection, a multi-authority operations pipeline, and a
React + Leaflet command dashboard (live map, kanban board, analytics, and a
Groq-powered Copilot).

**Stack:** FastAPI · WebSockets · YOLOv8 (Ultralytics) · OpenCV · React · Vite · Leaflet

## Run locally

```bash
pip install -r requirements.txt
python run.py        # → http://localhost:8000
```

## Deploy


## Link to opne the running version

https://github.com/krishiv47/roadsafety-sim/edit/main/README.md


The whole app is a single Docker container (UI + API + WebSockets). It runs on
any container host with ~2 GB RAM — Hugging Face Spaces (Docker), Google Cloud
Run, or Render. See [DEPLOY.md](DEPLOY.md) for the Cloud Run recipe.
