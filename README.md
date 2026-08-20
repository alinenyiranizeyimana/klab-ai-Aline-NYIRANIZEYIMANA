# Assignment 01 — Python for AI Warm-up

This repository contains my Day 1 Python for AI assignment.

## What is included

- `notebooks/day01_python_for_ai.ipynb` — the main assignment notebook
- `smooth_test.py` — a quick environment test
- `requirements.txt` — packages used in the notebook
- `reports/validation_accuracy.png` — chart created in the notebook

## Setup

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the smoke test:

```bash
python smooth.py
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/day01_python_for_ai.ipynb
```

## Environment-test expectation

If the environment is working, run:

```bash
python smooth.py
```

It should print:

```text
all good
```

## Notes

I kept the examples small on purpose so that I can explain every line of the code.
Before submitting, I restart the notebook kernel and run all cells from top to bottom.
