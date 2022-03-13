# Projet de Systèmes Répartis : Classification du risque de crédit pour les ménages allemands


## Données

L'ensemble de données utilisé dans ce projet est inclus sous le nom de `german_credit_data.csv`. Ce jeu de données est fourni par le Professeur Dr. Hans Hofmann de l'Institut de Statistique et d'Économétrie de l'Université d'Hambourg. Originellement composée de `20 variables` et `1000 observations`, le dataset utilisé pour notre analyse est une version allégée disponible sur Kaggle (https://www.kaggle.com/kabure/german-credit-data-with-risk) avec `10 attributs`, ceux non-retenus n'étant pas si importants ou leurs descriptions obscures.

La base finale conservée contient les variables suivantes :

- `Age` (variable numérique continue, Âge)
- `Sex` (variable textuelle catégorielle, Sexe : male, female)
- `Job` (variable numérique catégorielle, catégorie socio-professionnelle: 0 - non qualifié ou étranger, 1 - non qualifié et résident, 2 - qualifié, 3 - hautement qualifié)
- `Housing` (variable textuelle catégorielle, Statut d'occupation du logement: own, rent, or free)
- `Saving accounts` (variable textuelle catégorielle, Montant disponible dans le compte d'épargne : - little, moderate, quite rich, rich)
- `Checking account` (variable numérique continue, Montant disponible dans le compte courant - en Deutsch Mark)
- `Credit amount` (variable numérique continue, Montant du crédit - en Deutsche Mark)
- `Duration` (variable numérique continue, Durée du crédit en mois)
- `Purpose` (variable textuelle catégorielle avec pour modalités: car, radio/TV, furniture/equipment, business, education)
- `Risk` (variable textuelle catégorielle, C'est la variable cible, elle correspond au statut du crédit : good, bad)
