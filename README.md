Ce projet est un travail personnel.

# Analyse des réclamations d'assurance et prédiction des coûts

## Description du projet

Ce projet explore les réclamations d'assurance pour comprendre les risques associés aux profils de clients et aux contextes de sinistres. En analysant les données des réclamations, nous visons à obtenir des **insights stratégiques** pour améliorer la gestion des risques, ajuster les politiques de couverture et anticiper les besoins des assurés. 

L'objectif est de :
1. Extraire des **insights** à partir des données de réclamations pour identifier les facteurs clés qui influencent le coût des réclamations.
2. Développer un **modèle de prédiction** des coûts des réclamations afin de fournir des estimations plus précises.

Ce projet a pour but d'informer la stratégie de gestion des sinistres et d'identifier des leviers potentiels pour une meilleure **segmentation des risques**.

## Données

Le dataset utilisé pour cette analyse provient de Suresh Gupta et contient plusieurs variables relatives aux assurés et aux réclamations. Les données comprennent des informations géographiques, démographiques et médicales.

### Variables du dataset :

- **age** : Âge de l'assuré (numérique)
- **sex** : Sexe de l'assuré (catégorique : masculin, féminin)
- **weight** : Poids de l'assuré (numérique)
- **bmi** : Indice de masse corporelle (IMC) (numérique)
- **no_of_dependents** : Nombre de personnes à charge de l'assuré (numérique)
- **smoker** : Statut de fumeur de l'assuré (catégorique : non-fumeur = 0, fumeur = 1)
- **claim** : Montant réclamé par l'assuré (numérique)
- **bloodpressure** : Pression artérielle de l'assuré (numérique)
- **diabetes** : Statut diabétique de l'assuré (catégorique : non-diabétique = 0, diabétique = 1)
- **regular_ex** : Si l'assuré fait de l'exercice régulièrement (catégorique : pas d'exercice = 0, exercice = 1)
- **job_title** : Profession de l'assuré (catégorique)
- **city** : Ville de résidence de l'assuré (catégorique)
- **hereditary_diseases** : Maladies héréditaires de l'assuré (catégorique)

### Source des données :
Les données utilisées dans ce projet proviennent de Suresh Gupta et sont disponibles sur [Kaggle](https://www.kaggle.com/datasets/sureshgupta/health-insurance-data-set/data).
