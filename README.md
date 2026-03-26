# GSOC2026-QCD-LLM test

Brief notebook project for task evaluation in **GSoC 2026 / ML4SCI (Quantum Circuit Design with LLMs)**.

## What this contains
- `submission.ipynb`: deliverable notebook.

## Notebook scope
The notebook demonstrates 3 tasks:
1. Tool-calling for a Hilbert-space calculator.
2. QNN training tool on binary MNIST.
3. Agent-guided learning-rate optimization with explicit trial memory.

## Notes
- Remote LLM access is required for agent steps.
- The notebook is configured for a 20-epoch baseline and 20-epoch Task 3 trials.
- CPU works by default; GPU is used automatically if available (based on notebook device logic).
