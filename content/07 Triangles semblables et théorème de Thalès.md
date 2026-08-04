---
chapitre: 7
tags:
  - maths/troisieme
status: brouillon
---

> [!remarque] Chapitre en chantier
> Ce chapitre est encore exclu du support de cours compilé (`troisieme.tex`). Le texte et les 20 figures géométriques (tikz/tkz-euclide/pstricks, recompilées individuellement) sont maintenant complets ici ; il ne reste plus qu'à le relire et à le réintégrer au document source si souhaité.

# Triangles semblables et théorème de Thalès

## Triangles semblables

### Définition

> [!definition] Définition
> Deux triangles sont dits **semblables** lorsqu'ils ont les mêmes angles deux à deux.
>
> On dit aussi que deux triangles semblables sont des triangles de même forme.

> [!exemple] Exemple
> Les triangles $ABC$ et $DEF$ ci-dessous sont semblables car :
> - $\widehat{BAC} = \widehat{EDF}$
> - $\widehat{ABC} = \widehat{DEF}$
> - $\widehat{ACB} = \widehat{DFE}$

> [!remarque] Remarque
> Deux triangles semblables ont la même forme mais pas nécessairement la même taille. L'un peut être un agrandissement ou une réduction de l'autre.

### Propriété fondamentale

> [!propriete] Propriété
> Si deux triangles sont semblables, alors les longueurs des côtés de l'un sont proportionnelles aux longueurs des côtés correspondants de l'autre.
>
> Le coefficient de proportionnalité s'appelle le **rapport de similitude** ou **coefficient d'agrandissement** (ou de réduction).

> [!exemple] Exemple
> Si les triangles $ABC$ et $DEF$ sont semblables avec le rapport de similitude $k$, alors :
> $$\frac{DE}{AB} = \frac{EF}{BC} = \frac{DF}{AC} = k$$

> [!remarque] Remarque
> - Si $k > 1$, le triangle $DEF$ est un agrandissement du triangle $ABC$.
> - Si $k < 1$, le triangle $DEF$ est une réduction du triangle $ABC$.
> - Si $k = 1$, les deux triangles sont isométriques (superposables).

### Critères de similitude

Il existe plusieurs façons de démontrer que deux triangles sont semblables, sans avoir à vérifier les trois angles.

> [!propriete] Propriété — Critère AA (Angle-Angle)
> Si deux triangles ont **deux angles égaux** deux à deux, alors ils sont semblables.
>
> ![[thales-critere-aa.png]]

> [!remarque] Remarque
> Puisque la somme des angles d'un triangle vaut $180°$, si deux angles sont égaux, le troisième l'est automatiquement.

> [!propriete] Propriété — Critère SAS (Côté-Angle-Côté)
> Si deux triangles ont **un angle égal compris entre deux côtés proportionnels**, alors ils sont semblables.
>
> ![[thales-critere-sas.png]]

> [!exemple] Exemple
> Si $\widehat{BAC} = \widehat{EDF}$ et $\dfrac{DE}{AB} = \dfrac{DF}{AC} = k$, alors les triangles $ABC$ et $DEF$ sont semblables.

> [!propriete] Propriété — Critère SSS (Côté-Côté-Côté)
> Si deux triangles ont leurs **trois côtés proportionnels**, alors ils sont semblables.
>
> ![[thales-critere-sss.png]]

> [!exemple] Exemple
> Si $\dfrac{DE}{AB} = \dfrac{EF}{BC} = \dfrac{DF}{AC}$, alors les triangles $ABC$ et $DEF$ sont semblables.

> [!methode] Méthode — Démontrer que deux triangles sont semblables
> Pour démontrer que deux triangles sont semblables, on peut utiliser l'un des trois critères :
> 1. **Critère AA** : montrer que deux angles sont égaux (le plus souvent utilisé).
> 2. **Critère SAS** : montrer qu'un angle est égal et que les deux côtés adjacents sont proportionnels.
> 3. **Critère SSS** : montrer que les trois côtés sont proportionnels.

### Exercices d'application

