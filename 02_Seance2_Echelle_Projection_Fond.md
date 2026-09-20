---
title: Séance 2 - Échelle, projection et fond de carte
---

# Séance 2 - Les éléments fondamentaux d'une carte : échelle, projection et fond de carte

**Thème :** de l'espace réel à la carte — réduction, transformation et sélection de la réalité géographique

## Objectifs

- Comprendre les principaux éléments qui permettent de construire une représentation cartographique de l'espace : **l'échelle, la projection et le fond de carte**
- Comprendre qu'une carte implique nécessairement une **réduction**, une **transformation** et une **sélection** de la réalité

## 2.1 De l'espace réel à la carte

La Terre est immense et sa surface est courbe, alors qu'une carte est plane et de dimensions réduites. Trois questions se posent :

| Question | Notion |
| -------- | ------ |
| À quelle taille représenter le territoire ? | **L'échelle** |
| Comment représenter la surface courbe de la Terre sur un plan ? | **La projection** |
| Quels éléments du territoire conserver et représenter ? | **Le fond de carte et la généralisation** |

Ces choix dépendent de l'objectif de la carte : une carte de quartier, une carte de France et un planisphère ne montrent pas le même niveau de détail.

## 2.2 L'échelle : réduire la réalité pour la représenter

L'**échelle** exprime le rapport entre une distance mesurée sur la carte et la distance correspondante dans la réalité. Elle indique combien de fois la réalité a été réduite.

**L'échelle numérique** s'écrit sous forme de rapport (`1 : 100 000` ou `1 / 100 000`) : distance sur la carte : distance réelle, **exprimées dans la même unité**.

- **1 : 100 000** → 1 cm sur la carte = 100 000 cm = 1 000 m = **1 km** sur le terrain.
- **1 : 30 000 000** → 1 cm sur la carte = 30 000 000 cm = 300 000 m = **300 km** sur le terrain.

**L'échelle graphique** est une ligne graduée indiquant directement les distances réelles ; elle permet d'estimer rapidement la distance entre deux lieux.

## 2.3 Grande échelle et petite échelle

Une **grande échelle** représente un petit territoire avec beaucoup de détails ; une **petite échelle** représente un territoire plus vaste avec moins de détails.

| Échelle | Exemple | Espace représenté | Niveau de détail |
| ------- | ------- | ----------------- | ---------------- |
| **Grande** (1 / 10 000) | Plan de quartier (Paris) | Petit | Rues, bâtiments, certains équipements |
| **Moyenne** (1 / 1 000 000) | Carte d'une région (Île-de-France) | Plus vaste | Principales villes et axes de transport |
| **Petite** (1 / 10 000 000) | Carte de France | Grand | Grandes limites et principales villes |
| **Très petite** (1 / 100 000 000) | Planisphère | Très grand (monde) | Grands ensembles : continents, océans |

> **Plus l'échelle est petite, plus l'espace représenté est grand.**

Sur un plan détaillé de Paris on représente rues et bâtiments ; sur une carte de France, il serait impossible et inutile de représenter toutes les rues de Paris : l'échelle influence directement **le niveau de détail** de la carte.

## 2.4 La projection : passer de la Terre au plan

La **géodésie** définit la forme de la Terre et permet de localiser précisément chaque point (latitude, longitude, altitude) dans un système de référence. Il reste ensuite à représenter ces positions sur une surface plane : c'est la **projection cartographique**.

Comme la peau d'une orange que l'on essaie d'aplatir sur une table, la surface de la Terre ne peut pas être mise à plat sans être découpée, étirée ou déformée : **toute projection provoque des déformations**, qui peuvent concerner :

- les **surfaces** (agrandies ou réduites) ;
- les **formes** (étirées ou aplaties) ;
- les **angles** (conservés ou déformés) ;
- les **distances** (allongées ou réduites).

**Il n'existe pas de projection capable de conserver parfaitement toutes les propriétés de la surface terrestre.**

### Grandes familles de projections

| Famille | Propriété conservée | Limite |
| ------- | ------------------- | ------ |
| **Conformes** (ex. Mercator, 1569) | Les angles (localement) | Surfaces fortement déformées |
| **Équivalentes** | Les rapports de surface | Formes déformées |
| **Aphylactiques** (quelconques, de compromis) | Aucune parfaitement : compromis entre plusieurs déformations | Ni surfaces ni angles parfaitement conservés |

