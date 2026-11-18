# TP 5 : Importer, ranger et nettoyer des données

Introduction au langage R · Cnam · USSI6B-1

## Démarrer

1. Décompressez l'archive `tp5.zip`, puis ouvrez le projet en double-cliquant sur `tp5.Rproj`.
2. L'énoncé est en PDF sur Moodle.
3. Créez votre document R Markdown **`tp5_nom_prenom.Rmd`** (format HTML) **à la racine du dossier**, pour que les chemins `data/…` fonctionnent.
4. Son premier chunk charge les packages :

   ````
   ```{r setup, include = FALSE}
   library(tidyverse)
   library(readxl)
   ```
   ````

5. Structure : `# Partie A`, puis `## A1`, `## A2`… comme dans l'énoncé.

## Contenu du dossier

Le dossier `data/` contient tous les fichiers du TP. **Ne les modifiez pas** : les corrections se font dans votre code. L'import fait partie du TP : il n'y a pas de fichier `donnees_tp5.R`.

## Rendu

- Déposez sur Moodle **deux fichiers** : votre `.Rmd` et le `.html` knitté sans erreur.
- Seul ce qui est déposé à la date limite (voir Moodle) est pris en compte.