> [!exercice] Exercice 1
> Les triangles $MNP$ et $RST$ sont semblables.
>
> On donne : $MN = 6$ cm, $NP = 8$ cm, $MP = 10$ cm et $RS = 9$ cm.
> 1. Calculer le rapport de similitude.
> 2. En déduire les longueurs $ST$ et $RT$.

> [!exercice] Exercice 2
> Deux triangles équilatéraux sont-ils toujours semblables ? Justifier.

> [!exercice] Exercice 3
> Les triangles $ABC$ et $DEF$ sont semblables. On donne :
> - Triangle $ABC$ : $AB = 4$ cm, $BC = 5$ cm, $AC = 6$ cm
> - Triangle $DEF$ : $DE = 10$ cm
>
> Calculer les longueurs $EF$ et $DF$.

## Théorème de Thalès

### Rappel : angles et droites parallèles

> [!propriete] Propriété — Angles et droites parallèles
> Lorsque deux droites parallèles sont coupées par une sécante :
> - Les **angles correspondants** sont égaux.
> - Les **angles alternes-internes** sont égaux.
>
> ![[thales-angles-paralleles.png]]

### Démonstration du théorème de Thalès

> [!activite] Activité
> On considère deux droites $(d_1)$ et $(d_2)$ sécantes en $O$. Les points $A$ et $M$ sont sur $(d_1)$, les points $B$ et $N$ sont sur $(d_2)$. Les droites $(AB)$ et $(MN)$ sont parallèles.
>
> ![[thales-demo.png]]
>
> **Objectif :** démontrer que $$\frac{OA}{OM} = \frac{OB}{ON} = \frac{AB}{MN}$$

### Énoncé du théorème

> [!propriete] Propriété — Théorème de Thalès
> Soient deux droites $(d_1)$ et $(d_2)$ sécantes en un point $O$.
>
> Soient $A$ et $M$ deux points de la droite $(d_1)$ distincts de $O$.
>
> Soient $B$ et $N$ deux points de la droite $(d_2)$ distincts de $O$.
>
> Si les droites $(AB)$ et $(MN)$ sont parallèles, alors :
> $$\frac{OA}{OM} = \frac{OB}{ON} = \frac{AB}{MN}$$
>
> ![[thales-enonce.png]]

> [!remarque] Remarque — Pourquoi ça marche ?
> Le théorème de Thalès est une conséquence directe de la similitude des triangles :
> - Les droites parallèles créent des angles égaux (angles correspondants).
> - Deux triangles ayant deux angles égaux sont semblables (critère AA).
> - Des triangles semblables ont des côtés proportionnels.

### Différentes configurations

> [!methode] Méthode — Les trois configurations du théorème de Thalès
> Le théorème de Thalès peut s'appliquer dans trois configurations différentes :
>
> **Configuration 1 : les points sont dans le même ordre**
>
> ![[thales-config1.png]]
> $$\frac{OA}{OM} = \frac{OB}{ON} = \frac{AB}{MN}$$
>
> **Configuration 2 : les points ne sont pas dans le même ordre (configuration en papillon)**
>
> ![[thales-config2-papillon.png]]
> $$\frac{OA}{OM} = \frac{OB}{ON} = \frac{AB}{MN}$$
>
> **Configuration 3 : droites parallèles coupées par deux sécantes (triangle)**
>
> ![[thales-config3-triangle.png]]
>
> Si $(BC) \parallel (DE)$, alors :
> $$\frac{AB}{AD} = \frac{AC}{AE} = \frac{BC}{DE}$$

> [!remarque] Remarque
> Dans tous les cas, il faut :
> - Deux droites sécantes (ou parallèles dans la configuration 3).
> - Deux droites parallèles qui les coupent.

### Exercices d'application

> [!exercice] Exercice 1
> Sur la figure suivante, $GI=6$ cm, $GH=5$ cm, $IJ=3,6$ cm, $IK=2,4$ cm et $(GH) \parallel (JK)$.
>
> ![[thales-exo-ghi.png]]
>
> Calculer $JK$ et $IH$.

