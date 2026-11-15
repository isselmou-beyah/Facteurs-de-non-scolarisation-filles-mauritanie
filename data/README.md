# Données

Les micro-données utilisées ne sont **pas publiées** dans ce dépôt : elles sont confidentielles et appartiennent à l'ANSADE (Agence Nationale de la Statistique et de l'Analyse Démographique et Économique, Mauritanie).

## Sources

| Fichier attendu | Description | Où l'obtenir |
|---|---|---|
| `Fusion_3.csv` | Base EPCV 2019–2020 (individus et ménages fusionnés) | Sur demande auprès de l'ANSADE |
| `gadm41_MRT_shp/gadm41_MRT_1.shp` | Limites administratives des wilayas | [GADM 4.1](https://gadm.org/download_country.html), Mauritanie, niveau 1 |

## Principales variables utilisées

| Variable | Signification |
|---|---|
| `B2` | Sexe |
| `B4` | Âge |
| `B5`, `nivcm` | Statut matrimonial |
| `scole`, `scole_cat` | Statut scolaire (1 = non scolarisée, 0 = scolarisée) |
| `C2`, `C5` | Types d'enseignement fréquentés |
| `raison_non_freq` | Raison de non-fréquentation scolaire |
| `milieu`, `wilaya` | Milieu et wilaya de résidence |
| `Pr`, `quintile`, `decile1` | Pauvreté, quintile et décile de bien-être du ménage |
| `gse1` | Groupe socio-économique du chef de ménage |
| `age_cat`, `tranche_age` | Tranches d'âge |
| `ipond` | Poids de sondage |

Les fichiers de données placés dans ce dossier sont ignorés par Git (voir `.gitignore`), pour éviter de les publier par erreur.
