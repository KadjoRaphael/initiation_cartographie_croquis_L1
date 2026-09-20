# Initiation à la cartographie et au croquis géographique — Site du cours (L1)

Site pédagogique généré avec Jekyll (thème "Read the Docs"), publié sur GitHub Pages.
Même architecture que les sites `stats_cartographie` et du cours L2.

## Publier le site

1. Créer un nouveau dépôt public sur <https://github.com/new>
   (nom suggéré : `initiation_cartographie_L1`, sans README ni .gitignore).
2. Y déposer **le contenu** de ce dossier (Add file > Upload files), ou en terminal :

```
git init
git add .
git commit -m "Premier commit du site du cours"
git branch -M main
git remote add origin https://github.com/KadjoRaphael/initiation_cartographie_L1.git
git push -u origin main
```

3. **Settings > Pages** > Source `Deploy from a branch` > Branch `main` / `(root)` > Save.
4. Adresse du site : `https://kadjoraphael.github.io/initiation_cartographie_L1/`

## Ajouter du contenu

- Une page = un fichier `.md` à la racine (le numéro en début de nom fixe l'ordre du menu).
- Fichiers à distribuer (énoncés, fonds de carte, corrigés) : les déposer dans `documents/seanceN/`
  puis ajouter le lien dans la page correspondante :
  `[Fond de carte (PDF)](documents/seance3/fond_carte.pdf)`
- Quand une séance 3 à 9 est prête : retirer l'encadré « en cours de préparation » de sa page.

## Structure

```
index.md                                   -> accueil
00_Introduction.md                         -> programme, évaluation, matériel
01_Seance1_Introduction_Cartographie.md    -> Qu'est-ce qu'une carte ?              (prête)
02_Seance2_Echelle_Projection_Fond.md      -> Échelle, projection, fond de carte    (prête)
03_Seance3_Information_Geographique.md     -> QUOI ? OÙ ? COMMENT ?                 (plan)
04_Seance4_Semiologie_Graphique.md         -> Le langage cartographique             (plan)
05_Seance5_Construire_Une_Carte.md         -> Figurés, légende, habillage           (plan)
06_Seance6_Types_Cartes_Thematiques.md     -> Choisir un type de carte              (plan)
07_Seance7_Croquis_Geographique.md         -> Du document au croquis                (plan)
08_Seance8_Lire_Critiquer_Carte.md         -> Regard critique                       (plan)
09_Seance9_Atelier_Synthese.md             -> Production cartographique complète    (plan)
10_Ressources.md                           -> Bibliographie
documents/                                 -> PDF du support de cours (+ futurs fichiers)
```
