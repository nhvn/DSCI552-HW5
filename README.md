# DSCI 552 Homework 5 - Decision Trees and Regression

Alan Nhan's DSCI 552 Homework 5 is in the notebook `Nhan_Alan_HW5.ipynb`. It was run in full, and the outputs are saved in the file.

## Contents

- `Nhan_Alan_HW5.ipynb`: the completed notebook
- `requirements.txt`: Python dependencies
- `data/`: the datasets the notebook reads
  - `diagnosis.data`, `diagnosis.names`: Acute Inflammations dataset
  - `communities.data`, `communities.names`: Communities and Crime dataset

## Setup

You need Python 3.13. The notebook was developed with 3.13.1.

```bash
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Running the notebook

Start Jupyter from the repository root so the relative `data/` paths resolve:

```bash
jupyter notebook Nhan_Alan_HW5.ipynb
```

Then choose **Kernel → Restart & Run All**.
