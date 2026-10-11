# Machine Learning - Labs and Assignments (8MA2)

Work for the Machine Learning course (ARTI406) at Imam Abdulrahman Bin Faisal University, section 8MA2, second semester 2025-2026.

Tools: Python, pandas, NumPy, scikit-learn, Matplotlib, Jupyter.

## Contents

| Item | Folder | Topic |
|------|--------|-------|
| Assignment 2 | [lab-2](lab-2/) | Data quality assessment and preprocessing on the "Rain in Australia" dataset: date parsing, median imputation of missing values, IQR outlier capping, Min-Max and Z-score normalisation, PCA with explained-variance analysis |

The assignment notebook downloads the full dataset with `kagglehub` at runtime; a small `Sample_Weather_Data.csv` is included so the data layout can be inspected without downloading.

## Running

```bash
pip install pandas numpy scikit-learn matplotlib kagglehub jupyter
jupyter notebook
```
