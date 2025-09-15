                    Impact du sommeil sur la cognition et la santé
Description du projet

Ce projet explore les relations entre sommeil, stress et performance cognitive à partir d’un dataset fictif/expérimental sur le sommeil.
Objectifs :

Explorer les liens entre qualité du sommeil, stress, vigilance et régulation émotionnelle.

Construire des visualisations claires pour comprendre ces relations.

Mettre en place des modèles de Machine Learning pour prédire la qualité du sommeil.

                Données

Le dataset contient les colonnes suivantes :

Participant_ID : identifiant du participant

Sleep_Hours : nombre d’heures de sommeil

Sleep_Quality_Score : qualité du sommeil (1–5)

Daytime_Sleepiness : niveau de somnolence diurne

Stroop_Task_Reaction_Time : performance attentionnelle (ms)

N_Back_Accuracy : précision mémoire de travail (%)

Emotion_Regulation_Score : score de régulation émotionnelle

PVT_Reaction_Time : vigilance (ms)

Age, Gender, BMI

Caffeine_Intake, Physical_Activity_Level, Stress_Level

            Analyse exploratoire

Quelques visualisations réalisées :

Boxplot : Qualité du sommeil vs Somnolence diurne

Heatmap de corrélation : Sommeil , Stress , Régulation émotionnelle

Histogrammes : distribution des heures de sommeil

Scatterplots : relations sommeil , performances cognitives

            Machine Learning

Deux modèles ont été comparés pour prédire la qualité du sommeil (binaire : bonne vs mauvaise) :

Logistic Regression

Random Forest Classifier

Évaluation :

Rapport de classification (Accuracy, Precision, Recall, F1-score)

Matrice de confusion

Courbes ROC pour comparer les modèles

Importance des variables (Random Forest)

            Résultats :

Le Random Forest a obtenu un meilleur score global que la Logistic Regression.

Les variables les plus importantes pour prédire la qualité du sommeil sont :

Stress_Level

Sleep_Hours

BMI

            Libraires utilisées

Python : Pandas, Numpy 

Visualisation : Matplotlib, Seaborn

Machine Learning : Scikit-learn
