# SDSC2001_Cityu

Homework for **SDSC2001 Python for Data Science** at City University of Hong Kong. The notebooks practise Python fundamentals, pandas data wrangling, and matplotlib / seaborn plots.

These are my assignment solutions, shared for reference — please do not copy them for your own submissions.

## Files

| File | What it covers |
| --- | --- |
| [`Assignment1_AYFY.ipynb`](Assignment1_AYFY.ipynb) | Python types and functions, lambdas, list comprehensions, and NumPy (reshaping, stacking, a checkerboard matrix, sampling from a normal distribution) |
| [`Assignment2_AYFY.ipynb`](Assignment2_AYFY.ipynb) | pandas: concatenating and merging DataFrames; Olympic medal counts in [`medals.csv`](medals.csv); US county/state population questions on [`census.csv`](census.csv) |
| [`Assignment3_AYFY.ipynb`](Assignment3_AYFY.ipynb) | Visualisation with seaborn (`penguins`, `attention`) and matplotlib charts from `medals.csv` (histograms, a line chart, a stacked bar chart) |
| `medals.csv` | Olympic medal counts by country (summer, winter, and combined) |
| `census.csv` | US census population estimates for states and counties, 2010–2015 |

Run Assignment 2 and 3 from the repo root so `pd.read_csv('medals.csv')` and `pd.read_csv('census.csv')` can find the CSVs.

## Requirements

- Python 3 and [Jupyter](https://jupyter.org/)
- `numpy`, `pandas`, `matplotlib`, `seaborn`

```bash
python3 -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install jupyter numpy pandas matplotlib seaborn
jupyter notebook
```

Then open the assignment you want to run.

## Licence

MIT — see [LICENSE](LICENSE).
