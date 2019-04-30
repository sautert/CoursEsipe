# Recherche Opérationnelle

### definition :
- *(wiki)* La recherche opérationnelle est une discipline qui s'occupe de l'application de méthodes avancées pour faciliter l'aide à la décision
- *(Larousse)* Ensemble de techniques pour la résolution de problèmes, notamment d'économie, pour prendre les meilleures décision tout en respectant les contraintes du problème
- *(Cambridge dictionnary)* Work that is done to find the best ways to solve problems in business & industry

** => A la croisée entre : économie, math, algo. **

## I. Exemples :

### 1) Le voyageur de commerce (TSP)

On a n ville, le voyageur part de Paris et doit visiter toutes les villes indiquées et revenir à paris.

=> Comment minimiser le temps de trajet

Nomre de possibilité avec n ville : n!


### 2) Emetteurs

n émetteurs placés, chacun émet à une fréquence qui doit être différentes de celle d'un émetteur trop proche. On sait dire si 2 émetteurs sont proche ou non

=> De combien de fréquences différentes a-t-on besoin au minimum ?

** Modélisation : ** Un graphe des émetteurs

### 3) Mariage stable

n hommes | n femmes

Femme : A, B, C       
Hommes : X, Y, Z

Femme | pref | |Homme | pref
-|-|-|-|-
A | X, Y, Z || X | A, C, B
B | Z, X, Y || Y | B, A, C
C | X, Y, Z || Z | C, A, B

### 4) Rations alimentaires

sytèmes linéaires

### 5) Transport de marchandises

 | Charge max | Volume max
 -|-|-
 Avant | 10 | 6800
 milieu | 18 | 8700
 Arrière | 8 | 5300

 Il faut respecter les ratios de tonnage

 On veut transporter ces marchandises

 | Quatité dispo (tonne) | Volume (m3/tonne) | bénéfice
 -|-|-|-
 **M1** | 18 | 480 | 310
 **M2** | 15 | 650 | 380
 **M3** | 23 | 580 | 350
 **M4** | 12 | 390 | 285

### 6) Emplois du temps

Des classes, parfois en demi classe         
Des matière différentes   
Des profs avec des contraintes  
Des salles avec des capacités et des équipements


## II. Graphes

On trouve des problèmes du genre :
* Plus court chemin
* calcule de flots dans des réseaux

## III. Qu'est ce que la recherche Opé.

Terme générique pour des problèmes différents qui ont en commun d'être appliqués. Il s'agit de trouver des solutions pour rationaliser, simuler, optimiser, planifier

**Objectifs :**
- Apporter des nouvelles solutions
- Améliorer les solutions humaines
- S'adapter aux changements

L'algo est omniprésente en R.O.
- Identifier les plus difficiles -> heuristique | solution approchées
- Utiliser les bons algos ou outil quand le problème est facile/connu

Au passage, l'optimisation combinatoire est un domaine liés (théorique)
* On a des contraintes de validité d'une solutions
* On a un objectif (a maximiser ou minimiser)
* On cherche parmis les solutions valides, celles qui optimise l'Objectifs

**Ex :**
- Voyageur de commerce : n! solution valide
- Plus court chemin : Plein de chemin, on optimise le poids


## IV. La recherche opérationnelle dans le monde

Il y a un département R&D en RO dans :  
Air France, SNCF, EDF, France Telecom, Bouygues, Engie, La Poste, Renault, SFR, Google...

Dans certains cs, c'est critique pour la survie : Vélib (répartir les vélos la nuit)

**Les petites entreprises**
- Boites de conseil spécialisé
- Logiciels dédiés
- Partenariats académiques

Lien si intéressé : [**Challenges ROADEF**](http://challenge.roadef.org)