L'**indicatrice de Tissot** permet de visualiser ces déformations : de petits cercles tracés sur la Terre sont transformés lorsqu'ils sont représentés sur une carte plane (le cercle reste un cercle mais sa surface varie en conforme ; il s'aplatit mais sa surface reste constante en équivalente ; il devient une ellipse de taille variable en aphylactique).

> **À retenir :** l'objectif n'est pas de maîtriser toutes les projections, mais de comprendre qu'**une projection est nécessaire pour passer de la surface courbe de la Terre à une surface plane, et que cette transformation entraîne toujours des déformations.**

## 2.5 Une carte dépend aussi d'un point de vue

Nous sommes habitués aux planisphères avec le **Nord en haut** et souvent l'**Europe au centre**, mais ce n'est pas la seule représentation possible :

- **Un centrage différent** : planisphère de Mercator centré sur l'Europe ou sur le Japon (même projection, même orientation, centre différent).
- **Une orientation différente** : carte de McArthur (1979), Sud en haut. Placer le Nord en haut est une **convention cartographique**, non une obligation.

**Le centre d'une carte et son orientation sont eux aussi des choix cartographiques.** Face à une carte : *quel espace a été placé au centre ? quelle orientation a été choisie ? pourquoi ?*

## 2.6 Le fond de carte : le support de la représentation

Le **fond de carte** est le support géographique sur lequel les informations sont représentées. Selon l'objectif, il peut comporter : limites des pays, des régions ou des communes, littoral, cours d'eau, principales villes, routes, autres repères utiles. Tous ces éléments ne doivent pas apparaître sur toutes les cartes.

*Exemple : pour représenter la population des régions françaises, les limites régionales sont nécessaires ; représenter toutes les routes et tous les cours d'eau rendrait la carte trop chargée.*

Le choix du fond de carte dépend du **message que l'on souhaite transmettre**.

## 2.7 La généralisation : sélectionner et simplifier l'information

Lorsqu'on réduit un territoire, il devient impossible de conserver tous les détails. Le cartographe doit **sélectionner, simplifier ou supprimer** certains éléments : c'est la **généralisation cartographique**.

- À **grande échelle** (ex. 1 : 25 000), une côte peut être représentée avec de nombreux détails (routes, bâtiments, petits îlots).
- À **échelle moyenne** (ex. 1 : 250 000), certains détails sont simplifiés (moins de routes, certains îlots supprimés).
- À **petite échelle** (ex. 1 : 2 500 000), seuls les éléments principaux sont conservés (villes majeures, limites générales, littoral simplifié).

La généralisation ne signifie pas que la carte est incorrecte : elle permet de **rendre l'information lisible à l'échelle choisie**. Plus l'espace représenté est vaste, plus l'information est sélectionnée et simplifiée.

## 2.8 Échelle, projection et fond de carte : trois choix liés

Pour représenter la population en France, le cartographe doit décider :

1. **Quelle portion de l'espace représenter ?** France entière, une région, une commune ?
2. **À quelle échelle ?** Le niveau de détail dépend de l'espace représenté.
3. **Quel fond de carte ?** Communes, départements ou régions ?
4. **Quelle projection ?** Particulièrement importante lorsque l'espace devient vaste.
5. **Quels éléments sélectionner ?** Pour que la carte reste claire et lisible (titre, légende, couleurs, figurés...).

## À retenir

- **L'échelle** exprime le rapport entre une distance sur la carte et la distance correspondante dans la réalité.
- Une **grande échelle** représente un espace restreint avec beaucoup de détails ; une **petite échelle** un espace plus vaste avec moins de détails.
- Une **projection cartographique** permet de représenter la surface courbe de la Terre sur un plan.
- Toute projection entraîne des **déformations** : aucune ne peut tout conserver parfaitement.
- Le **fond de carte** est le support géographique de l'information.
- La **généralisation** consiste à sélectionner et simplifier les éléments pour conserver une carte lisible.
- Changer d'échelle, de projection ou de fond de carte peut modifier la manière dont un territoire est perçu.

## TD / Activité pratique - Comprendre comment l'espace devient une carte

**Exercice 1 - Lire et utiliser une échelle.** À partir d'une carte fournie, mesurer plusieurs distances à la règle et calculer les distances réelles.
*Exemple : sur une carte au 1 : 100 000, deux villes sont séparées de 4 cm. Quelle est leur distance réelle ? (1 cm = 1 km → 4 cm = 4 km.)*

**Exercice 2 - Comparer plusieurs échelles.** Pour un même territoire présenté à plusieurs échelles :

1. quelle carte représente l'espace le plus vaste ?
2. laquelle contient le plus de détails ?
3. quels éléments apparaissent ou disparaissent quand l'échelle change ?
4. pourquoi tous les éléments ne peuvent-ils pas être conservés ?

**Exercice 3 - Comparer des planisphères.** À partir de deux ou trois représentations du monde, observer :

1. la forme et la taille apparente des continents ;
2. le territoire placé au centre ;
3. l'orientation de la carte ;
4. les principales différences entre les représentations.

**Question de synthèse :** *« Pourquoi ne peut-on pas considérer une carte comme une reproduction exacte de la réalité ? »*

*Cette activité prépare la [séance 3](03_Seance3_Information_Geographique.html), consacrée à l'information géographique et aux trois questions QUOI ? OÙ ? COMMENT ?*

## Support de cours

[Support de cours (PDF)](documents/Semiologie_graphique_L1.pdf) — Séance 2 : pages 16 à 25.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance2/` puis ajouter le lien ici.)

## Correction

*À venir.*
