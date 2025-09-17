# NebulaWrap

A minimal, practical LLM wrapper SDK: pluggable adapters, provenance (GoldenDAG), safety hooks, memory, streaming, and a prompt test harness.

## Quickstart

1. Create a virtualenv and install:
```bash
python -m venv .venv && . .venv/bin/activate
pip install -e .
pip install openai  # if you will use OpenAIAdapter