> [!exercice] Exercice 2
> Sur la figure suivante, $UW=10$ cm, $UV=9$ cm, $WX=4$ cm, $WY=3,2$ cm et $(UV) \parallel (XY)$.
>
> ![[thales-exo-uvw.png]]
>
> Calculer $XY$ et $WV$.

> [!exercice] Exercice 3
> On sait que $HL=9$ cm, $HK=16,2$ cm et $LI=3,7$ cm.
>
> ![[thales-exo-hlk.png]]
>
> Calculer la valeur exacte de $KJ$.

> [!exercice] Exercice 4
> Un poteau vertical de $2,5$ m de hauteur projette une ombre de $1,8$ m sur le sol.
>
> Au même instant, un arbre projette une ombre de $6,3$ m.
>
> Quelle est la hauteur de l'arbre ?

## Réciproque du théorème de Thalès

### Énoncé

> [!propriete] Propriété — Réciproque du théorème de Thalès
> Soient deux droites $(d_1)$ et $(d_2)$ sécantes en un point $O$.
>
> Soient $A$ et $M$ deux points de la droite $(d_1)$ distincts de $O$.
>
> Soient $B$ et $N$ deux points de la droite $(d_2)$ distincts de $O$.
>
> Si $\dfrac{OA}{OM} = \dfrac{OB}{ON}$ et si les points $A$, $O$, $M$ et $B$, $O$, $N$ sont alignés dans le même ordre, alors les droites $(AB)$ et $(MN)$ sont parallèles.

> [!remarque] Attention !
> Il faut vérifier deux conditions :
> 1. L'égalité des rapports : $\dfrac{OA}{OM} = \dfrac{OB}{ON}$.
> 2. L'alignement dans le même ordre des points.
>
> Si ces deux conditions sont vérifiées, alors on peut conclure que les droites sont parallèles.

### Méthodologie

> [!methode] Méthode — Démontrer que deux droites sont parallèles avec la réciproque de Thalès
> Pour démontrer que deux droites $(AB)$ et $(MN)$ sont parallèles en utilisant la réciproque du théorème de Thalès :
> 1. **Vérifier les hypothèses** : repérer deux droites sécantes avec des points alignés.
> 2. **Calculer les rapports** : $\dfrac{OA}{OM}$ et $\dfrac{OB}{ON}$.
> 3. **Comparer les rapports** :
>     - Si les rapports sont égaux et les points alignés dans le même ordre, alors les droites sont parallèles.
>     - Si les rapports ne sont pas égaux, on ne peut rien conclure avec ce théorème.
> 4. **Conclure** en rédigeant clairement.

> [!exemple] Exemple
> Sur une figure, on donne : $OA = 3$ cm, $OM = 4,5$ cm, $OB = 4$ cm et $ON = 6$ cm.
>
> Les droites $(AB)$ et $(MN)$ sont-elles parallèles ?
>
> **Solution :**
> - D'une part : $\dfrac{OA}{OM} = \dfrac{3}{4,5} = \dfrac{30}{45} = \dfrac{2}{3}$
> - D'autre part : $\dfrac{OB}{ON} = \dfrac{4}{6} = \dfrac{2}{3}$
> - On constate que $\dfrac{OA}{OM} = \dfrac{OB}{ON}$.
> - De plus, les points $A$, $O$, $M$ sont alignés dans cet ordre et les points $B$, $O$, $N$ sont alignés dans cet ordre.
>
> D'après la réciproque du théorème de Thalès, les droites $(AB)$ et $(MN)$ sont parallèles.

## Contraposée du théorème de Thalès

### Énoncé

> [!propriete] Propriété — Contraposée du théorème de Thalès
> Soient deux droites $(d_1)$ et $(d_2)$ sécantes en un point $O$.
>
> Soient $A$ et $M$ deux points de la droite $(d_1)$ distincts de $O$.
>
> Soient $B$ et $N$ deux points de la droite $(d_2)$ distincts de $O$.
>
> Si $\dfrac{OA}{OM} \neq \dfrac{OB}{ON}$, alors les droites $(AB)$ et $(MN)$ ne sont pas parallèles.

