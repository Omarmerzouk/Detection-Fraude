# Detection-Fraude
💳 Détection de Fraude par Carte Bancaire avec Machine Learning
📌 Description du projet

Ce projet vise à développer un modèle d’intelligence artificielle capable de détecter les transactions frauduleuses par carte bancaire.

Avec l’augmentation des paiements électroniques, la fraude financière représente un enjeu majeur pour les institutions bancaires. Grâce au Machine Learning, il est possible d’analyser automatiquement de grandes quantités de données et d’identifier des comportements suspects en temps réel.

📊 Dataset utilisé

Nous utilisons le dataset Credit Card Fraud Detection disponible sur Kaggle :

👉 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

🔍 Caractéristiques :
284 807 transactions
492 fraudes seulement ⚠️ (dataset très déséquilibré)
Variables V1 à V28 (issues d’une transformation PCA)
Time : temps entre transactions
Amount : montant
Class :
0 → transaction normale
1 → fraude
⚙️ Prétraitement des données

Les étapes suivantes ont été appliquées :

🔎 Analyse exploratoire des données (EDA)
📏 Normalisation (Amount, Time) avec StandardScaler
✂️ Séparation train/test avec stratification
⚖️ Gestion du déséquilibre avec SMOTE
🤖 Modèles utilisés

Plusieurs algorithmes ont été testés pour comparer les performances :

🌳 Decision Tree
🌲 Random Forest
📍 K-Nearest Neighbors (KNN)
🧠 Neural Network (MLP)
📈 Métriques d’évaluation

Étant donné le déséquilibre des classes, l’accuracy seule n’est pas pertinente.

Nous utilisons :

✔️ Precision
🔁 Recall
⚖️ F1-score
📉 AUC-ROC
