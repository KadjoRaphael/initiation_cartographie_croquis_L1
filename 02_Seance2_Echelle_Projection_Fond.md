---
title: Séance 2 - Échelle, projection et fond de carte
nav_order: 4
---

# Séance 2 - Les éléments fondamentaux d'une carte : échelle, projection et fond de carte

Cette deuxième séance est consacrée aux principaux éléments qui permettent de
passer de **l'espace réel à sa représentation sur une carte**.

Nous étudierons trois notions fondamentales : **l'échelle**, la **projection
cartographique** et le **fond de carte**.

L'objectif est également de comprendre qu'une carte implique nécessairement
une **réduction**, une **transformation** et une **sélection** de la réalité
géographique.

> **Fil conducteur de la séance :** comment passe-t-on de l'espace réel à sa
> représentation sur une carte ?

---

## 🎯 Objectifs de la séance

À la fin de cette séance, vous devrez être capable de :

- comprendre ce qu'est l'**échelle** d'une carte ;
- lire une échelle numérique et une échelle graphique ;
- calculer une distance réelle à partir d'une distance mesurée sur une carte ;
- distinguer **grande échelle** et **petite échelle** ;
- comprendre la relation entre l'échelle et le niveau de détail ;
- comprendre pourquoi une **projection cartographique** est nécessaire ;
- comprendre que toute projection entraîne des **déformations** ;
- comprendre que le centrage et l'orientation d'une carte sont des choix ;
- comprendre le rôle du **fond de carte** ;
- comprendre le principe de **généralisation cartographique**.

---

# 1. De l'espace réel à la carte

Lorsqu'on réalise une carte, il est impossible de représenter un territoire
exactement comme il existe dans la réalité.

La Terre est immense et sa surface est **courbe**, alors qu'une carte est
généralement représentée sur une surface **plane** et de dimensions réduites.

Il faut donc effectuer plusieurs transformations pour passer du territoire
réel à sa représentation cartographique.

Trois questions sont particulièrement importantes :

1. **À quelle taille représenter le territoire ?**  
   → C'est la question de l'**échelle**.

2. **Comment représenter la surface courbe de la Terre sur un plan ?**  
   → C'est la question de la **projection cartographique**.

3. **Quels éléments du territoire conserver et représenter ?**  
   → C'est la question du **fond de carte** et de la **généralisation**.

Ces choix dépendent de l'objectif de la carte.

Une carte de quartier, une carte de France et un planisphère ne peuvent pas
représenter le même niveau de détail.

---

# 2. L'échelle : réduire la réalité pour la représenter

L'**échelle** exprime le rapport entre une distance mesurée sur la carte et
la distance correspondante dans la réalité.

Elle indique donc combien de fois la réalité a été **réduite** pour pouvoir
être représentée sur la carte.

On rencontre principalement deux formes d'échelle :

- l'**échelle numérique** ;
- l'**échelle graphique**.

---

## 2.1. L'échelle numérique

L'échelle numérique s'écrit sous la forme d'un rapport.

Par exemple :

**1 : 100 000**

Cela signifie que :

**1 cm sur la carte = 100 000 cm dans la réalité**

Il faut ensuite convertir cette distance :

**100 000 cm = 1 000 m = 1 km**

Donc :

> **À l'échelle 1 : 100 000, 1 cm sur la carte représente 1 km sur le terrain.**

### Exemple

Deux villes sont séparées de **4 cm** sur une carte au **1 : 100 000**.

Nous savons que :

**1 cm = 1 km**

Donc :

**4 cm = 4 km**

La distance réelle entre les deux villes est donc de **4 km**.

---

## 2.2. L'échelle graphique

L'**échelle graphique** est représentée par une ligne graduée indiquant
directement les distances réelles.

Elle permet d'estimer rapidement la distance entre deux lieux sur une carte.

Par exemple, une barre graduée peut indiquer :

**0 ─── 10 ─── 20 ─── 30 km**

On peut alors comparer directement une distance mesurée sur la carte avec
cette échelle.

---

## 2.3. Un deuxième exemple de calcul

Prenons une carte à l'échelle :

**1 : 30 000 000**

Cela signifie que :

**1 cm sur la carte = 30 000 000 cm dans la réalité**

Or :

**30 000 000 cm = 300 000 m = 300 km**

Donc :

> **À l'échelle 1 : 30 000 000, 1 cm sur la carte représente 300 km dans la réalité.**

---

# 3. Grande échelle et petite échelle

Le vocabulaire cartographique peut sembler surprenant au début.

En cartographie :

