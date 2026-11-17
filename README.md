# Springboard case studies

Thirteen guided exercises from Springboard's Data Science Career Track,
completed between November 2024 and September 2025. Each folder holds one
study: its notebook, its data, and the study's original README where it had
one.

Springboard wrote the questions, the notebook structure and most of the
markdown; the code that answers them is mine. They are coursework, kept as a
record of what I learned rather than as finished analyses.

Each study was a separate repository until November 2026. Its commit history
is kept inside its folder.

## Contents

### Databases and data wrangling

| Study | What it does |
|---|---|
| [sql-country-club](sql-country-club/) | Thirteen SQL questions on a fictional country club's bookings, facilities and members: nine in MySQL, four run from Python against a SQLite copy of the database. |
| [london-house-prices](london-house-prices/) | Reshapes the UK House Price Index for London and ranks boroughs by how much their average price grew between 1998 and 2018. |
| [pyspark-adult-income](pyspark-adult-income/) | Spark SQL and DataFrame queries on the UCI Adult income data, then logistic-regression and gradient-boosted-tree classifiers with cross-validation in Spark MLlib. |

### Statistical inference

| Study | What it does |
|---|---|
| [frequentist-inference](frequentist-inference/) | Sampling distributions, the central limit theorem and z and t intervals on simulated heights; then hypothesis tests on a medical-charges dataset. |
| [app-store-ratings](app-store-ratings/) | Asks whether Apple App Store apps are rated higher than Google Play apps, with a permutation test on two Kaggle datasets. |

### Regression

| Study | What it does |
|---|---|
| [red-wine-regression](red-wine-regression/) | Linear regression on the physicochemical red-wine data (1,599 wines) with scikit-learn and statsmodels, from one predictor to ten. |
| [boston-housing-regression](boston-housing-regression/) | Ordinary least squares on the Boston housing data: nested-model F-tests, AIC, and residual and influence diagnostics. |
| [logistic-regression-heart-disease](logistic-regression-heart-disease/) | Predicts heart disease from 13 clinical measurements (270 patients) with logistic regression and a cross-validated search over regularisation strength. |

### Trees, ensembles and nearest neighbours

| Study | What it does |
|---|---|
| [random-forest-covid19](random-forest-covid19/) | A random forest that classifies the recorded outcome of South Korean COVID-19 patients from their case records. |
| [gradient-boosting-titanic](gradient-boosting-titanic/) | Builds a three-tree boosted regressor by hand, then fits a gradient-boosting classifier to Titanic survival. |
| [knn-grid-search-diabetes](knn-grid-search-diabetes/) | K-nearest neighbours and a random forest on the Pima diabetes data, with hyperparameters chosen by grid search. |

### Distance and similarity

| Study | What it does |
|---|---|
| [euclidean-manhattan-distances](euclidean-manhattan-distances/) | Compares Euclidean and Manhattan distance on a three-feature dataset. |
| [cosine-similarity](cosine-similarity/) | Cosine similarity between points, and between short texts represented as TF-IDF vectors. |

## Running a notebook

Most notebooks read their data by a path relative to their own folder, so
start Jupyter from that folder; `london-house-prices` downloads its
spreadsheet from the London Datastore. The notebooks need Python 3 with
NumPy, pandas, SciPy, Matplotlib, seaborn, scikit-learn and statsmodels, and
two use plotly or SQLAlchemy. `pyspark-adult-income` also needs PySpark and
was written for Google Colab.

## License

The code I wrote is released under the [MIT License](LICENSE). It does not
cover Springboard's exercise text or the datasets, which keep their own
terms.
