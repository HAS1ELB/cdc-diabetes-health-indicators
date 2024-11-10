### Description des Caractéristiques du Dataset

| Feature                    | Type        | Description                                                                                                                       |
| ------------------------------------ | ----------- | --------------------------------------------------------------------------------------------------------------------------------- |
| `ID`                               | Identifiant | Identifiant unique pour chaque enregistrement.                                                                                    |
| `BMI`                              | Numérique  | Indice de masse corporelle, calculé à partir du poids et de la taille (utilisé pour déterminer le niveau de santé du poids). |
| `PhysHlth`                         | Numérique  | Nombre de jours (au cours des 30 derniers jours) où la santé physique n'était pas bonne.                                       |
| `Age`                              | Ordinal     | Groupe d'âge du participant (par ex., "18 to 24", "25 to 29", etc.).                                                             |
| `HighBP`                           | Binaire     | Présence d'hypertension artérielle (0 = Non, 1 = Oui).                                                                          |
| `HighChol`                         | Binaire     | Présence de cholestérol élevé (0 = Non, 1 = Oui).                                                                             |
| `CholCheck`                        | Binaire     | Test de cholestérol réalisé dans les 5 dernières années (0 = Non, 1 = Oui).                                                  |
| `Smoker`                           | Binaire     | Indique si la personne est fumeuse (0 = Non, 1 = Oui).                                                                            |
| `Stroke`                           | Binaire     | Indique si la personne a déjà eu un AVC (0 = Non, 1 = Oui).                                                                     |
| `HeartDiseaseorAttack`             | Binaire     | Antécédents de crise cardiaque ou de maladie cardiaque (0 = Non, 1 = Oui).                                                      |
| `PhysActivity`                     | Binaire     | Pratique d'une activité physique au cours du dernier mois (0 = Non, 1 = Oui).                                                    |
| `Fruits`                           | Binaire     | Consommation de fruits au moins une fois par jour (0 = Non, 1 = Oui).                                                             |
| `Veggies`                          | Binaire     | Consommation de légumes au moins une fois par jour (0 = Non, 1 = Oui).                                                           |
| `HvyAlcoholConsump`                | Binaire     | Consommation excessive d'alcool (0 = Non, 1 = Oui).                                                                               |
| `AnyHealthcare`                    | Binaire     | Accès à un système de soins de santé (0 = Non, 1 = Oui).                                                                      |
| `NoDocbcCost`                      | Binaire     | Absence de visite chez le médecin à cause du coût (0 = Non, 1 = Oui).                                                          |
| `GenHlth`                          | Ordinal     | État de santé général (ex., "Poor", "Fair", "Good", "Very Good", "Excellent"), encodé en valeurs ordinales.                  |
| `MentHlth`                         | Numérique  | Nombre de jours (au cours des 30 derniers jours) où la santé mentale n'était pas bonne.                                        |
| `DiffWalk`                         | Binaire     | Difficulté à marcher ou à monter des escaliers (0 = Non, 1 = Oui).                                                             |
| `Sex`                              | Binaire     | Sexe de la personne (0 = Femme, 1 = Homme).                                                                                       |
| `Education`                        | Ordinal     | Niveau d'éducation atteint (par ex., "Never Attended School" = 0, "Elementary" = 1, etc.).                                       |
| `Income`                           | Ordinal     | Niveau de revenu, codé de manière ordinale.                                                                                     |
| `Diabetes_binary`                  | Binaire     | Statut de diabète (0 = Non-Diabétique, 1 = Diabétique).                                                                        |

### Remarques

- Ce dataset contient des données de santé collectées pour l'analyse des conditions de santé publique.
- Les variables `BMI`, `PhysHlth`, et `MentHlth` permettent d'évaluer les aspects de santé physique et mentale.
- Les variables `HighBP`, `HighChol`, `Stroke`, et `HeartDiseaseorAttack` aident à identifier des facteurs de risque pour des conditions de santé sévères.
- Les colonnes ordinales comme `Age`, `GenHlth`, et `Education` peuvent nécessiter un encodage pour les analyses statistiques.