> **Une grande échelle représente généralement un petit territoire avec
> beaucoup de détails.**

À l'inverse :

> **Une petite échelle représente un territoire plus vaste avec moins de détails.**

Par exemple :

| Type de carte | Échelle | Espace représenté | Niveau de détail |
| --- | --- | --- | --- |
| Plan d'un quartier | Grande échelle | Petit | Très détaillé |
| Carte d'une région | Échelle moyenne | vaste | Détails intermédiaires |
| Carte de France | Petite échelle | Plus Vaste | Peu détaillé |
| Planisphère | Très petite échelle | Monde entier | Très peu détaillé |

Il faut donc retenir une relation essentielle :

> **Plus l'échelle est petite, plus l'espace représenté est grand et moins
> la carte contient de détails.**

### Exemple

Sur un plan détaillé de Paris, il est possible de représenter :

- les rues ;
- les bâtiments ;
- certains équipements ;
- différents lieux particuliers.

Sur une carte de France, il serait impossible et inutile de représenter
toutes les rues et tous les bâtiments de Paris.

Il faut donc **sélectionner les informations les plus importantes**.

L'échelle influence ainsi directement le **niveau de détail de la carte**.

---

# 4. La projection : passer de la Terre au plan

La Terre possède une surface **courbe**, alors que la carte est généralement
**plane**.

Pour représenter la Terre, il faut d'abord pouvoir localiser précisément
les différents points à sa surface.

La **géodésie** permet notamment de définir des coordonnées géographiques
comme :

- la latitude ;
- la longitude ;
- l'altitude.

Une fois ces positions définies, il reste à les représenter sur une surface
plane : une feuille, un écran ou tout autre support cartographique.

Cette transformation est appelée **projection cartographique**.

> **Une projection cartographique permet de transformer la surface courbe
> de la Terre afin de la représenter sur une surface plane.**

Une question apparaît alors :

**Peut-on représenter une surface courbe sur un plan sans la déformer ?**

La réponse est **non**.

---

## 4.1. Pourquoi les projections provoquent-elles des déformations ?

On peut comparer le problème à une **orange**.

Imaginez que vous essayiez de retirer la peau d'une orange et de la poser
complètement à plat sur une table.

Il est impossible de le faire sans :

- la découper ;
- l'étirer ;
- la déformer.

Il en va de même pour la surface de la Terre.

> **Toute projection cartographique provoque donc des déformations.**

Ces déformations peuvent concerner notamment :

- les **surfaces** ;
- les **formes** ;
- les **angles** ;
- les **distances**.

Il n'existe donc pas de projection capable de conserver parfaitement
toutes les propriétés de la surface terrestre.

---

## 4.2. Quelques grandes familles de projections

Il existe de nombreuses projections cartographiques.

Elles ne cherchent pas toutes à conserver les mêmes propriétés.

### Les projections conformes

Les **projections conformes** cherchent principalement à conserver
les **angles localement**.

En revanche, les surfaces peuvent être fortement déformées.

La projection de **Mercator**, mise au point en 1569, constitue un exemple
connu de projection conforme.

### Les projections équivalentes

Les **projections équivalentes** cherchent à conserver les **rapports
de surface**.

Elles sont donc particulièrement intéressantes lorsqu'on souhaite comparer
la superficie des territoires.

En revanche, les formes peuvent être déformées.

### Les projections de compromis

Certaines projections cherchent plutôt à trouver un **compromis entre
plusieurs types de déformations**.

Elles ne conservent alors parfaitement ni les surfaces ni les angles,
mais cherchent à limiter les déformations générales.

> **À ce stade, l'objectif n'est pas de connaître ou de mémoriser toutes
> les projections cartographiques.**
>
> Il faut surtout comprendre qu'une projection est nécessaire pour passer
> de la surface courbe de la Terre à une surface plane et que cette
> transformation entraîne toujours des **déformations**.

---

# 5. Une carte dépend aussi d'un point de vue

La manière de représenter le monde dépend également du **centrage** et de
l'**orientation** de la carte.

Nous sommes habitués à observer des planisphères avec :

- le **Nord en haut** ;
- l'**Europe** souvent placée dans une position centrale.

Mais cette représentation n'est pas la seule possible.

Un planisphère peut, par exemple, être centré :

- sur l'Europe ;
- sur le Japon ;
- sur l'océan Pacifique ;
- sur un autre espace.

L'orientation peut également être différente.

La **carte de McArthur**, publiée en 1979, propose par exemple une
représentation du monde avec le **Sud en haut**.

Ces différentes représentations permettent de comprendre une idée importante :

