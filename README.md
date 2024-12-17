# telangana_classification_challenge

The link for the challenge is:
https://zindi.africa/competitions/telangana-crop-health-challenge


**Project steps**
1. Understand our data (Exploratory Data Analysis)* 
    - Univariate Analysis
    - Bivariate Analysis
    - Outlier Detection
    - Feature Engineering
    - Handle Imbalance
2. Download the satellite images
3. Add their data to our dataset
4. Feature Importance Analysis
5. Train our first model. Get our first metric.

**Structure for the project**
data_science_project/
├── data/                    # Raw and processed data
│   ├── raw/                 # Original, unmodified data
│   ├── processed/           # Cleaned and transformed data
│   └── external/            # Data from external sources
│
├── notebooks/               # Jupyter notebooks for analysis
│   ├── exploratory_analysis.ipynb
│   └── model_building.ipynb
│
├── src/                     # Source code for data processing, modeling, etc.
│   ├── __init__.py          # Mark this folder as a package
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model.py             # Functions for building the model
│   └── utils.py             # Utility functions
│
├── models/                  # Trained models and model configurations
│   ├── model.pkl            # Serialized model
│   └── model_config.yaml    # Model hyperparameters and settings
│
├── results/                 # Visualizations, reports, and outputs
│   ├── figures/             # Graphs and plots
│   ├── performance_metrics/ # Performance evaluation metrics
│   └── model_evaluation.txt
│
├── tests/                   # Unit tests for data processing, models, etc.
│   ├── test_data_preprocessing.py
│   └── test_model.py
│
├── requirements.txt         # List of required Python packages
├── environment.yml          # Conda environment definition file
├── README.md                # Project overview and instructions
└── setup.py                 # If creating a package or library

