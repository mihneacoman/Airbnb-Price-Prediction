# Airbnb Price Prediction

## Descriere
Proiect pentru predictia preturilor Airbnb in New York folosind modele clasice de Machine Learning.  
Scopul este de a prezice preturile cazarilor pe baza caracteristicilor precum locatia, tipul camerei, numarul de recenzii etc. Au fost testate modelele: Linear Regression cu regularizare Ridge, Random Forest Regressor, XGBoost.

## Set de date
- Nume dataset: New York City Airbnb Open Data
- Sursa: [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- Contine informatii despre listarile Airbnb din NYC, inclusiv pret, locatie, numar de camere, tip de apartament si facilitati
- Numar de randuri si coloane: ~48000 randuri, 16 coloane

## Structură proiect
- `notebooks/` – Notebook principal cu analiza datelor si antrenarea modelelor
- `models/` – Modele salvate local (`.pkl`)  
- `data/` – Dataset-uri  
- `requirements.txt` – Pachete necesare pentru rularea notebook-ului  
- `.gitignore` – Fisiere ignorate de Git

## Cum se foloseste
1. Cloneaza repo-ul:
```bash
git clone https://github.com/mihneacoman/Airbnb-Price-Prediction