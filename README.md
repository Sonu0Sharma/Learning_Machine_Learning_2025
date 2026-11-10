# Learning Machine Learning (2025)

A structured collection of Jupyter notebooks documenting my hands-on practice across core Python data science libraries, exploratory data analysis, and end-to-end feature engineering pipelines.

<p align="center">
  <img src="https://img.shields.io/badge/status-learning-yellow" alt="Status" />
  <img src="https://img.shields.io/badge/Python-3.11%20%7C%203.12-blue" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626" alt="Jupyter Notebook" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458" alt="Pandas" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Preprocessing-F7931E" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License" />
</p>

| [💻 GitHub Repository](https://github.com/Sonu0Sharma/Learning_Machine_Learning_2025) |
|---|

> **Context:** This repository documents my hands-on exploration of classical machine learning workflows and data science fundamentals. The focus is on building familiarity through practice — the code here reflects a continuous learning process, not a finished product.

## What This Covers

- **Array Programming with NumPy**: Multi-dimensional array creation, vectorization versus native Python list operations, slicing, fancy indexing, array reshaping, and broadcasting mechanisms.
- **Data Wrangling with Pandas**: Series and DataFrame indexing, conditional row filtering, `groupby` aggregations, multi-level pivot tables, merge operations, and handling duplicates across real-world datasets (Titanic, IPL matches, Fortune 500).
- **Statistical Data Visualization**: Univariate and bivariate plotting using Matplotlib and Seaborn, including correlation heatmaps, kernel density estimates (`distplot`), pairplots, multi-graph subplots, and bar charts.
- **Data Ingestion Workflows**: Ingesting structured and semi-structured data from local CSVs, JSON structures, relational databases via SQL queries, public REST APIs, and basic web scraping techniques.
- **Feature Transformation & Scaling**: Normal distribution diagnostics, standardization (`StandardScaler`), min-max normalization (`MinMaxScaler`), log transformations, and power transformations (Box-Cox and Yeo-Johnson).
- **Categorical & Mixed Data Encoding**: Nominal encoding with `OneHotEncoder`, ordinal feature mapping, handling mixed data types, high-cardinality values, and date-time feature decomposition.
- **Missing Value & Outlier Treatment**: Univariate and multivariate imputation strategies (`SimpleImputer`, `MissingIndicator`, `KNNImputer`, `IterativeImputer`) alongside outlier detection using Z-Score thresholds, IQR boxplot filtering, and Winsorization.
- **Reproducible ML Pipelines**: Assembling end-to-end preprocessing pipelines using Scikit-Learn's `ColumnTransformer` and `Pipeline` abstractions to prevent data leakage during modeling.

## Repository Structure

```
.
├── 100_days_of_ML/       # Daily exercises: feature engineering & Scikit-Learn pipelines
├── learn_Numpy/          # NumPy array manipulation, indexing, and vectorization
├── learn_Pandas/         # Pandas data structures, aggregation, and EDA notebooks
├── learn_Matplotlib/     # 2D data plotting, multi-axis subplots, and figures
├── learn_seaborn/        # Statistical charts, pairplots, and distribution analysis
├── project/              # End-to-end guided practice ML workflow
├── .gitignore            # Git ignore rules for environments and checkpoints
├── LICENSE               # MIT License
└── README.md             # Practice log and repository guide
```

## Technologies

- **Core Language**: Python 3.11 / 3.12
- **Data Manipulation**: NumPy, Pandas
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning & Preprocessing**: Scikit-Learn
- **Environment**: Jupyter Notebook / JupyterLab

## Getting Started

### Prerequisites
- Python 3.10+ (tested on Python 3.11 and 3.12)
- pip and virtualenv

### Setup Instructions

```bash
# Clone the repository
git clone https://github.com/Sonu0Sharma/Learning_Machine_Learning_2025.git
cd Learning_Machine_Learning_2025

# Set up and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies and start Jupyter
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Navigate to any topic folder (e.g., `100_days_of_ML/` or `learn_Pandas/`) in the Jupyter dashboard to run and experiment with the notebooks.

## Reflections

Working through these notebooks gave me a clear, practical understanding of why data preprocessing and feature engineering take up most of an applied machine learning project. Writing manual transformations before using Scikit-Learn's `ColumnTransformer` highlighted how easily data leakage can occur if scaling or imputation parameters are computed on the entire dataset instead of training splits alone. Navigating NumPy's broadcasting rules and handling mixed data types were initially challenging, but building repeatable pipelines reinforced solid habits. Next, I plan to explore classical supervised algorithms (linear models, tree-based ensembles) and systematic cross-validation.

## License

This repository is licensed under the [MIT License](./LICENSE).