> **Le centre d'une carte et son orientation sont eux aussi des choix
> cartographiques.**

Face à une carte, on peut donc se demander :

- **Quel espace a été placé au centre ?**
- **Quelle orientation a été choisie ?**
- **Pourquoi ?**

Il n'existe pas une seule manière de représenter le monde.

---

# 6. Le fond de carte : le support de la représentation

Le **fond de carte** est le support géographique sur lequel les informations
vont être représentées.

Selon l'objectif de la carte, il peut comporter différents éléments :

- les limites des pays ;
- les limites des régions ;
- les limites des départements ou des communes ;
- le littoral ;
- les cours d'eau ;
- les principales villes ;
- les routes ;
- d'autres repères géographiques utiles.

Tous ces éléments ne doivent pas nécessairement apparaître sur toutes
les cartes.

### Exemple

Imaginons que l'on souhaite représenter la **population des régions
françaises**.

Les limites régionales sont nécessaires pour identifier les territoires.

En revanche, représenter toutes les routes, tous les cours d'eau et toutes
les villes rendrait probablement la carte trop chargée.

Le cartographe doit donc conserver uniquement les éléments utiles.

> **Le choix du fond de carte dépend du message que l'on souhaite transmettre.**

---

# 7. La généralisation : sélectionner et simplifier l'information

Lorsqu'on réduit un territoire pour le représenter sur une carte, il devient
impossible de conserver tous les détails.

Le cartographe doit donc :

- **sélectionner** certains éléments ;
- **simplifier** certains tracés ;
- parfois **supprimer** certains détails ;
- éventuellement **schématiser** certaines formes.

Cette opération est appelée **généralisation cartographique**.

### Exemple

À grande échelle, une côte peut être représentée avec de nombreux détails :

- petites baies ;
- îlots ;
- irrégularités du littoral.

Lorsque l'espace représenté devient plus vaste, tous ces éléments ne peuvent
plus être conservés.

Certains détails doivent alors être simplifiés ou supprimés pour maintenir
la lisibilité de la carte.

La généralisation ne signifie donc pas nécessairement que la carte est
incorrecte.

Elle permet de **rendre l'information lisible à l'échelle choisie**.

Il faut retenir que :

> **Plus l'espace représenté est vaste, plus l'information cartographique
> doit être sélectionnée et simplifiée.**

Le changement d'échelle entraîne donc une variation :

- du niveau de détail ;
- du nombre d'objets représentés ;
- de la forme de certains objets cartographiques.

---

# 8. Échelle, projection et fond de carte : trois choix liés

L'échelle, la projection et le fond de carte ne doivent pas être étudiés
séparément.

Ces trois éléments participent ensemble à la **construction de la carte**.

Imaginons que l'on souhaite représenter la **population en France**.

Le cartographe doit notamment se poser plusieurs questions.

### 1. Quelle portion de l'espace représenter ?

La France entière ?  
Une région ?  
Une commune ?

### 2. À quelle échelle ?

Le niveau de détail ne sera pas le même selon l'espace représenté.

### 3. Quel fond de carte utiliser ?

Faut-il représenter :

- les régions ?
- les départements ?
- les communes ?

Le choix dépend de l'information que l'on souhaite cartographier.

### 4. Quelle projection utiliser ?

Cette question devient particulièrement importante lorsque l'espace
représenté est vaste.

### 5. Quels éléments conserver ?

Le cartographe doit enfin sélectionner les éléments nécessaires afin
que la carte reste **claire et lisible**.

Ces choix montrent à nouveau qu'une carte est une **construction**.

Le cartographe transforme, réduit et simplifie l'espace réel afin de
transmettre une information géographique.

---

# ✅ À retenir

À l'issue de cette deuxième séance, retenez principalement que :

1. **L'échelle** exprime le rapport entre une distance sur la carte et
   la distance correspondante dans la réalité.

2. Une **grande échelle** représente un espace restreint avec beaucoup
   de détails, tandis qu'une **petite échelle** représente un espace plus
   vaste avec moins de détails.

3. L'échelle influence directement le **niveau de détail** et le nombre
   d'objets représentés sur une carte.

4. Une **projection cartographique** permet de représenter la surface courbe
   de la Terre sur une surface plane.

5. **Toute projection entraîne des déformations.** Aucune projection ne peut
   conserver parfaitement les surfaces, les formes, les angles et les
   distances en même temps.

6. Le **centrage** et l'**orientation** d'une carte sont également des choix
   cartographiques.

7. Le **fond de carte** constitue le support géographique sur lequel
   l'information est représentée.

