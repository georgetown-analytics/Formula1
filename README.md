
<span style="color:navy">
============================================================================</span>  

**Team:** *Formula1 Crash Course*   
**Project:** *Predicting Formula1 car crashes and which place car will finish* <span style="color:navy">============================================================================</span>

**Cohort 24:** *Capstone Project for the Certificate of Data Science*  
**Georgetown University:** *School of Continuing Studies*  
*Summmer 2021*  


##### **Project Organization** -- The directory organization for our project follows the following structure:  
*------------*


    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── data: data from raw to interim to processed. Includes wrangling transformations. 
    │   ├── interim        <- Intermediate data that has been transformed in some way, `[i.e. wrangling steps]`.
    │   ├── processed      <- The final data sets for modeling, `[i.e. what we deploy in our models]`.
    │   └── raw            <- The original data dump `[i.e. Kaggle, other government agencies]`.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks that wrangled and visaulized data. Naming  
    │                         convention is a number (for ordering), a short `_` delimited description, 
    │                         and steps in the pipeline process, e.g. 01_EDA__initial_wrangling.ipynb`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── source code        <- Source code for use in this project. DRAFT BELOW BASED ON LOAN CANOE PROJECT. NOT SURE IF WILL DO THIS. 
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
    
--------
