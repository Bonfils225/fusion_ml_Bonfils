git init
git add .
git commit -m "🚀 Fusion ML Bonfils v1"
git branch -M main
git remote add origin https://github.com/tonpseudo/fusion-ml-bonfils.git
git push -u origin main
# 🤖 Fusion ML - Bonfils Corporation™

Application Streamlit de fusion de probabilités (P_poisson + P_bookie) à l’aide d’un pipeline de machine learning avec calibration.

## 🧠 Objectif

Cette application permet de :
- Fusionner deux sources de probabilités (modèle Poisson et Bookmaker)
- Appliquer une calibration via un classifieur logistique
- Visualiser les résultats et télécharger les prédictions au format CSV
- Afficher une courbe de calibration pour évaluer la fiabilité des probabilités

## 🚀 Lancer l'application en local

```bash
pip install -r requirements.txt
streamlit run app.py
