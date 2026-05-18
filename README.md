# kenya_lulc

A project to fine-tune GFM for land cover and crop mapping in Kenya

## Setup

Install with [uv](https://docs.astral.sh/uv/):

```bash
uv sync
```

Or install in editable mode:

```bash
pip install -e ".[dev]"
```

## Project structure

```
kenya_lulc/
├── pyproject.toml
├── src/
│   └── kenya_lulc/
│       ├── __init__.py
│       └── definitions.py      # ROOT_DIR, DATA_PATH, OUTPUT_PATH
├── data/                       # Input data (git-ignored)
├── notebooks/                  # Jupyter notebooks
├── output/                     # Results (git-ignored)
└── tests/
```

## Usage

```python
from kenya_lulc import DATA_PATH, OUTPUT_PATH
```
