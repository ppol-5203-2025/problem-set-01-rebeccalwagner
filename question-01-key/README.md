# Repository Overview: `question-01-key`

This repository is organized to support data analysis and figure generation for **Question 01**. 

---

```
question-01-key/
├── code/
│   ├── additional_analysis.py
│   ├── appendix.py
│   ├── data_processing.py
│   └── main.py
│
├── data/
│   ├── clean_data.csv
│   └── raw_data.csv
│
└── figures/
    ├── fig_1.png
    ├── fig_1a_hetro.png
    ├── fig_2.png
    ├── fig_2a_polar.png
    ├── fig_3.png
    ├── fig_3a_robust.png
    ├── fig_4.png
    └── fig_5.png
```

---

## Folder Descriptions

### `code/`
Contains Python scripts for processing data and generating figures.

- **`main.py`** – Primary analysis pipeline.  
- **`data_processing.py`** – Cleans and prepares raw data.  
- **`additional_analysis.py`** – Runs supplementary or robustness analyses.  
- **`appendix.py`** – Produces additional figures or appendix results.

### `data/`
Holds input datasets.

- **`raw_data.csv`** – Original dataset (unprocessed).  
- **`clean_data.csv`** – Cleaned version created by the data processing script.

### `figures/`
Stores all generated plots and figures.

- **`fig_1.png` – `fig_5.png`** – Main analysis figures.  
- **`fig_1a_hetro.png`, `fig_2a_polar.png`, `fig_3a_robust.png`** – Supplementary robustness or sensitivity figures.

---
