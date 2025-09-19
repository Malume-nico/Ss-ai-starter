# SS-AI Starter

Quickstart prototype for Shooting Star AI MVP.

## What this includes
- FastAPI backend with endpoints to ingest posts and request predictions.
- Synthetic data generator and training script for a velocity model (XGBoost).
- Simple in-memory feature store and model server.
- Blueprint generator that outputs a content script + caption template.

## Goals
Spin up locally, train the prototype model on synthetic data, ingest sample posts, and call the prediction endpoint to see velocity predictions + generated blueprint.

## Quickstart (local)

1. Create a virtual environment and install requirements:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt# Ss-ai-starter