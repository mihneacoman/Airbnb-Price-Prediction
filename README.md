# Airbnb Price Prediction

## Descriere
Proiect pentru predictia preturilor Airbnb în New York folosind modele clasice de Machine Learning.  
Scopul este de a prezice preturile cazarilor pe baza caracteristicilor precum locatia, tipul camerei, numarul de recenzii etc. Au fost testate modelele: Linear Regression cu regularizare Ridge, Random Forest Regressor, XGBoost.

## Set de date
- Nume dataset: New York City Airbnb Open Data
- Sursa: [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- Contine informatii despre listările Airbnb din NYC, inclusiv preț, locație, număr de camere, tip de apartament și facilități
- Număr de rânduri și coloane: ~48000 rânduri, 16 coloane

## Structură proiect
- `notebooks/` – Notebook principal cu analiza datelor și antrenarea modelelor
- `models/` – Modele salvate local (`.pkl`)  
- `data/` – Dataset-uri  
- `requirements.txt` – Pachete necesare pentru rularea notebook-ului  
- `.gitignore` – Fișiere ignorate de Git

## Cum se foloseste
1. Clonează repo-ul:
```bash
git clone <URL_repo>