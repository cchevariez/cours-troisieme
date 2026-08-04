---
chapitre: 12
tags:
  - maths/troisieme
---

# Statistiques - Probabilité

## Statistiques

### Vocabulaire

> [!definition] Définition — Population
> On appelle population d'une série statistique l'ensemble des sujets d'une étude statistique.

> [!definition] Définition — Caractère
> On appelle caractère d'une série statistique le critère suivant lequel on étudie la population. On note $x_i$ le caractère de la ligne $i$.

> [!definition] Définition — Effectif
> L'effectif correspond au nombre d'individus correspondant à un caractère. On note $x_i$ le caractère et $n_i$ l'effectif de la ligne $i$.

> [!definition] Définition — Effectif total
> On appelle effectif total le nombre total d'individus dans la population. On le note $N$.

> [!exercice] Exercice 1
> Voici deux études statistiques :
>
> Étude sur l'âge des élèves dans une classe de quatrième.
>
> | Âge | Effectif |
> |---|---|
> | 11 | 2 |
> | 12 | 10 |
> | 13 | 9 |
> | 14 | 7 |
>
> Étude d'un constructeur automobile sur la couleur des voitures de ses clients.
>
> | Couleur | Effectif |
> |---|---|
> | Rouge | 10 |
> | Gris | 20 |
> | Noir | 25 |
> | Bleu | 15 |
> | Vert | 8 |
> | Blanc | 30 |
>
> 1. Déterminer, pour chacune des études, la population étudiée.
> 2. Déterminer, pour chacune des études, le caractère étudié.
> 3. Pour chacune des études, déterminer $x_3$ et $n_4$.
> 4. Pour chacune des études, donner une interprétation sous la forme d'une phrase de la troisième ligne de chaque tableau.
> 5. Déterminer l'effectif total de chaque série.

### Indicateurs

> [!definition] Définition — Étendue
> L'étendue d'une série statistique est la différence entre la plus grande valeur et la plus petite valeur de la série.

> [!definition] Définition — Fréquences en pourcentage
> On appelle fréquence le rapport entre un effectif partiel ($n_i$) et l'effectif total ($N$). On note $f_i$ la fréquence de la ligne $i$.
> $$f_i = \frac{n_i}{N} \times 100$$

> [!definition] Définition — Moyenne
> On appelle moyenne le rapport entre la somme des valeurs et le nombre de valeurs. On la note $\overline{x}$.
> $$\overline{x} = \frac{\text{somme}(n_i \times x_i)}{N} = \frac{\sum n_i x_i}{N}$$

> [!exercice] Exercice 2
> Reprenons une étude statistique du premier exercice.
>
> Étude sur l'âge des élèves dans une classe de première BAC.
>
> | Âge | Effectif |
> |---|---|
> | 15 | 2 |
> | 16 | 10 |
> | 17 | 9 |
> | 18 | 7 |
>
> 1. Déterminer l'étendue de cette série. Donner une interprétation de ce résultat.
> 2. Reproduire, sur votre copie, le tableau ci-dessus en rajoutant une colonne « fréquences en % » puis compléter cette colonne. Vos calculs doivent être arrondis au centième.
> 3. Déterminer la moyenne de cette série. Donner une interprétation de ce résultat.

> [!exercice] Exercice 3
> En sortie de caisse, on demande aux agents le code postal du client afin de pouvoir faire une étude géographique de la clientèle. Après une semaine de saisie, on a obtenu le tableau suivant :
>
> | Commune | Effectif |
> |---|---|
> | Beynost | 236 |
> | Miribel | 125 |
> | Montuel | 75 |
> | Rillieux-la-Pape | 144 |
> | Caluire | 80 |
> | Lyon | 300 |
> | Tramoyes | 35 |
>
> ![[carte2.png]]
>
> 1. Quelle est la population étudiée ?
> 2. Quel est le caractère de la population étudiée ? Est-il quantitatif ou qualitatif ?
> 3. Calculer l'effectif total.
> 4. Recopier et compléter le tableau en calculant la fréquence relative à chaque ville, d'abord sous forme décimale puis en pourcentage arrondi à l'unité.
> 5. Représenter cette série statistique sous la forme d'un diagramme circulaire.
> 6. À l'aide de la carte ci-dessus, imaginer et réaliser une représentation pertinente de la série statistique et lui donner un titre.

