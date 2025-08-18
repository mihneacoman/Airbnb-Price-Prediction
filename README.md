# Airbnb Price Prediction

## Description
This project aims to predict Airbnb prices in New York City using classical Machine Learning models.  
The goal is to estimate accommodation prices based on features such as location, room type, number of reviews, etc. The following models were tested: Ridge-regularized Linear Regression, Random Forest Regressor, and XGBoost.

## Dataset
- Dataset name: New York City Airbnb Open Data
- Source: [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- Contains information about NYC Airbnb listings, including price, location, number of rooms, apartment type, and amenities
- Number of rows and columns: ~48,000 rows, 16 columns

## Project Structure
- `notebooks/` – Main notebook with data analysis and model training
- `models/` – Saved models (`.pkl`)  
- `data/` – Datasets  
- `requirements.txt` – Required packages to run the notebook  
- `.gitignore` – Files ignored by Git

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/mihneacoman/Airbnb-Price-Prediction.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Open the notebook in `notebooks/` and run the cells.