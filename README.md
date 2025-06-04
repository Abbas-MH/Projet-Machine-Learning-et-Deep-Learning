# 🧠 Portfolio de Projets de ML et Deep Learning

Ce dépôt présente trois projets réalisés dans un cadre académique ou personnel, avec pour objectifs l'analyse, la segmentation ou la prédiction à partir de données réelles.  
Ces projets mettent en œuvre différentes compétences en data science : préparation de données, réduction de dimension, modélisation, clustering, évaluation et interprétation.

---

## 🧩 Projet 1 – Segmentation de clientèle (Wholesale Customers)

🔗 **Lien vers les données :**  
[UCI – Wholesale Customers Dataset]( https://archive.ics.uci.edu/dataset/292/wholesale+customers)

### 🎯 Objectif

Ce projet vise à segmenter les clients à partir de leurs habitudes d’achat (dépenses dans divers produits : lait, Produits frais, etc.) à l’aide de méthodes de réduction de dimensions et clustering comme l'Analyse en composante principale et K-means.

### 🧩 Utilité

- Mieux comprendre les profils de clients types (restaurants, épiciers, etc).
- Cibler les actions commerciales (offres personnalisées, promotions).
- Optimiser les campagnes marketing en fonction des groupes de consommateurs détectés.

---

## 🏘️ Projet 2 – Prédiction du prix de biens immobiliers

🔗 **Lien vers les données :**  
[Challenge ENS - Prédiction de prix](https://challengedata.ens.fr/participants/challenges/68/)  
📄 **Description des variables (en cas de lien indisponible) :** Voir plus bas 👇

### 🎯 Objectif

Ce projet vise à prédire le prix d’un bien immobilier en fonction de ses caractéristiques (type de bien, surface, nombre de pièces, performances énergétiques, localisation, etc.) à l’aide de modèles supervisés (XGBoost, Regression Linéaire...).

### 🧩 Utilité

- Estimer un prix cohérent pour les acheteurs ou les agences immobilières.
- Détecter les biens potentiellement sous-évalués ou surévalués.
- Fournir un outil d’aide à la décision dans le secteur immobilier.

### 📝 Description des principales variables

| Nom                           | Description                                         |
|-------------------------------|-----------------------------------------------------|
| id_annonce                    | Identifiant unique de l’annonce                     |
| price                         | Prix affiché du bien (variable cible)               |
| property_type                 | Type de bien (maison, appartement...)               |
| city / postal_code            | Localisation du bien                                |
| size, land_size, floor        | Superficie et étage                                 |
| nb_rooms, nb_bedrooms, nb_bathrooms | Nombre de pièces, chambres, salles de bain   |
| energy_performance_value, energy_performance_category | Performance énergétique      |
| ghg_value, ghg_category       | Émissions de gaz à effet de serre                   |
| has_a_balcony, has_a_cellar, has_a_garage | Indicateurs de présence d’équipements   |
| ...et autres variables liées à la structure ou aux équipements du bien |             |

---

## 📬 Feedback

Ces projets sont encore perfectibles.  
Les suggestions, remarques ou critiques constructives sont les bienvenues pour améliorer les approches et les résultats.