> [!definition] Définition — Médiane
> La médiane $M_e$ d'une série est telle que :
> - au moins 50% des données ont des valeurs inférieures ou égales à $M_e$ ;
> - au moins 50% des données ont des valeurs supérieures ou égales à $M_e$.

> [!exemple] Exemple — Calcul de la médiane avec une liste
> Supposons qu'un entraîneur de natation veuille former deux groupes de niveau, demande à ses 9 nageurs de parcourir deux longueurs en nage libre, et relève les temps suivants en secondes :
> $$30,6 \;;\; 29,1 \;;\; 32,9 \;;\; 35,1 \;;\; 30,0 \;;\; 36,4 \;;\; 31,7 \;;\; 35,5 \;;\; 33,9$$
> En rangeant les temps dans l'ordre croissant, on obtient :
> $$29,1 \;;\; 30,0 \;;\; 30,6 \;;\; 31,7 \;;\; \mathbf{32,9} \;;\; 33,9 \;;\; 35,1 \;;\; 35,5 \;;\; 36,4$$
> On peut isoler les 4 meilleurs nageurs et les 4 moins bons, mais il reste un nageur qui pourrait être dans l'un ou l'autre groupe : celui qui a nagé en 32,9 s. Ce temps est appelé la **médiane** de la série statistique : il partage la série en deux groupes de même effectif.
>
> Supposons maintenant qu'un 10ᵉ nageur arrive et soit capable de nager en 28,7 s. La liste devient :
> $$28,7 \;;\; 29,1 \;;\; 30,0 \;;\; 30,6 \;;\; 31,7 \;;\; 32,9 \;;\; 33,9 \;;\; 35,1 \;;\; 35,5 \;;\; 36,4$$
> Comme l'effectif est pair, il y a deux valeurs centrales. La médiane est leur moyenne :
> $$(31,7 + 32,9) \div 2 = 32,3 \text{ s}$$
>
> **En résumé**, lorsque la série est rangée dans l'ordre :
> - si l'effectif total est impair, la médiane est la valeur centrale de la série ;
> - si l'effectif total est pair, la médiane est la moyenne des deux valeurs centrales.
>
> **Calcul de la médiane à partir d'un tableau d'effectifs :**
>
> Prenons ce tableau de pointures de chaussures :
>
> | Pointure | 39 | 40 | 41 | 42 | 43 | 44 | 45 |
> |---|---|---|---|---|---|---|---|
> | Effectif | 2 | 4 | 8 | 15 | 14 | 10 | 8 |
>
> L'effectif total est 61, donc la valeur centrale est en position $\lceil 61 \div 2 \rceil = 31$. On calcule les effectifs cumulés croissants :
>
> | Pointure | 39 | 40 | 41 | 42 | 43 | 44 | 45 |
> |---|---|---|---|---|---|---|---|
> | Effectif | 2 | 4 | 8 | 15 | 14 | 10 | 8 |
> | Eff. cumulés | 2 | 6 | 14 | 29 | 43 | 53 | 61 |
>
> Les valeurs de la 30ᵉ à la 43ᵉ sont des 43. La 31ᵉ valeur est donc 43 : la médiane est $M_e = 43$.

### Tableur et statistiques

On utilise l'outil informatique pour nous assister. Pour faire nos calculs, on utilise un tableur ; le plus connu est Excel. Pour effectuer ses calculs, un tableur n'utilise pas directement une valeur mais l'*adresse* de la cellule où se trouve cette valeur. Cette adresse fonctionne comme aux échecs : l'adresse $B12$ correspond à la valeur située dans la colonne $B$, ligne $12$.

