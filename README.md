kaggle-nba-player-stats
==============================

## Dataset
[Kaggle NBA Players stats since 1950](https://www.kaggle.com/drgilermo/nba-players-stats)

## Objective
We're looking to get a feel for core problem-solving skills. The prompt is intentionally open-ended for interpretation. Based on the open nature of the prompt, this assignment could take as little as 10 minutes and on the flip side, it could merit 10's of hours. Please target to spend 2-3 hours on the assignment after loading the dataset into a notebook. To reiterate, one of the main purposes of the open prompt is to allow for creativity and interpretation - if you can defend it, there are no wrong answers. Having fun with this assignment isn't the worst thing in the world.

## Prompt
Based on the dataset, create your "best" 5 person dream team with 1 player in each of their respective positions (PG, SG, SF, PF, C). Caveat - you can only use 1 player per decade and within the past 5 decades (aka - 2010's, 2000's, 1990's, 1980's, 1970's). If a player has played at least 1 game in multiple decades, you can use them for whichever decade you prefer.

Once your rockstar team is assembled, predict the number of points they will score in the upcoming season.

## Evaluation
As mentioned and with nature of the prompt, we're looking to evaluate the assignment based on 1) the ability to produce a clean problem statement/strategy, 2) creativity of strategy, 3) quality of code, 4) ability to communicate results and insights worth exploring in the future.

## Project Organization

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
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
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