8. La **généralisation cartographique** consiste à sélectionner et simplifier
   les éléments représentés afin de conserver une carte lisible.

9. **Changer d'échelle, de projection ou de fond de carte peut modifier
   la manière dont un territoire est représenté et perçu.**

---

# ✏️ TD / Activité pratique

## Comprendre comment l'espace devient une carte

L'objectif de cette activité est de mettre en pratique les trois grandes
notions étudiées pendant la séance :

- l'échelle ;
- le niveau de détail ;
- la projection cartographique.

Le TD est organisé en **trois exercices courts et progressifs**.

---

## Exercice 1 - Lire et utiliser une échelle

À partir d'une carte fournie par l'enseignant, mesurez plusieurs distances
à l'aide d'une règle puis calculez les distances réelles correspondantes.

### Exemple

Sur une carte au **1 : 100 000**, deux villes sont séparées de **4 cm**.

Quelle est leur distance réelle ?

Nous savons que :

**1 cm = 1 km**

Donc :

**4 cm = 4 km**

La distance réelle est donc de **4 km**.

---

## Exercice 2 - Comparer plusieurs échelles

Vous observerez plusieurs représentations du **même territoire à des
échelles différentes**.

Pour chaque représentation, répondez aux questions suivantes :

1. Quelle carte représente l'espace le plus vaste ?
2. Quelle carte contient le plus de détails ?
3. Quels éléments apparaissent ou disparaissent lorsque l'échelle change ?
4. Pourquoi tous les éléments ne peuvent-ils pas être conservés ?

### Objectif

Cet exercice permet de comprendre la relation entre :

**échelle → espace représenté → niveau de détail → généralisation**

---

## Exercice 3 - Comparer des planisphères

Vous comparerez deux ou trois représentations différentes du monde.

Observez notamment :

1. la **forme** des continents ;
2. leur **taille apparente** ;
3. le territoire placé au **centre** ;
4. l'**orientation** de la carte ;
5. les principales différences entre les représentations.

L'objectif est de comprendre qu'un planisphère dépend :

- de la projection utilisée ;
- du centrage choisi ;
- de l'orientation choisie.

---

## Question de synthèse

À partir des trois exercices, répondez à la question suivante :

> **Pourquoi ne peut-on pas considérer une carte comme une reproduction
> exacte de la réalité ?**

Pour répondre, pensez notamment :

- à la réduction liée à l'échelle ;
- aux déformations liées à la projection ;
- à la sélection des informations ;
- à la généralisation ;
- au choix du fond de carte ;
- au centrage et à l'orientation.

### Objectif du TD

À ce stade, il ne s'agit pas de maîtriser toutes les projections
cartographiques ni toutes les opérations de généralisation.

L'objectif est de comprendre qu'en passant de l'espace réel à la carte,
le cartographe doit nécessairement **réduire, transformer, sélectionner
et simplifier la réalité géographique**.

---

# 📄 Support de cours

Le support de la séance est disponible au format PDF :

👉 [**Télécharger le support de la séance 2 (PDF)**](documents/Seance2_Les_elements_fondamentaux_d_une_carte.pdf)

Ce document correspond à la partie **« Séance 2 - Les éléments fondamentaux
d'une carte : échelle, projection et fond de carte »**.

---

# ✏️ Données et énoncé

### TD2 - Comprendre comment l'espace devient une carte

Le TD comprend trois exercices :

- lire et utiliser une échelle ;
- comparer un même territoire à plusieurs échelles ;
- comparer plusieurs représentations du monde.

👉 [**Télécharger l'énoncé du TD2 (PDF)**](documents/Exercice_seance_2.pdf)

---

# ✅ Correction du TD

La correction est disponible au format PDF :

👉 [**Télécharger la correction du TD2 (PDF)**](documents/XCorrection_exercice_seance_2.pdf)

---

## ➡️ Séance suivante

La prochaine séance sera consacrée à **l'information géographique**.

Après avoir compris comment l'espace réel est transformé pour être représenté
sur une carte, nous nous intéresserons à **l'information que l'on souhaite
cartographier**.

Nous apprendrons notamment à répondre à trois questions fondamentales :

**QUOI ? → Quel phénomène souhaite-t-on représenter ?**  
**OÙ ? → Où est-il localisé ?**  
**COMMENT ? → Comment peut-on le représenter ?**

Nous distinguerons également les trois grandes formes d'implantation
cartographique :

- ponctuelle ;
- linéaire ;
- surfacique.

👉 [**Continuer vers la séance 3 - L'information géographique : QUOI ? OÙ ? COMMENT ?**](03_Seance3_Information_Geographique.md)
