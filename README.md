# Memoire_ISDS
# Projet de détection des transactions frauduleuses

Ce projet vise à développer un modèle de détection des transactions frauduleuses à l'aide de la régression logistique. L'objectif est d'identifier les transactions potentiellement frauduleuses dans un ensemble de données de transactions.

## Description du projet

Ce projet propose une solution de détection des transactions frauduleuses basée sur un modèle de régression logistique. Il utilise un ensemble de données de transactions pour entraîner le modèle et évaluer sa performance. L'objectif est d'aider les entreprises à détecter les transactions suspectes et à prendre des mesures préventives pour minimiser les pertes financières.

## Structure du projet

Le projet est organisé comme suit :

- `logistic_regression.ipynb` : ce fichier contient le code principal du modèle de régression logistique.
- `train.csv` : ce fichier contient les données d'entraînement utilisées pour ajuster le modèle.
- `test.csv` : ce fichier contient les données de test utilisées pour évaluer les performances du modèle.

## Utilisation

Pour exécuter ce projet, vous devez disposer des dépendances suivantes :

- Python 3.7 ou une version ultérieure
- Les bibliothèques Python suivantes : numpy, pandas, scikit-learn



Pour utiliser le modèle de régression logistique, exécutez le fichier `logistic_regression.ipynb` :

Le code chargera les données d'entraînement à partir du fichier `train.csv` et effectuera l'ajustement du modèle de régression logistique. Il utilisera ensuite les données de test à partir du fichier `test.csv` pour évaluer les performances du modèle. Les résultats obtenus sur l'ensemble de test, y compris la précision, le rappel et la F-mesure, seront affichés à la fin de l'exécution du code.

## Comparaison avec d'autres approches

Le code fournit également une comparaison des performances du modèle de régression logistique avec d'autres approches de classification telles que la régression logistique, les k plus proches voisins, le support vector classifier et le decision tree classifier. Les résultats de chaque approche sont affichés et permettent de comparer les performances en termes de précision, de rappel et de F-mesure.

## Améliorations possibles et limites de l'étude

Bien que le modèle de régression logistique ait montré de bonnes performances dans la détection des transactions frauduleuses, il existe encore des améliorations possibles. Par exemple, l'utilisation de techniques d'échantillonnage telles que l'oversampling ou le undersampling pourrait permettre de mieux gérer les déséquilibres de classe présents dans les données. De plus, l'ajout de variables supplémentaires ou l'exploration d'autres modèles pourraient également améliorer les performances.

Il convient également de noter que cette étude présente certaines limites. Les résultats obtenus dépendent des données utilisées, il est donc important de s'assurer que les données sont représentatives et de qualité. De plus, cette étude se concentre sur un modèle de régression logistique parmi d'autres approches possibles, il est donc recommandé d'explorer d'autres modèles et techniques pour obtenir une meilleure compréhension du problème de détection de fraudes.

## Conclusion

En conclusion, ce projet présente une mise en œuvre d'un modèle de régression logistique pour la détection des transactions frauduleuses. Le modèle obtient de bonnes performances en termes de précision, de rappel et de F-mesure. Cependant, des améliorations peuvent encore être apportées et il est important de prendre en compte les limites de cette étude. Ce projet fournit une base solide pour la détection des transactions frauduleuses et peut servir de point de départ pour de futures améliorations.
