Project: RPA Execution Log Analysis and Failure Prediction

This project contains an end-to-end workflow for analysing Robotic Process Automation  execution logs and building a machine-learning model that predicts whether a bot run is likely to fail.
The work includes data cleaning, feature engineering, exploratory data analysis, and training a CatBoost classification model.

The project is designed as a proof-of-concept for predictive monitoring based on execution logs only.

RPA_PROJECT/
│
├── data/  
│   └── (raw or processed datasets)
│
├── exp/
│   ├── catboost_info/   # CatBoost internal training logs
│   └── data_exp.ipynb   # Main Jupyter Notebook with full analysis & model
│
├── venv/                # Virtual environment (created locally)
│
├── README.txt           # Project overview and instructions
└── requirements.txt     # Python package dependencies


Main Notebook

The entire workflow — data preparation, EDA, feature engineering, model training and evaluation — is implemented in exp/data_exp.ipynb

Create Virtual Environment:

1.Create
python -m venv venv

2.Activate
venv\Scripts\activate

3.Install dependencies
pip install -r requirements.txt

4.Add parquet file in data folder
