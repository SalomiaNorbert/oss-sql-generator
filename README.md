# OSS SQL Generator

**Natural Language to SQL Generator (OSS Model: SQLCoder)**

AI SQL generator using open-source SQLCoder (HF Transformers, PyTorch).  
Provides a Colab notebook for interactive use and a `.py` script for local runs. This project demonstrates text → SQL conversion without paid APIs.

---

## Demo / Quick Start

**Open in Colab:**  
(Replace `YOUR-USER` below with your GitHub username)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USER/oss-sql-generator/blob/main/oss_sql_generator.ipynb)

### Requirements
- Python 3.9+ (recommended)
- NVIDIA GPU for reasonable speed (model can run in 8-bit on lower VRAM)
- Packages (install with `pip install -r requirements.txt`):
  - `torch`
  - `transformers`
  - `accelerate`
  - `bitsandbytes`
  - `sqlparse`
  - `pandas`

---

## Files in this repo
- `oss_sql_generator.ipynb` — Colab notebook (interactive demo + steps)
- `oss_sql_generator.py` — Standalone script (run locally)
- `requirements.txt` — Python dependencies
- `README.md` — This file

---

## Usage (script)
Create a virtual env and install deps:
```bash
python -m venv venv
source venv/bin/activate    # mac/linux
# venv\Scripts\activate     # windows
pip install -r requirements.txt