> [!exercice] Exercice 4
> Voici une feuille de calcul :
>
> ![[stat_tab3.png]]
>
> La cellule $C1$ utilise une formule : quel sera le résultat obtenu ?

> [!exercice] Exercice 5
> Le tableau ci-dessous a été réalisé à l'aide d'un tableur. Il indique le nombre d'abonnements Internet à haut débit et à très haut débit entre 2014 et 2016, sur réseau fixe, en France. (Sources : Arcep et Statistica.)
>
> | | A | B (2014) | C (2015) | D (2016) |
> |---|---|---|---|---|
> | 1 | | **2014** | **2015** | **2016** |
> | 2 | Abonnements à haut débit (en millions) | 22,855 | 22,63 | 22,238 |
> | 3 | Abonnements à très haut débit (en millions) | 3,113 | 4,237 | 5,446 |
> | 4 | Total (en millions) | 25,968 | 26,867 | 27,684 |
>
> 1. Combien d'abonnements Internet à très haut débit, en millions, ont été comptabilisés pour l'année 2016 ?
> 2. Vérifier qu'en 2016, il y avait 817 000 abonnements Internet à haut débit et à très haut débit de plus qu'en 2015.
> 3. Quelle formule a-t-on pu saisir dans la cellule $B4$ avant de la recopier vers la droite, jusqu'à la cellule $D4$ ?
> 4. En 2015, seulement 5,6 % des abonnements Internet à très haut débit utilisaient la fibre optique. Quel nombre d'abonnements Internet à très haut débit cela représentait-il ?

> [!exercice] Exercice 6
> Sur une feuille de calcul, on a reporté le classement des dix premiers pays, par le nombre de médailles, aux Jeux Olympiques de Rio en 2016.
>
> | | A (Rang) | B (Pays) | C (Or) | D (Argent) | E (Bronze) | F (Total) |
> |---|---|---|---|---|---|---|
> | 2 | 1 | États-Unis | 46 | 37 | 38 | 121 |
> | 3 | 2 | Grande Bretagne | 27 | 23 | 17 | 67 |
> | 4 | 3 | Chine | 26 | 18 | 26 | 70 |
> | 5 | 4 | Russie | 19 | 18 | 19 | 56 |
> | 6 | 5 | Allemagne | 17 | 10 | 15 | 42 |
> | 7 | 6 | Japon | 12 | 8 | 21 | 41 |
> | 8 | 7 | France | 10 | 18 | 14 | 42 |
> | 9 | 8 | Corée du Sud | 9 | 3 | 9 | 21 |
> | 10 | 9 | Italie | 8 | 12 | 8 | 28 |
> | 11 | 10 | Australie | 8 | 11 | 10 | 29 |
>
> 1. Quelle formule, parmi les trois proposées, a été saisie dans la cellule $F2$ de cette feuille de calcul, avant qu'elle soit étirée vers le bas ?
>
> | Formule A | Formule B | Formule C |
> |---|---|---|
> | $=46+37+38$ | `=SOMME(C2:E2)` | `C2+D2+E2` |
>
> 2. On observe la série des nombres de médailles d'or de ces dix pays.
>     1. Quelle est l'étendue de cette série ?
>     2. Quelle est la moyenne de cette série ?
> 3. Quel est le pourcentage de médailles d'or remportées par la France par rapport à son nombre total de médailles ? Arrondir le résultat au dixième de %.
> 4. Le classement aux Jeux Olympiques s'établit selon le nombre de médailles d'or obtenues et non selon le nombre total de médailles. Pour cette raison, la France avec 42 médailles se retrouve derrière le Japon qui n'en a que 41. En observant l'Italie et l'Australie, établir la règle de classement en cas d'égalité sur le nombre de médailles d'or.
> 5. Un journaliste sportif propose une nouvelle procédure pour classer les pays : chaque médaille d'or rapporte 3 points, chaque médaille d'argent rapporte 2 points et chaque médaille de bronze rapporte 1 point. Dans ces conditions, la France dépasserait-elle le Japon ?
