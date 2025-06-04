# Mémoire : Modélisation de la fréquence des sinistres en assurance automobile

Ce dépôt contient le code Python associé à mon mémoire de fin d'études.  
L’objectif est de comparer les approches traditionnelles (GLM) aux techniques de Machine Learning (Random Forest, XGBoost, CatBoost) pour la tarification en assurance auto.

## Contenu du dépôt

- `modele_GLM.ipynb` : Modélisation avec un modèle Poisson (GLM)
- `modele_RF_XGB_CatBoost.ipynb` : Implémentation des modèles Random Forest, XGBoost et CatBoost
- `validation_croisee_et_courbes.ipynb` : Analyse de la stabilité (validation croisée, courbes d’apprentissage)
- `analyse_SHAP_XGBoost.ipynb` : Analyse d’explicabilité avec SHAP (XGBoost)

## Données utilisées

Les données proviennent de la base **freMTPL2freq** disponible sur OpenML :  
https://www.openml.org/d/42214

## Objectif

Évaluer la performance prédictive et la capacité explicative de plusieurs modèles de prédiction de la fréquence des sinistres.  

## Licence

Ce code est partagé à titre académique. Merci de ne pas réutiliser sans mention.

---

###  Ce dépôt est lié à mon mémoire disponible sur demande.

