# Entrai-nement-du-classificateur

Description du projet:
Ce projet vise à classer les pays en groupes homogènes basés sur divers indicateurs socio-économiques et de santé en utilisant des techniques de clustering non supervisé et de classification supervisée. Le but est d'identifier des modèles dans les données qui peuvent aider à comprendre les différences et les similitudes entre les pays, ce qui pourrait être utile pour les études de développement international et les politiques publiques.

Description des méthodes d'analyse et des résultats:
Regroupement :
Prétraitement des données : Normalisation des variables pour garantir une comparaison équitable lors du clustering.
Réduction de dimensionnalité : Utilisation de l'ACP (Analyse en Composantes Principales) pour réduire le nombre de dimensions tout en conservant l'essentiel de l'information.
Méthode de clustering : Utilisation de l'algorithme K-means pour regrouper les pays. Le nombre optimal de clusters a été déterminé en utilisant la méthode du coude et l'analyse silhouette.
Classification:
Modèles utilisés : SVM (Support Vector Machine) et Random Forest. Ces modèles ont été choisis pour leur efficacité reconnue en classification.
Optimisation des hyperparamètres : Utilisation d'Optuna pour l'optimisation des hyperparamètres afin de maximiser la précision des prédictions.
Évaluation des modèles : Les modèles ont été évalués en fonction de leur précision, rappel, et score F1 sur un ensemble de données de test.
Résultats:
Clusters : Les pays ont été divisés en X clusters distincts, reflétant des niveaux de développement et de santé variables.
Classification : Le modèle Random Forest a surpassé le modèle SVM avec une précision de X%, indiquant une forte capacité à généraliser les résultats du clustering.
