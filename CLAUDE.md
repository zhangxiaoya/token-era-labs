# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

Token Era Labs is an AI/ML learning repository focused on LLMs, transformers, and generative AI. The workflow is human-guided, AI-assisted: the user selects papers/algorithms, Claude Code helps extract key logic and generate skeleton code, and the user reviews and optimizes critical logic.

Directory structure:
- `docs/paper-notes/` - Research paper notes and summaries
- `docs/learning-log/` - Learning progress and insights
- `experiments/` - Quick experiments and prototypes (from-scratch implementations)
- `projects/` - Larger, structured AI applications and demos
- `resources/` - Datasets, models, and reference materials

## Development Environment

**Python version:** 3.10+

**Install dependencies:**
```bash
pip install -r requirements.txt
```

**Core packages:** `torch`, `transformers`, `numpy`, `pandas`

## Running Code

**Run a Python script:**
```bash
python experiments/<script_name>.py
```

**Run a Jupyter notebook:**
```bash
jupyter lab
```

## Project Conventions

**New experiment:** Create a file in `experiments/` with a descriptive name (e.g., `attention_from_scratch.py`).

**New project:** Create a subdirectory in `projects/` with its own README and structure.

**Paper notes:** Add markdown files to `docs/paper-notes/` following the existing format.

**Learning logs:** Add date-stamped entries in `docs/learning-log/`.