> [!remarque] Remarque
> La contraposée permet de démontrer que deux droites **ne sont pas parallèles**. Elle est utilisée lorsque les rapports calculés ne sont pas égaux.

### Méthodologie

> [!methode] Méthode — Démontrer que deux droites ne sont pas parallèles
> Pour démontrer que deux droites $(AB)$ et $(MN)$ ne sont pas parallèles :
> 1. **Calculer les rapports** : $\dfrac{OA}{OM}$ et $\dfrac{OB}{ON}$.
> 2. **Comparer les rapports** : si $\dfrac{OA}{OM} \neq \dfrac{OB}{ON}$.
> 3. **Conclure** : d'après la contraposée du théorème de Thalès, les droites $(AB)$ et $(MN)$ ne sont pas parallèles.

> [!exemple] Exemple
> Sur une figure, on a : $OP = 6$ cm, $OR = 8$ cm, $OQ = 9$ cm et $OS = 13$ cm.
>
> Les droites $(PQ)$ et $(RS)$ sont-elles parallèles ?
>
> **Solution :**
> - D'une part : $\dfrac{OP}{OR} = \dfrac{6}{8} = \dfrac{3}{4} = 0,75$
> - D'autre part : $\dfrac{OQ}{OS} = \dfrac{9}{13} \approx 0,69$
> - On constate que $\dfrac{OP}{OR} \neq \dfrac{OQ}{OS}$.
>
> D'après la contraposée du théorème de Thalès, les droites $(PQ)$ et $(RS)$ ne sont pas parallèles.

### Exercices d'application

> [!exercice] Exercice 1
> 1. Sur la figure ci-contre, on a : $TC = 4$ cm, $TJ = 5$ cm, $JK = 8,5$ cm, $CH = 6,8$ cm. Les droites $(CJ)$ et $(HK)$ sont-elles parallèles ?
>
>     ![[thales-exo-tcj-hk.png]]
>
> 2. Sur la figure ci-contre, on a : $AP = 4$ cm, $AV = 5$ cm, $VR = 3,5$ cm, $PJ = 2,8$ cm. Les droites $(PV)$ et $(JR)$ sont-elles parallèles ?
>
>     ![[thales-exo-apv-jr.png]]
>
> 3. Sur la figure ci-contre, on a : $ZE = 4$ cm, $ZR = 5$ cm, $RK = 7,5$ cm, $EC = 6,2$ cm. Les droites $(ER)$ et $(CK)$ sont-elles parallèles ?
>
>     ![[thales-exo-zer-ck.png]]
>
> 4. Sur la figure ci-contre, on a : $XD = 6$ cm, $XP = 5$ cm, $PE = 2,5$ cm, $DN = 3$ cm. Les droites $(DP)$ et $(NE)$ sont-elles parallèles ?
>
>     ![[thales-exo-xdp-ne.png]]

> [!exercice] Exercice 2
> *D'après l'exercice 3 du brevet Métropole 2024.*
>
> Sur la figure ci-dessous, on a :
> - $(\mathscr{C})$ est un cercle de centre $X$ et de rayon $10$ cm ;
> - $[SF]$ est un diamètre de ce cercle et $D$ est un point du cercle ;
> - les points $F$, $Y$, $S$ sont alignés, ainsi que les points $D$, $P$, $S$ ;
> - les droites $(FD)$ et $(YP)$ sont parallèles ;
> - $FD = 12$ cm ; $DS = 16$ cm et $SY = 4$ cm.
>
> ![[thales-exo-cercle-sfd.png]]
>
> 1. Justifier que le diamètre $[SF]$ mesure $20$ cm.
> 2. Démontrer que le triangle $SFD$ est rectangle en $D$.
> 3. Calculer $SP$.
> 4.
>     1. Justifier que l'aire du triangle $SFD$ est égale à $96$ cm².
>     2. Calculer l'aire du disque, arrondie au centième. *Rappel* : l'aire du disque est égale à $\pi \times R^2$, où $R$ est le rayon du disque.
> 5. Quel pourcentage de l'aire du disque représente l'aire du triangle $SFD$ ?

