**Team:** *Formula1 Crash Course*   
**Project:** *Drive to Survive: Predicting Formula 1 Vehicle Failure*

**Cohort 24:** *Capstone Project for the Certificate of Data Science*  
**Georgetown University:** *School of Continuing Studies*  
*Summmer 2021*  

**Abstract:** Our team built several classification models, of which Bagging Classifier was
the best, to predict whether a car in Formula 1 would finish the race or not. We gathered
a range of data on race results from 1996 to the present day, including features such as
car speed, weather, and track features. Our data underwent a variety of transformations and
wrangling until we were able to implement the most optimized versions into our models, which
we measured with ROC curves and confusion matrices. Our analysis identified patterns in
vehicle failure and uses these to make predictions.

**Project Organization:** The directory organization for our project follows the structure listed below:


    ├── .ipynb_checkpoints <- Assorted checkpoints of various workbooks.
    │
    ├── Data Visualization <- Jupyter notebooks that visualized our data.
    │
    ├── Data Wrangling     <- Jupyter notebooks that wrangled data.
    │
    ├── Evaluation         <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── Exploratory Data   <- Includes workbooks of all our EDA files.
    │       Analysis         
    │ 
    ├── Interactive Widget <- This contains all work done to produce an interactive widget.           
    │                         Note that the final product is in
    │                         'FinalInteractiveWidget_FrontEnd_BaggingClassifier.ipynb'.
    │
    ├── data: Data from raw to interim to processed. Includes wrangling transformations. 
    │   ├── interim        <- Intermediate data that has been transformed in some way,
    │                         i.e. wrangling steps.
    │   ├── processed      <- The final data sets for modeling, i.e. what we deploy in our models.
    │   └── raw            <- The original data dump, i.e. Kaggle, other government agencies.
    │
    ├── Reports            <- This contains our written paper with compiled analysis, as well
    │                         as our presentation.
    │
    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`.
    

    
--------
