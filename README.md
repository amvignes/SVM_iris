Support Vector Machine (SVM) - Iris Dataset
 
Description

Ce projet met en œuvre un Support Vector Machine (SVM) pour la classification de fleurs à partir du dataset Iris. L'algorithme SVM est utilisé ici pour démontrer son efficacité à résoudre des problèmes de classification multiclasse. Ce projet fait partie de mon parcours d'apprentissage en intelligence artificielle (IA) et en apprentissage automatique (machine learning).
Le dataset Iris contient trois classes différentes de fleurs, et chaque classe est représentée par quatre caractéristiques. Le but du modèle est de prédire la classe à partir des caractéristiques fournies. Le SVM, avec son kernel linéaire, a permis d'obtenir des résultats très satisfaisants avec une précision globale de 98%.


Objectifs

L'objectif principal de ce projet est d'appliquer mes connaissances en algorithmes de classification supervisée et d'améliorer ma compréhension des SVM en les intégrant dans un pipeline de machine learning complet. Cela inclut :
* La préparation des données (standardisation).
* La modélisation avec SVM.
* L'évaluation des performances via des métriques comme la précision, le rappel et le F1-score.

  
Étapes du projet

1. Chargement du dataset Iris : Utilisation du dataset fourni par scikit-learn.
2. Préparation des données : Division du dataset en ensembles d'entraînement et de test, suivie de la standardisation des données à l'aide de StandardScaler pour garantir que les caractéristiques soient sur la même échelle.
3. Entraînement du modèle SVM : Utilisation d'un kernel linéaire pour entraîner le modèle sur les données d'entraînement.
4. Évaluation des performances : Utilisation des métriques accuracy_score et classification_report pour analyser les résultats du modèle.


Résultats

Avec le kernel linéaire choisi, j'ai obtenu des résultats remarquables sur le dataset Iris, avec une précision globale de 98%. Voici un aperçu des résultats :
* Classe 0 (Setosa) : F1-score de 1.00
* Classe 1 (Versicolor) : F1-score de 0.96
* Classe 2 (Virginica) : F1-score de 0.96
Ces résultats montrent que le SVM est très efficace pour ce problème de classification.


Mon parcours d'apprentissage

Ce projet s'inscrit dans ma démarche d'exploration des algorithmes de machine learning, notamment en classification supervisée. Après avoir étudié des algorithmes tels que le K-Nearest Neighbors (KNN), les arbres de décision, et les réseaux de neurones convolutifs (CNN), je me suis tourné(e) vers les SVM pour élargir mon éventail de compétences.
La mise en œuvre réussie de ce projet me permet de mieux comprendre l'importance de la préparation des données, des choix de modèles et de l'évaluation des performances dans les projets de machine learning.
