# Data Science Template

## Directory Structure
```text
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.testrun.org
```

## Acknowledgement

After [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/#directory-structure)

## References

1. [Python](https://stackoverflow.com/questions/448271/what-is-init-py-for) [packages](https://docs.python.org/3/tutorial/modules.html#packages).
2. Building with _TBD_ (e.g. [Bazel](https://bazel.build), [Makefile](https://www.google.com/search?q=python+Makefile&oq=python+Makefile&aqs=chrome..69i57j69i61j69i60j69i65l2j69i60.3508j0j7&sourceid=chrome&ie=UTF-8)).
3. Testing with [tox](https://tox.readthedocs.io/en/latest/).
4. Documentation with [Sphinx](http://sphinx-doc.org).