> [!exercice] Exercice 3 — DNB Septembre 2024 Métropole
> Un agriculteur possède un champ de blé ayant la forme d'un triangle $ABC$ rectangle en $B$ représenté ci-contre.
>
> On donne $AB = 200$ m et $BC = 150$ m.
>
> Pour moissonner son champ, il utilise une moissonneuse-batteuse qui, à chaque passage, coupe des bandes de 12 mètres de large parallèles à la droite $(AB)$. On a donc $BE = 12$ m.
>
> Il commence à passer le long du côté $[AB]$. Le segment en pointillés $[DE]$ représente la limite du premier passage de la moissonneuse-batteuse.
>
> Après avoir fait 5 passages, il a moissonné le quadrilatère $ABGF$.
>
> ![[thales-exo-champ-ble.png]]
>
> 1.
>     1. Montrer que $BG = 60$ m.
>     2. En déduire que $CG = 90$ m.
> 2. Démontrer que la longueur $GF$ est de $120$ m.
> 3.
>     1. Démontrer que l'aire du triangle rectangle $CGF$ est de 5 400 m².
>     2. Le quadrilatère $ABGF$ a une surface de 9 600 m² qui a été moissonnée en 80 minutes. On admet que le temps de travail de la moissonneuse-batteuse est proportionnel à la surface moissonnée. Calculer le temps de travail qu'il faut pour moissonner la partie restante $CGF$ de son champ.
> 4. L'année suivante, il décide de clôturer son champ $ABC$ afin d'y mettre des animaux pour l'été. Quelle longueur de clôture doit-il acheter ?

> [!exercice] Exercice 4 — DNBPRO Septembre 2023 Métropole
> On considère la figure suivante.
>
> ![[thales-exo-rectangle-obcd.png]]
>
> 1. Calculer la longueur du segment $[BD]$.
> 2. Montrer par un calcul que la longueur du segment $[OC]$ est 18 mètres.
> 3. On souhaite calculer la longueur du segment $[AC]$ en utilisant le théorème de Thalès sachant que :
>     - Dans le triangle $(ODB)$ les droites $(AC)$ et $(BD)$ sont parallèles.
>     - Les points $O$, $A$ et $B$ sont alignés.
>     - Les points $O$, $C$ et $D$ sont alignés.
>     1. L'une des égalités suivantes correspond au théorème de Thalès appliqué à la figure ci-dessus :
>         $$\dfrac{OC}{OD} = \dfrac{AC}{BD} \;;\quad \dfrac{OC}{CD} = \dfrac{AC}{BD} \;;\quad\dfrac{DC}{DO} = \dfrac{OA}{OB} \;;\quad\dfrac{OD}{OC} = \dfrac{OA}{OB}$$
>         Recopier la bonne égalité sur la copie.
>     2. Calculer la longueur du segment $[AC]$ en donnant toutes les étapes du calcul.

> [!exercice] Exercice 5 — DNBPRO Septembre 2023 Polynésie
> *Les calculs seront détaillés sur la copie.*
>
> Tehani souhaite une étagère murale composée de 2 planches en manguier et d'une corde. Les deux planches représentées par les segments $[MN]$ et $[BC]$ mesurent respectivement 20 cm et 40 cm. Pour des raisons d'esthétique, elle décide d'espacer les 2 planches et le point de fixation $A$ de 30 cm à chaque fois. On donne : $AP = PH = 30$ cm, $(MN) \parallel (BC)$ et $(AH) \perp (BC)$.
>
> ![[thales-exo-etagere.png]]
>
> 1. Donner les mesures des longueurs $MN$ et $BC$, exprimées en cm.
> 2. Calculer la longueur $BH$. Exprimer le résultat en cm.
> 3. Calculer la longueur $AH$. Exprimer le résultat en cm.
>
> Pour terminer son étagère, elle doit rajouter une corde (représentée par les segments $[AB]$ et $[AC]$).
>
> 4. Calculer la longueur $AB$. Exprimer le résultat en cm.
> 5. Justifier si une corde de 100 cm est assez longue.
