---
chapitre: 26
tags:
  - maths/troisieme
---

# Automatismes

## Présentation

Depuis la session 2022, l'épreuve de mathématiques du brevet commence par une partie « automatismes » : 20 minutes, **sans calculatrice**, 6 points, portant sur l'ensemble des notions du cycle 4 (5e, 4e, 3e). Ce chapitre propose de travailler ces automatismes toute l'année, à raison d'une fiche de 15 minutes par semaine sur 25 semaines, en classe si le temps le permet ou en autonomie sinon.

**Deux règles de construction :**
1. **On ne teste jamais une notion avant le cours correspondant.** Les automatismes liés aux chapitres 1 à 14 n'apparaissent qu'après que le chapitre a été traité en classe. En revanche, les automatismes de cycle 4 sans chapitre dédié dans ce cours (fractions, relatifs, proportionnalité simple, etc., déjà vus en 5e/4e) sont travaillés dès la semaine 1.
2. **C'est additif, pas remplaçant.** Une fois qu'un thème entre en rotation, il continue à revenir régulièrement dans les semaines suivantes — l'objectif est de ne plus jamais le perdre d'ici l'épreuve, pas de le travailler une seule fois.

Chaque semaine propose deux fiches indépendantes de 10 questions courtes (Fiche A et Fiche B), portant sur exactement les mêmes cases thématiques mais avec des valeurs numériques différentes — la répétition du type de question n'est pas un problème, c'est même l'objectif. Chaque fiche est suivie immédiatement de son corrigé.

**Conventions de rédaction des résultats**, sauf indication contraire dans l'énoncé :
- Un résultat fractionnaire est donné sous forme de fraction **irréductible**.
- Un résultat qui comporte $\pi$ est donné sous sa **valeur exacte** (par exemple $9\pi$ cm²), sauf si l'énoncé demande explicitement une valeur arrondie.
- Un résultat décimal exact est donné tel quel ; s'il ne « tombe pas juste », l'énoncé précise l'arrondi attendu (au dixième, au centième...).

## Légende des thèmes

**Cycle 4 (dès la semaine 1) :**

| Code | Thème |
|---|---|
| `CM` | Calcul mental et priorités opératoires |
| `FR` | Fractions (addition, soustraction, simplification) |
| `REL` | Nombres relatifs |
| `PROP` | Proportionnalité et pourcentages |
| `PUI` | Puissances de 10, écriture scientifique |
| `CONV` | Conversions d'unités |
| `AP` | Aires et périmètres usuels |
| `LEC` | Lecture de graphiques et de tableaux |

**Troisième (déblocage progressif) :** `Ch1` à `Ch14`, correspondant aux chapitres de ce cours.

## Calendrier de déblocage (par défaut, à ajuster selon votre progression réelle)

| Chapitre | Semaines de cours | Semaine de déblocage |
|---|---|---|
| 1. Activités numériques et littérales | S1–S2 | S3 |
| 2. Rappels de géométrie | S3–S4 | S5 |
| 3. Le développement | S5–S6 | S7 |
| 4. Arithmétique | S7–S8 | S9 |
| 5. Proportionnalité et grandeurs composées | S9–S10 | S11 |
| 6. Factorisation | S11 | S12 |
| 7. Triangles semblables et Thalès | S12–S13 | S14 |
| 8. Notion de fonction | S14 | S15 |
| 9. Équations et inéquations | S15–S16 | S17 |
| 10. Fonctions affines et linéaires | S17 | S18 |
| 11. Trigonométrie | S18–S19 | S20 |
| 12. Statistiques - Probabilité | S20 | S21 |
| 13. Homothétie | S21 | S22 |
| 14. Géométrie dans l'espace | S22–S23 | S24 |

À partir de la semaine 24, plus aucun nouveau thème : les fiches deviennent entièrement cumulatives, en révision directe de l'épreuve.

## Rappels de méthode (cycle 4)

> [!methode] Méthode — `CM` Priorités opératoires
> Dans un calcul sans parenthèses, on effectue dans l'ordre : 1) les puissances, 2) les multiplications et divisions (de gauche à droite), 3) les additions et soustractions (de gauche à droite). S'il y a des parenthèses, on les calcule en premier, en respectant les mêmes priorités à l'intérieur.

> [!exemple] Exemple 1 — sans parenthèses
> $$5 + 3 \times 4 = 5 + 12 = 17$$
> On calcule d'abord $3\times4$, jamais $5+3$ en premier.

> [!exemple] Exemple 2 — avec parenthèses
> $$(5+3)\times 4 = 8 \times 4 = 32$$
> Ici les parenthèses imposent de calculer $5+3$ avant de multiplier.

> [!exemple] Exemple 3 — avec une puissance
> $$2 + 3^2 \times 2 = 2 + 9 \times 2 = 2+18=20$$
> On calcule d'abord la puissance $3^2=9$, puis la multiplication, puis l'addition.

> [!methode] Méthode — `FR` Addition et soustraction de fractions
> Pour additionner ou soustraire deux fractions, il faut d'abord les mettre au même dénominateur, puis additionner ou soustraire les numérateurs en gardant ce dénominateur commun.
> $$\frac{a}{b} + \frac{c}{b} = \frac{a+c}{b}$$

> [!exemple] Exemple 1 — même dénominateur
> $$\frac{3}{5}-\frac{1}{5}=\frac{2}{5}$$

> [!exemple] Exemple 2 — un dénominateur multiple de l'autre
> $$\frac{2}{3}+\frac{1}{6} = \frac{4}{6}+\frac{1}{6} = \frac{5}{6}$$
> $6$ est un multiple de $3$ ($6=3\times2$), donc on convertit $\dfrac{2}{3}$ en $\dfrac{4}{6}$.

> [!exemple] Exemple 3 — dénominateurs quelconques
> $$\frac{1}{4}+\frac{1}{3} = \frac{3}{12}+\frac{4}{12} = \frac{7}{12}$$
> On prend comme dénominateur commun le produit $4\times3=12$.

> [!methode] Méthode — `REL` Opérations sur les relatifs
> - Deux nombres de même signe : on additionne leurs distances à zéro et on garde le signe commun.
> - Deux nombres de signes différents : on soustrait leurs distances à zéro (la plus petite à la plus grande) et on garde le signe du nombre qui a la plus grande distance à zéro.
> - Soustraire un nombre revient à ajouter son opposé.
> - Produit ou quotient : même signe $\Rightarrow$ résultat positif ; signes différents $\Rightarrow$ résultat négatif.

> [!exemple] Exemple 1 — addition, même signe
> $$(-5)+(-3)=-8$$

> [!exemple] Exemple 2 — addition, signes différents
> $$(-5)+8=3$$

> [!exemple] Exemple 3 — soustraction
> $$4-(-7)=4+7=11$$

> [!exemple] Exemple 4 — produit ou quotient
> $$(-3)\times(-4)=12 \qquad (-3)\times4=-12 \qquad (-12)\div(-4)=3$$

> [!methode] Méthode — `PROP` Produit en croix et pourcentages
> Dans un tableau de proportionnalité, $\dfrac{a}{b}=\dfrac{c}{d}$ donc $a \times d = b \times c$ (produit en croix). Calculer $t\%$ d'une quantité $Q$, c'est calculer $\dfrac{t}{100}\times Q$.

> [!exemple] Exemple 1 — produit en croix
> Si $\dfrac{4}{5}=\dfrac{x}{15}$, alors $x=\dfrac{4\times15}{5}=12$.

> [!exemple] Exemple 2 — calculer un pourcentage
> 20% de 45 : $\dfrac{20}{100}\times 45 = 9$.

> [!exemple] Exemple 3 — coefficient multiplicateur
> Une réduction de 15% sur 40 € : nouveau prix $=40\times(1-0,15)=40\times0,85=34$ €.

> [!methode] Méthode — `PUI` Puissances de 10 et écriture scientifique
> $10^n$ s'écrit 1 suivi de $n$ zéros ; $10^{-n} = \dfrac{1}{10^n}$. Un nombre en écriture scientifique s'écrit $a \times 10^n$ avec $1 \le a < 10$.

> [!exemple] Exemple 1 — produit et quotient de puissances de 10
> $$10^3\times10^2=10^5=100\,000 \qquad \dfrac{10^5}{10^2}=10^3=1\,000$$

> [!exemple] Exemple 2 — écriture scientifique d'un grand nombre
> $$3\,400 = 3,4 \times 10^3$$

> [!exemple] Exemple 3 — écriture scientifique d'un petit nombre
> $$0,00056 = 5,6\times 10^{-4}$$

> [!methode] Méthode — `CONV` Conversions usuelles
> Longueurs : $1\text{ m} = 100\text{ cm} = 1\,000\text{ mm}$. Aires : $1\text{ m}^2=10\,000\text{ cm}^2$. Volumes : $1\text{ m}^3 = 1\,000\text{ L}$, $1\text{ L}=1\text{ dm}^3$. Durées : $1\text{ h}=60\text{ min}=3\,600\text{ s}$.

> [!exemple] Exemple 1 — aire
> $$2,5 \text{ m}^2 = 25\,000 \text{ cm}^2$$

> [!exemple] Exemple 2 — volume et capacité
> $$3 \text{ L} = 3 \text{ dm}^3 = 3\,000 \text{ cm}^3$$

> [!exemple] Exemple 3 — durée
> $$1\text{ h}\,30\text{min} = 1,5 \text{ h} \qquad \text{(car } 30\text{ min}=0,5\text{ h)}$$

> [!methode] Méthode — `AP` Aires et périmètres usuels
> $$\mathcal{A}_{rectangle}=L\times l \qquad \mathcal{A}_{triangle}=\dfrac{b\times h}{2} \qquad \mathcal{A}_{disque}=\pi r^2 \qquad \mathcal{P}_{cercle}=2\pi r$$

> [!exemple] Exemple 1 — rectangle
> Longueur 6 cm, largeur 4 cm : aire $=6\times4=24$ cm², périmètre $=2\times(6+4)=20$ cm.

> [!exemple] Exemple 2 — triangle
> Base 8 cm, hauteur 5 cm : aire $=\dfrac{8\times5}{2}=20$ cm².

> [!exemple] Exemple 3 — disque
> Rayon 3 cm : aire $=\pi\times3^2=9\pi$ cm² (valeur exacte), périmètre $=2\pi\times3=6\pi$ cm (valeur exacte).

> [!methode] Méthode — `LEC` Lire un graphique ou un tableau
> Sur un graphique, un point est repéré par ses coordonnées $(x\,;y)$ : $x$ est l'abscisse (lue horizontalement), $y$ est l'ordonnée (lue verticalement). Dans une série statistique, la moyenne est la somme des valeurs divisée par leur effectif total, et l'étendue est la différence entre la plus grande et la plus petite valeur.

> [!exemple] Exemple 1 — coordonnées d'un point
> Un point situé à l'abscisse 3 et à l'ordonnée 7 a pour coordonnées $(3\,;7)$.

> [!exemple] Exemple 2 — moyenne
> Moyenne de $4$, $6$ et $8$ : $\dfrac{4+6+8}{3}=\dfrac{18}{3}=6$.

> [!exemple] Exemple 3 — étendue
> Étendue de la série $2, 9, 4, 15$ : $15-2=13$.

> [!remarque] Remarque
> La lecture de graphiques utilisant la notation $f(x)$ (image, antécédent) sera formalisée au chapitre 8 — elle apparaîtra dans les fiches à partir de la semaine 15.

## Fiches hebdomadaires

### Semaine 1

> [!exercice] Semaine 1 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $12 + 8 \times 5$
> 2. `CM` Calculer : $(7-3)\times(9-5)$
> 3. `FR` Calculer et simplifier : $\dfrac{1}{4}+\dfrac{1}{2}$
> 4. `FR` Calculer : $\dfrac{5}{6}-\dfrac{1}{3}$
> 5. `REL` Calculer : $(-8)+5$
> 6. `REL` Calculer : $(-4)\times(-6)$
> 7. `PROP` Dans un tableau de proportionnalité, une colonne est $(4\,;9)$ et une autre $(x\,;27)$. Trouver $x$.
> 8. `PUI` Écrire $10^4 \times 10^{-2}$ sous la forme $10^n$.
> 9. `CONV` Convertir $3,2$ m en cm.
> 10. `AP` Calculer le périmètre d'un rectangle de longueur 7 cm et de largeur 4 cm.

#### Corrigé — Semaine 1 — Fiche A
1. $12+40=52$
2. $4\times4=16$
3. $\frac{1}{4}+\frac{2}{4}=\frac{3}{4}$
4. $\frac{5}{6}-\frac{2}{6}=\frac{3}{6}=\frac{1}{2}$
5. $-3$
6. $24$
7. $x\times 9 = 4\times 27=108$ donc $x=12$
8. $10^{4-2}=10^2$
9. $320$ cm
10. $2\times(7+4)=22$ cm

> [!exercice] Semaine 1 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $9 + 6 \times 7$
> 2. `CM` Calculer : $(10-4)\times(8-5)$
> 3. `FR` Calculer et simplifier : $\dfrac{1}{3}+\dfrac{1}{6}$
> 4. `FR` Calculer : $\dfrac{3}{4}-\dfrac{1}{2}$
> 5. `REL` Calculer : $(-9)+4$
> 6. `REL` Calculer : $(-3)\times(-7)$
> 7. `PROP` Dans un tableau de proportionnalité, une colonne est $(3\,;8)$ et une autre $(x\,;24)$. Trouver $x$.
> 8. `PUI` Écrire $10^3 \times 10^{-1}$ sous la forme $10^n$.
> 9. `CONV` Convertir $2,7$ m en cm.
> 10. `AP` Calculer le périmètre d'un rectangle de longueur 9 cm et de largeur 5 cm.

#### Corrigé — Semaine 1 — Fiche B
1. $9+42=51$
2. $6\times3=18$
3. $\frac{2}{6}+\frac{1}{6}=\frac{3}{6}=\frac{1}{2}$
4. $\frac{3}{4}-\frac{2}{4}=\frac{1}{4}$
5. $-5$
6. $21$
7. $x\times8=3\times24=72$ donc $x=9$
8. $10^{3-1}=10^2$
9. $270$ cm
10. $2\times(9+5)=28$ cm

### Semaine 2

> [!exercice] Semaine 2 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $20 - 3 \times 4$
> 2. `CM` Calculer : $15 \times 2 - 6 \div 2$
> 3. `FR` Calculer : $\dfrac{2}{5}+\dfrac{3}{10}$
> 4. `REL` Calculer : $(-12)-(-7)$
> 5. `REL` Calculer : $(-24) \div 6$
> 6. `PROP` Une recette pour 4 personnes utilise 250 g de farine. Combien de farine pour 6 personnes ?
> 7. `PUI` Écrire $45\,000$ en écriture scientifique.
> 8. `CONV` Convertir $2,5$ L en cm³.
> 9. `AP` Calculer l'aire d'un triangle de base 8 cm et de hauteur 5 cm.
> 10. `LEC` Sur un graphique, un point a pour coordonnées $(3\,;7)$. Donner son abscisse puis son ordonnée.

#### Corrigé — Semaine 2 — Fiche A
1. $20-12=8$
2. $30-3=27$
3. $\frac{4}{10}+\frac{3}{10}=\frac{7}{10}$
4. $-12+7=-5$
5. $-4$
6. $\dfrac{250\times 6}{4}=375$ g
7. $4,5\times 10^4$
8. $2,5\times1000=2\,500$ cm³
9. $\dfrac{8\times5}{2}=20$ cm²
10. Abscisse : 3 ; ordonnée : 7

> [!exercice] Semaine 2 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $18-2\times5$
> 2. `CM` Calculer : $12\times3-8\div4$
> 3. `FR` Calculer : $\dfrac{3}{8}+\dfrac{1}{4}$
> 4. `REL` Calculer : $(-9)-(-4)$
> 5. `REL` Calculer : $(-36)\div9$
> 6. `PROP` Une recette pour 3 personnes utilise 180 g de sucre. Combien pour 5 personnes ?
> 7. `PUI` Écrire $7\,200$ en écriture scientifique.
> 8. `CONV` Convertir $1,8$ L en cm³.
> 9. `AP` Calculer l'aire d'un triangle de base 10 cm et de hauteur 6 cm.
> 10. `LEC` Un tableau de proportionnalité donne les couples $(1\,;4)$, $(2\,;8)$, $(3\,;12)$. Quel nombre correspond à 5 dans ce tableau ?

#### Corrigé — Semaine 2 — Fiche B
1. $18-10=8$
2. $36-2=34$
3. $\frac{3}{8}+\frac{2}{8}=\frac{5}{8}$
4. $-9+4=-5$
5. $-4$
6. $\dfrac{180\times5}{3}=300$ g
7. $7,2\times10^3$
8. $1\,800$ cm³
9. $\dfrac{10\times6}{2}=30$ cm²
10. Le coefficient est $4$ (car $4\div1=4$), donc $5\times4=20$ correspond à 5.

### Semaine 3

> [!exercice] Semaine 3 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $6^2 - 4 \times 5$
> 2. `FR` Calculer : $2 - \dfrac{3}{4}$
> 3. `REL` Calculer : $(-5)^2$
> 4. `PROP` 60 est augmenté de 20%. Quelle est la nouvelle valeur ?
> 5. `Ch1` Calculer la valeur de $A = 3x-5$ pour $x=-2$.
> 6. `Ch1` Calculer la valeur de $B=2x^2+1$ pour $x=3$.
> 7. `CONV` Convertir 1h15min en minutes.
> 8. `AP` Calculer l'aire d'un disque de rayon 3 cm (valeur exacte).
> 9. `PUI` Écrire $2^3 \times 2^2$ sous la forme d'une seule puissance de 2, puis calculer sa valeur.
> 10. `LEC` Calculer l'étendue de la série suivante : 4, 9, 2, 15, 7.

#### Corrigé — Semaine 3 — Fiche A
1. $36-20=16$
2. $\frac{8}{4}-\frac{3}{4}=\frac{5}{4}$
3. $25$
4. $60\times 1,2=72$
5. $3\times(-2)-5=-6-5=-11$
6. $2\times 9+1=19$
7. $75$ min
8. $\pi\times 3^2=9\pi$ cm²
9. $2^{3+2}=2^5=32$
10. Étendue $=15-2=13$ (valeur maximale moins valeur minimale)

> [!exercice] Semaine 3 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $5^2-3\times6$
> 2. `FR` Calculer : $3 - \dfrac{2}{5}$
> 3. `REL` Calculer : $(-4)^2$
> 4. `PROP` 50 est augmenté de 10%. Quelle est la nouvelle valeur ?
> 5. `Ch1` Calculer la valeur de $A=4x-3$ pour $x=-1$.
> 6. `Ch1` Calculer la valeur de $B=3x^2-2$ pour $x=2$.
> 7. `CONV` Convertir 2h30min en minutes.
> 8. `AP` Calculer l'aire d'un disque de rayon 2 cm (valeur exacte).
> 9. `PUI` Calculer $3^2\times3^3$ sous la forme d'une seule puissance de 3, puis calculer sa valeur.
> 10. `LEC` Un tableau donne le nombre de tickets vendus chaque jour : lundi 12, mardi 15, mercredi 9, jeudi 20, vendredi 14. Quel jour a-t-on vendu le plus de tickets ?

#### Corrigé — Semaine 3 — Fiche B
1. $25-18=7$
2. $\frac{15}{5}-\frac{2}{5}=\frac{13}{5}$
3. $16$
4. $50\times1,1=55$
5. $4\times(-1)-3=-7$
6. $3\times4-2=10$
7. $150$ min
8. $\pi\times2^2=4\pi$ cm²
9. $3^{2+3}=3^5=243$
10. Jeudi, avec 20 tickets vendus (c'est le maximum de la série).

### Semaine 4

> [!exercice] Semaine 4 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $(2+3)^2 - 10$
> 2. `FR` Calculer et simplifier : $\dfrac{3}{5} \times \dfrac{10}{9}$
> 3. `REL` Calculer : $5-12+3$
> 4. `Ch1` Tester si $x=2$ est solution de l'égalité $3x+1=2x+3$.
> 5. `PROP` Sur une carte à l'échelle 1/25 000, une distance mesure 4 cm. Quelle est la distance réelle, en km ?
> 6. `PUI` Calculer $\dfrac{10^5}{10^2}$.
> 7. `CONV` Convertir 3 500 cm² en m².
> 8. `AP` Calculer l'aire d'un carré de côté 9 cm.
> 9. `LEC` Lire (calculer) la moyenne de la série : 4, 6, 8, 10, 12.
> 10. `CM` Calculer : $100 - 5^2 \times 3$

#### Corrigé — Semaine 4 — Fiche A
1. $25-10=15$
2. $\frac{30}{45}=\frac{2}{3}$
3. $-4$
4. $3\times2+1=7$ et $2\times2+3=7$ : les deux membres sont égaux, donc $x=2$ est bien solution.
5. $4\times 25\,000=100\,000$ cm $=1\,000$ m $=1$ km
6. $10^{5-2}=10^3=1\,000$
7. $3\,500$ cm² $=0,35$ m²
8. $81$ cm²
9. $\dfrac{4+6+8+10+12}{5}=\dfrac{40}{5}=8$
10. $100-75=25$

> [!exercice] Semaine 4 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $(4+1)^2-8$
> 2. `FR` Calculer et simplifier : $\dfrac{2}{3}\times\dfrac{9}{4}$
> 3. `REL` Calculer : $7-15+2$
> 4. `Ch1` Tester si $x=3$ est solution de l'égalité $2x+1=3x-2$.
> 5. `PROP` Sur une carte à l'échelle 1/10 000, une distance mesure 5 cm. Quelle est la distance réelle, en km ?
> 6. `PUI` Calculer $\dfrac{10^6}{10^3}$.
> 7. `CONV` Convertir 2 800 cm² en m².
> 8. `AP` Calculer l'aire d'un carré de côté 7 cm.
> 9. `LEC` Calculer la moyenne de la série : 5, 7, 9, 11, 13.
> 10. `CM` Calculer : $80-4^2\times2$

#### Corrigé — Semaine 4 — Fiche B
1. $25-8=17$
2. $\frac{18}{12}=\frac{3}{2}$
3. $-6$
4. $2\times3+1=7$ et $3\times3-2=7$ : les deux membres sont égaux, donc $x=3$ est bien solution.
5. $5\times10\,000=50\,000$ cm $=500$ m $=0,5$ km
6. $10^{6-3}=10^3=1\,000$
7. $2\,800$ cm² $=0,28$ m²
8. $49$ cm²
9. $\dfrac{5+7+9+11+13}{5}=\dfrac{45}{5}=9$
10. $80-32=48$

### Semaine 5

> [!exercice] Semaine 5 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $30 \div 5 + 2 \times 6$
> 2. `FR` Calculer : $\dfrac{5}{8}-\dfrac{1}{4}$
> 3. `REL` Calculer : $(-3)\times 4 - 7$
> 4. `Ch1` Développer : $3(x+4)$
> 5. `Ch2` Un triangle rectangle a pour côtés de l'angle droit 6 cm et 8 cm. Calculer la longueur de son hypoténuse.
> 6. `Ch2` $(AB) \parallel (CD)$ et $(CD)\perp \mathcal{D}$. Que peut-on dire de $(AB)$ et $\mathcal{D}$ ?
> 7. `PROP` Un article à 80 € subit une réduction de 15%. Calculer le prix final.
> 8. `CONV` Convertir 0,75 m³ en L.
> 9. `AP` Calculer le périmètre d'un cercle de rayon 5 cm (valeur exacte).
> 10. `PUI` Écrire $0,00072$ en écriture scientifique.

#### Corrigé — Semaine 5 — Fiche A
1. $6+12=18$
2. $\frac{5}{8}-\frac{2}{8}=\frac{3}{8}$
3. $-12-7=-19$
4. $3x+12$
5. $\sqrt{6^2+8^2}=\sqrt{100}=10$ cm
6. $(AB)\perp \mathcal{D}$ (une droite perpendiculaire à l'une de deux droites parallèles est perpendiculaire à l'autre)
7. $80\times 0,85=68$ €
8. $750$ L
9. $2\pi\times5=10\pi$ cm
10. $7,2\times10^{-4}$

> [!exercice] Semaine 5 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $40\div8+3\times5$
> 2. `FR` Calculer : $\dfrac{7}{10}-\dfrac{1}{5}$
> 3. `REL` Calculer : $(-5)\times3-4$
> 4. `Ch1` Développer : $4(x+2)$
> 5. `Ch2` Un triangle rectangle a pour côtés de l'angle droit 9 cm et 12 cm. Calculer la longueur de son hypoténuse.
> 6. `Ch2` $(AB)\perp(CD)$ et $(CD) \parallel \mathcal{D}$. Que peut-on dire de $(AB)$ et $\mathcal{D}$ ?
> 7. `PROP` Un article à 60 € subit une réduction de 25%. Calculer le prix final.
> 8. `CONV` Convertir 0,3 m³ en L.
> 9. `AP` Calculer le périmètre d'un cercle de rayon 8 cm (valeur exacte).
> 10. `PUI` Écrire $0,00035$ en écriture scientifique.

#### Corrigé — Semaine 5 — Fiche B
1. $5+15=20$
2. $\frac{7}{10}-\frac{2}{10}=\frac{5}{10}=\frac{1}{2}$
3. $-15-4=-19$
4. $4x+8$
5. $\sqrt{9^2+12^2}=\sqrt{81+144}=\sqrt{225}=15$ cm
6. $(AB)\perp\mathcal{D}$ (une droite perpendiculaire à l'une de deux droites parallèles est perpendiculaire à l'autre)
7. $60\times0,75=45$ €
8. $300$ L
9. $2\pi\times8=16\pi$ cm
10. $3,5\times10^{-4}$

### Semaine 6

> [!exercice] Semaine 6 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $8 \times 7 - 3^2$
> 2. `FR` Calculer et simplifier : $\dfrac{7}{9}-\dfrac{2}{9}$
> 3. `REL` Calculer : $(-15) + (-6)$
> 4. `Ch1` Développer et réduire : $2x+3(x-1)$
> 5. `Ch2` Le triangle $RST$ est tel que $RS=5$, $ST=12$, $RT=13$. Est-il rectangle ? Justifier.
> 6. `Ch2` $[AB]$ est un diamètre d'un cercle et $C$ est un point du cercle distinct de $A$ et $B$. Quelle est la nature du triangle $ABC$ ?
> 7. `PROP` Quel est le coefficient de proportionnalité entre 5 et 35 ?
> 8. `CONV` Convertir 4 200 m en km.
> 9. `AP` Calculer l'aire d'un disque de diamètre 10 cm (valeur exacte).
> 10. `LEC` Un tableau donne les notes 12, 14, 9, 15, 10. Calculer la moyenne.

#### Corrigé — Semaine 6 — Fiche A
1. $56-9=47$
2. $\frac{5}{9}$
3. $-21$
4. $2x+3x-3=5x-3$
5. Le plus grand côté est $RT=13$. $RS^2+ST^2=25+144=169=13^2=RT^2$, donc d'après la réciproque du théorème de Pythagore, le triangle est rectangle en $S$.
6. $ABC$ est rectangle en $C$ (triangle inscrit dans un demi-cercle).
7. $35\div 5=7$
8. $4\,200$ m $=4,2$ km
9. Rayon $=5$ cm, aire $=\pi\times 5^2=25\pi$ cm²
10. $\dfrac{12+14+9+15+10}{5}=\dfrac{60}{5}=12$

> [!exercice] Semaine 6 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $9\times5-4^2$
> 2. `FR` Calculer et simplifier : $\dfrac{8}{10}-\dfrac{3}{10}$
> 3. `REL` Calculer : $(-11)+(-9)$
> 4. `Ch1` Développer et réduire : $3x+2(x-4)$
> 5. `Ch2` Le triangle $KLM$ est tel que $KL=9$, $LM=12$, $KM=15$. Est-il rectangle ? Justifier.
> 6. `Ch2` $[EF]$ est un diamètre d'un cercle et $G$ un point du cercle distinct de $E$ et $F$. Quelle est la nature du triangle $EFG$ ?
> 7. `PROP` Quel est le coefficient de proportionnalité entre 6 et 42 ?
> 8. `CONV` Convertir 3 700 m en km.
> 9. `AP` Calculer l'aire d'un disque de diamètre 8 cm (valeur exacte).
> 10. `LEC` Un tableau donne les notes 11, 13, 15, 9, 12. Calculer la moyenne.

#### Corrigé — Semaine 6 — Fiche B
1. $45-16=29$
2. $\frac{5}{10}=\frac{1}{2}$
3. $-20$
4. $3x+2x-8=5x-8$
5. Le plus grand côté est $KM=15$. $KL^2+LM^2=81+144=225=15^2=KM^2$, donc le triangle est rectangle en $L$.
6. $EFG$ est rectangle en $G$ (triangle inscrit dans un demi-cercle).
7. $42\div6=7$
8. $3\,700$ m $=3,7$ km
9. Rayon $=4$ cm, aire $=\pi\times4^2=16\pi$ cm²
10. $\dfrac{11+13+15+9+12}{5}=\dfrac{60}{5}=12$

### Semaine 7

> [!exercice] Semaine 7 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $50 - 2 \times (6+3)$
> 2. `FR` Calculer : $\dfrac{3}{4} \div \dfrac{1}{2}$
> 3. `REL` Calculer : $(-2)^3$
> 4. `Ch1` Calculer la valeur de $C=(x+2)^2$ pour $x=1$.
> 5. `Ch2` Deux droites sont perpendiculaires à une même troisième droite. Que peut-on en conclure ?
> 6. `Ch3` Développer : $-4(2x-3)$
> 7. `Ch3` Développer : $(x+2)(x-5)$
> 8. `PROP` 15 élèves sur 25 dans une classe sont des filles. Quel est le pourcentage de filles ?
> 9. `CONV` Convertir 2h 6min en heures décimales.
> 10. `AP` Calculer le périmètre d'un triangle équilatéral de côté 6 cm.

#### Corrigé — Semaine 7 — Fiche A
1. $50-18=32$
2. $\frac{3}{4}\times\frac{2}{1}=\frac{6}{4}=\frac{3}{2}$
3. $-8$
4. $(1+2)^2=9$
5. Elles sont parallèles entre elles.
6. $-8x+12$
7. $x^2-5x+2x-10=x^2-3x-10$
8. $\dfrac{15}{25}\times100=60\%$
9. $6$ min $=0,1$ h donc $2,1$ h
10. $3\times6=18$ cm

> [!exercice] Semaine 7 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $60-3\times(5+2)$
> 2. `FR` Calculer : $\dfrac{5}{6} \div \dfrac{1}{3}$
> 3. `REL` Calculer : $(-3)^3$
> 4. `Ch1` Calculer la valeur de $D=(x-3)^2$ pour $x=5$.
> 5. `Ch2` Deux droites sont parallèles à une même troisième droite. Que peut-on en conclure ?
> 6. `Ch3` Développer : $-5(3x-2)$
> 7. `Ch3` Développer : $(x+4)(x-3)$
> 8. `PROP` 18 élèves sur 30 sont des garçons. Quel est le pourcentage de garçons ?
> 9. `CONV` Convertir 1h 48min en heures décimales.
> 10. `AP` Calculer le périmètre d'un triangle équilatéral de côté 9 cm.

#### Corrigé — Semaine 7 — Fiche B
1. $60-21=39$
2. $\frac{5}{6}\times\frac{3}{1}=\frac{15}{6}=\frac{5}{2}$
3. $-27$
4. $(5-3)^2=4$
5. Elles sont parallèles entre elles.
6. $-15x+10$
7. $x^2-3x+4x-12=x^2+x-12$
8. $\dfrac{18}{30}\times100=60\%$
9. $48$ min $=0,8$ h donc $1,8$ h
10. $3\times9=27$ cm

### Semaine 8

> [!exercice] Semaine 8 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $7^2 - 3\times 8$
> 2. `FR` Calculer : $\dfrac{1}{6}+\dfrac{1}{3}-\dfrac{1}{2}$
> 3. `REL` Calculer : $(-9) \times (+3)$
> 4. `Ch2` Calculer $AC$ dans un triangle $ABC$ rectangle en $B$ avec $AB=9$ et $BC=12$.
> 5. `Ch3` Développer et réduire : $5x-2(3x-1)$
> 6. `Ch3` Développer à l'aide d'une identité remarquable : $(x+3)^2$
> 7. `PUI` Écrire sous la forme d'une seule puissance de 10 : $\dfrac{10^{-2}\times 10^5}{10}$
> 8. `CONV` Convertir 0,4 kg en g.
> 9. `AP` Calculer l'aire d'un rectangle de longueur 12 cm et de largeur 5 cm.
> 10. `LEC` Calculer l'étendue de la série suivante : 18, 5, 22, 11, 9.

#### Corrigé — Semaine 8 — Fiche A
1. $49-24=25$
2. $\frac{1}{6}+\frac{2}{6}-\frac{3}{6}=\frac{0}{6}=0$
3. $-27$
4. $AC=\sqrt{9^2+12^2}=\sqrt{81+144}=\sqrt{225}=15$
5. $5x-6x+2=-x+2$
6. $x^2+6x+9$
7. $10^{-2+5-1}=10^2=100$
8. $400$ g
9. $60$ cm²
10. Étendue $=22-5=17$

> [!exercice] Semaine 8 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $6^2-2\times9$
> 2. `FR` Calculer : $\dfrac{1}{4}+\dfrac{1}{2}-\dfrac{1}{8}$
> 3. `REL` Calculer : $(-7)\times(+5)$
> 4. `Ch2` Calculer $BC$ dans un triangle $ABC$ rectangle en $A$ avec $AB=8$ et $AC=15$.
> 5. `Ch3` Développer et réduire : $4x-3(2x+1)$
> 6. `Ch3` Développer à l'aide d'une identité remarquable : $(x-5)^2$
> 7. `PUI` Écrire sous la forme d'une seule puissance de 10 : $\dfrac{10^4\times10^{-1}}{10^2}$
> 8. `CONV` Convertir 0,6 kg en g.
> 9. `AP` Calculer l'aire d'un rectangle de longueur 8 cm et de largeur 6 cm.
> 10. `LEC` Sur un graphique, un point a pour coordonnées $(6\,;-3)$. Donner son abscisse puis son ordonnée.

#### Corrigé — Semaine 8 — Fiche B
1. $36-18=18$
2. $\frac{2}{8}+\frac{4}{8}-\frac{1}{8}=\frac{5}{8}$
3. $-35$
4. $BC=\sqrt{8^2+15^2}=\sqrt{64+225}=\sqrt{289}=17$
5. $4x-6x-3=-2x-3$
6. $x^2-10x+25$
7. $10^{4-1-2}=10^1=10$
8. $600$ g
9. $48$ cm²
10. Abscisse : 6 ; ordonnée : $-3$

### Semaine 9

> [!exercice] Semaine 9 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $9 \times 6 - 4^2$
> 2. `FR` Calculer : $\dfrac{4}{5} - \dfrac{1}{10}$
> 3. `REL` Calculer : $(-6)+(-2)\times 3$
> 4. `Ch1` Développer et réduire : $4(x-2)+3x$
> 5. `Ch3` Développer : $(2x-1)(x+3)$
> 6. `Ch4` 63 est-il divisible par 9 ? Justifier à l'aide du critère de divisibilité.
> 7. `Ch4` Calculer PGCD(18, 24) en listant les diviseurs.
> 8. `PROP` Un coefficient multiplicateur de 0,92 correspond à quelle évolution en pourcentage ?
> 9. `CONV` Convertir 5 dm³ en L.
> 10. `AP` Calculer l'aire d'un triangle rectangle dont les côtés de l'angle droit mesurent 6 cm et 10 cm.

#### Corrigé — Semaine 9 — Fiche A
1. $54-16=38$
2. $\frac{8}{10}-\frac{1}{10}=\frac{7}{10}$
3. $-6-6=-12$
4. $4x-8+3x=7x-8$
5. $2x^2+6x-x-3=2x^2+5x-3$
6. $6+3=9$, et 9 est divisible par 9, donc 63 est divisible par 9.
7. Diviseurs de 18 : 1, 2, 3, 6, 9, 18. Diviseurs de 24 : 1, 2, 3, 4, 6, 8, 12, 24. Diviseurs communs : 1, 2, 3, 6 → PGCD $=6$.
8. $0,92=1-0,08$ : c'est une **baisse de 8%**.
9. $5$ dm³ $=5$ L
10. $\dfrac{6\times10}{2}=30$ cm²

> [!exercice] Semaine 9 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $8\times5-3^2$
> 2. `FR` Calculer : $\dfrac{3}{4}-\dfrac{1}{8}$
> 3. `REL` Calculer : $(-4)+(-3)\times2$
> 4. `Ch1` Développer et réduire : $5(x-1)+2x$
> 5. `Ch3` Développer : $(3x-2)(x+4)$
> 6. `Ch4` 84 est-il divisible par 3 ? Justifier à l'aide du critère de divisibilité.
> 7. `Ch4` Calculer PGCD(30, 45) en listant les diviseurs.
> 8. `PROP` Un coefficient multiplicateur de 1,08 correspond à quelle évolution en pourcentage ?
> 9. `CONV` Convertir 8 dm³ en L.
> 10. `AP` Calculer l'aire d'un triangle rectangle dont les côtés de l'angle droit mesurent 5 cm et 12 cm.

#### Corrigé — Semaine 9 — Fiche B
1. $40-9=31$
2. $\frac{6}{8}-\frac{1}{8}=\frac{5}{8}$
3. $-4-6=-10$
4. $5x-5+2x=7x-5$
5. $3x^2+12x-2x-8=3x^2+10x-8$
6. $8+4=12$, et 12 est divisible par 3, donc 84 est divisible par 3.
7. Diviseurs de 30 : 1, 2, 3, 5, 6, 10, 15, 30. Diviseurs de 45 : 1, 3, 5, 9, 15, 45. Diviseurs communs : 1, 3, 5, 15 → PGCD $=15$.
8. $1,08=1+0,08$ : c'est une **hausse de 8%**.
9. $8$ dm³ $=8$ L
10. $\dfrac{5\times12}{2}=30$ cm²

### Semaine 10

> [!exercice] Semaine 10 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $(15-7)\times 3 + 2$
> 2. `FR` Calculer et simplifier : $\dfrac{9}{4}-\dfrac{1}{4}$
> 3. `REL` Calculer : $8 - (-3) - 5$
> 4. `Ch2` $M$ est le milieu de $[AB]$. Que peut-on dire de $AM$ et $MB$ ?
> 5. `Ch3` Développer à l'aide d'une identité remarquable : $(3x-2)(3x+2)$
> 6. `Ch4` 84 est-il un multiple de 7 ?
> 7. `Ch4` Décomposer 60 en produit de facteurs premiers.
> 8. `PUI` Calculer $(10^2)^3$.
> 9. `CONV` Convertir 1,5 h en minutes.
> 10. `LEC` La médiane d'une série de 5 valeurs rangées dans l'ordre est la valeur du milieu. Trouver la médiane de 3, 7, 8, 12, 20.

#### Corrigé — Semaine 10 — Fiche A
1. $8\times3+2=26$
2. $\frac{9}{4}-\frac{1}{4}=\frac{8}{4}=2$
3. $8+3-5=6$
4. $AM=MB$
5. $9x^2-4$
6. $84 \div 7 = 12$, donc oui, 84 est un multiple de 7.
7. $60 = 2^2 \times 3 \times 5$
8. $10^6=1\,000\,000$
9. $90$ min
10. Médiane $=8$

> [!exercice] Semaine 10 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $(20-6)\times2+3$
> 2. `FR` Calculer et simplifier : $\dfrac{7}{3}-\dfrac{1}{3}$
> 3. `REL` Calculer : $9-(-4)-6$
> 4. `Ch2` $N$ est le milieu de $[PQ]$. Que peut-on dire de $PN$ et $NQ$ ?
> 5. `Ch3` Développer à l'aide d'une identité remarquable : $(5x-1)(5x+1)$
> 6. `Ch4` 96 est-il un multiple de 8 ?
> 7. `Ch4` Décomposer 84 en produit de facteurs premiers.
> 8. `PUI` Calculer $(10^3)^2$.
> 9. `CONV` Convertir 2,25 h en minutes.
> 10. `LEC` La médiane d'une série de 5 valeurs rangées dans l'ordre est la valeur du milieu. Trouver la médiane de 2, 5, 9, 14, 21.

#### Corrigé — Semaine 10 — Fiche B
1. $14\times2+3=31$
2. $\frac{7}{3}-\frac{1}{3}=\frac{6}{3}=2$
3. $9+4-6=7$
4. $PN=NQ$
5. $25x^2-1$
6. $96\div8=12$, donc oui, 96 est un multiple de 8.
7. $84=2^2\times3\times7$
8. $10^6=1\,000\,000$
9. $135$ min
10. Médiane $=9$

### Semaine 11

> [!exercice] Semaine 11 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $4^2 + 3 \times (7-4)$
> 2. `FR` Calculer : $\dfrac{5}{12}+\dfrac{1}{4}$
> 3. `REL` Calculer : $(-7)-(-2)+(-5)$
> 4. `Ch3` Développer à l'aide d'une identité remarquable : $(x-4)^2$
> 5. `Ch4` Calculer PGCD(45, 60) par décomposition en facteurs premiers.
> 6. `Ch5` Un cycliste parcourt 30 km en 1h15min. Calculer sa vitesse moyenne, en km/h.
> 7. `Ch5` Un article coûte 45 € après une augmentation de 20%. Quel était son prix initial ?
> 8. `PUI` Écrire $56\,000\,000$ en écriture scientifique.
> 9. `CONV` Convertir 90 km/h en m/s.
> 10. `AP` Calculer l'aire d'un triangle de base 14 cm et de hauteur 6 cm.

#### Corrigé — Semaine 11 — Fiche A
1. $16+9=25$
2. $\frac{5}{12}+\frac{3}{12}=\frac{8}{12}=\frac{2}{3}$
3. $-7+2-5=-10$
4. $x^2-8x+16$
5. $45=3^2\times5$, $60=2^2\times3\times5$ → PGCD $=3\times5=15$
6. $t=1,25$ h ; $v=\dfrac{30}{1,25}=24$ km/h
7. $PI\times1,2=45$ donc $PI=\dfrac{45}{1,2}=37,5$ €
8. $5,6\times10^7$
9. $90$ km/h $=\dfrac{90\,000}{3\,600}=25$ m/s
10. $\dfrac{14\times6}{2}=42$ cm²

> [!exercice] Semaine 11 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $3^2+4\times(9-6)$
> 2. `FR` Calculer : $\dfrac{7}{18}+\dfrac{1}{6}$
> 3. `REL` Calculer : $(-9)-(-3)+(-6)$
> 4. `Ch3` Développer à l'aide d'une identité remarquable : $(x+5)^2$
> 5. `Ch4` Calculer PGCD(36, 54) par décomposition en facteurs premiers.
> 6. `Ch5` Un coureur parcourt 21 km en 1h45min. Calculer sa vitesse moyenne, en km/h.
> 7. `Ch5` Un article coûte 56 € après une réduction de 20%. Quel était son prix initial ?
> 8. `PUI` Écrire $8\,300\,000$ en écriture scientifique.
> 9. `CONV` Convertir 72 km/h en m/s.
> 10. `AP` Calculer l'aire d'un triangle de base 12 cm et de hauteur 5 cm.

#### Corrigé — Semaine 11 — Fiche B
1. $9+12=21$
2. $\frac{7}{18}+\frac{3}{18}=\frac{10}{18}=\frac{5}{9}$
3. $-9+3-6=-12$
4. $x^2+10x+25$
5. $36=2^2\times3^2$, $54=2\times3^3$ → PGCD $=2\times3^2=18$
6. $t=1,75$ h ; $v=\dfrac{21}{1,75}=12$ km/h
7. $PI\times0,8=56$ donc $PI=\dfrac{56}{0,8}=70$ €
8. $8,3\times10^6$
9. $72$ km/h $=\dfrac{72\,000}{3\,600}=20$ m/s
10. $\dfrac{12\times5}{2}=30$ cm²

### Semaine 12

> [!exercice] Semaine 12 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $6 \times (9-5) - 2^3$
> 2. `FR` Calculer et simplifier : $\dfrac{2}{3} \times \dfrac{3}{8}$
> 3. `REL` Calculer : $(-4)^2 - (-3)^2$
> 4. `Ch2` $ABCD$ est un parallélogramme. Que peut-on dire des droites $(AB)$ et $(CD)$ ?
> 5. `Ch5` Convertir une vitesse de 20 m/s en km/h.
> 6. `Ch6` Factoriser : $5x-15$
> 7. `Ch6` Factoriser à l'aide d'une identité remarquable : $x^2-49$
> 8. `PROP` Vérifier que 4,8 est proportionnel à 12 avec un coefficient 0,4.
> 9. `CONV` Convertir 2,3 t en kg.
> 10. `LEC` Une droite passe par les points $(0\,;3)$ et $(2\,;7)$. Donner l'ordonnée du point d'abscisse 0.

#### Corrigé — Semaine 12 — Fiche A
1. $6\times4-8=24-8=16$
2. $\frac{6}{24}=\frac{1}{4}$
3. $16-9=7$
4. $(AB) \parallel (CD)$
5. $20\times3,6=72$ km/h
6. $5(x-3)$
7. $(x-7)(x+7)$
8. $12\times0,4=4,8$ : c'est correct.
9. $2\,300$ kg
10. L'ordonnée du point d'abscisse 0 est 3 (c'est l'ordonnée à l'origine).

> [!exercice] Semaine 12 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $4\times(7-3)-2^3$
> 2. `FR` Calculer et simplifier : $\dfrac{5}{6}\times\dfrac{3}{10}$
> 3. `REL` Calculer : $(-5)^2-(-2)^2$
> 4. `Ch2` $EFGH$ est un parallélogramme. Que peut-on dire des droites $(EF)$ et $(GH)$ ?
> 5. `Ch5` Convertir une vitesse de 15 m/s en km/h.
> 6. `Ch6` Factoriser : $8x-24$
> 7. `Ch6` Factoriser à l'aide d'une identité remarquable : $x^2-81$
> 8. `PROP` Vérifier que 6,3 est proportionnel à 9 avec un coefficient 0,7.
> 9. `CONV` Convertir 1,8 t en kg.
> 10. `LEC` Une droite passe par les points $(0\,;-4)$ et $(3\,;5)$. Donner l'ordonnée du point d'abscisse 0.

#### Corrigé — Semaine 12 — Fiche B
1. $4\times4-8=8$
2. $\frac{15}{60}=\frac{1}{4}$
3. $25-4=21$
4. $(EF) \parallel (GH)$
5. $15\times3,6=54$ km/h
6. $8(x-3)$
7. $(x-9)(x+9)$
8. $9\times0,7=6,3$ : c'est correct.
9. $1\,800$ kg
10. L'ordonnée du point d'abscisse 0 est $-4$.

### Semaine 13

> [!exercice] Semaine 13 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $3^3 - 5 \times 4$
> 2. `FR` Calculer : $\dfrac{7}{10}-\dfrac{1}{5}$
> 3. `REL` Calculer : $(-2)\times(-3)\times(-1)$
> 4. `Ch1` Développer : $-2(x-5)$
> 5. `Ch3` Développer : $(4x+1)(2x-3)$
> 6. `Ch4` 91 est-il premier ? Justifier.
> 7. `Ch5` Une carte est à l'échelle 1/50 000. Une distance réelle de 3 km correspond à quelle distance sur la carte, en cm ?
> 8. `Ch6` Factoriser : $(x-3)(2x+1)-(x-3)$
> 9. `AP` Calculer le volume d'un pavé droit de dimensions 5 cm, 4 cm et 3 cm.
> 10. `LEC` Un diagramme en bâtons a un effectif total de 40 ; une valeur a un effectif de 8. Quelle est sa fréquence, en pourcentage ?

#### Corrigé — Semaine 13 — Fiche A
1. $27-20=7$
2. $\frac{7}{10}-\frac{2}{10}=\frac{5}{10}=\frac{1}{2}$
3. $(-2)\times(-3)\times(-1)=6\times(-1)=-6$
4. $-2x+10$
5. $8x^2-12x+2x-3=8x^2-10x-3$
6. $91=7\times13$, donc 91 n'est pas premier.
7. $3$ km $=300\,000$ cm ; distance carte $=\dfrac{300\,000}{50\,000}=6$ cm
8. $(x-3)\left[(2x+1)-1\right]=(x-3)\times2x=2x(x-3)$
9. $5\times4\times3=60$ cm³
10. $\dfrac{8}{40}\times100=20\%$

> [!exercice] Semaine 13 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $4^3-7\times5$
> 2. `FR` Calculer : $\dfrac{9}{10}-\dfrac{2}{5}$
> 3. `REL` Calculer : $(-1)\times(-1)\times(-4)$
> 4. `Ch1` Développer : $-3(x-4)$
> 5. `Ch3` Développer : $(2x+5)(x-2)$
> 6. `Ch4` 75 est-il premier ? Justifier.
> 7. `Ch5` Une carte est à l'échelle 1/20 000. Une distance réelle de 4 km correspond à quelle distance sur la carte, en cm ?
> 8. `Ch6` Factoriser : $(x+1)(3x-2)+(x+1)$
> 9. `AP` Calculer le volume d'un pavé droit de dimensions 6 cm, 4 cm et 2 cm.
> 10. `LEC` Un diagramme a un effectif total de 50 ; une valeur a un effectif de 15. Quelle est sa fréquence, en pourcentage ?

#### Corrigé — Semaine 13 — Fiche B
1. $64-35=29$
2. $\frac{9}{10}-\frac{4}{10}=\frac{5}{10}=\frac{1}{2}$
3. $(-1)\times(-1)\times(-4)=1\times(-4)=-4$
4. $-3x+12$
5. $2x^2-4x+5x-10=2x^2+x-10$
6. $75=3\times25=3\times5^2$, donc 75 n'est pas premier (divisible par 3 et par 5).
7. $4$ km $=400\,000$ cm ; distance carte $=\dfrac{400\,000}{20\,000}=20$ cm
8. $(x+1)\left[(3x-2)+1\right]=(x+1)(3x-1)$
9. $6\times4\times2=48$ cm³
10. $\dfrac{15}{50}\times100=30\%$

### Semaine 14

> [!exercice] Semaine 14 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $18 \div 3 + 4^2$
> 2. `FR` Calculer : $\dfrac{5}{6} \div \dfrac{5}{3}$
> 3. `REL` Calculer : $10 - 3 \times (-2)$
> 4. `Ch3` Développer : $(5-x)(2+x)$
> 5. `Ch6` Factoriser : $3x^2-12$ (attention, deux étapes sont nécessaires)
> 6. `Ch7` Dans le triangle $ABC$, $M\in[AB]$, $N\in[AC]$, $(MN)\parallel(BC)$, $AM=4$, $AB=10$, $AN=6$. Calculer $AC$.
> 7. `Ch7` Deux triangles semblables ont un rapport de similitude $k=2,5$. Un côté du petit triangle mesure 4 cm : quelle est la longueur du côté correspondant du grand triangle ?
> 8. `PROP` Un article passe de 120 € à 90 €. Calculer le taux d'évolution, en %.
> 9. `CONV` Convertir 3h 40min en minutes.
> 10. `AP` Calculer le périmètre d'un rectangle d'aire 48 cm² et de largeur 6 cm.

#### Corrigé — Semaine 14 — Fiche A
1. $6+16=22$
2. $\frac{5}{6}\times\frac{3}{5}=\frac{15}{30}=\frac{1}{2}$
3. $10+6=16$
4. $10+5x-2x-x^2=-x^2+3x+10$
5. $3x^2-12=3(x^2-4)=3(x-2)(x+2)$
6. $\dfrac{AC}{AN}=\dfrac{AB}{AM}$ donc $AC=\dfrac{AN\times AB}{AM}=\dfrac{6\times10}{4}=15$
7. $4\times2,5=10$ cm
8. $\dfrac{90-120}{120}\times100=-25\%$ : c'est une baisse de 25%.
9. $3\times60+40=220$ min
10. Longueur $=\dfrac{48}{6}=8$ cm, périmètre $=2\times(8+6)=28$ cm

> [!exercice] Semaine 14 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $24\div4+3^2$
> 2. `FR` Calculer : $\dfrac{7}{4} \div \dfrac{7}{8}$
> 3. `REL` Calculer : $6-4\times(-3)$
> 4. `Ch3` Développer : $(6-x)(3+x)$
> 5. `Ch6` Factoriser : $5x^2-20$
> 6. `Ch7` Dans le triangle $DEF$, $P\in[DE]$, $Q\in[DF]$, $(PQ)\parallel(EF)$, $DP=3$, $DE=8$, $DQ=4,5$. Calculer $DF$.
> 7. `Ch7` Deux triangles semblables ont un rapport de similitude $k=0,4$. Un côté du grand triangle mesure 15 cm : quelle est la longueur du côté correspondant du petit triangle ?
> 8. `PROP` Un article passe de 200 € à 250 €. Calculer le taux d'évolution, en %.
> 9. `CONV` Convertir 2h 15min en minutes.
> 10. `AP` Calculer le périmètre d'un rectangle d'aire 60 cm² et de largeur 5 cm.

#### Corrigé — Semaine 14 — Fiche B
1. $6+9=15$
2. $\frac{7}{4}\times\frac{8}{7}=\frac{56}{28}=2$
3. $6+12=18$
4. $18+6x-3x-x^2=-x^2+3x+18$
5. $5(x^2-4)=5(x-2)(x+2)$
6. $DF=\dfrac{DQ\times DE}{DP}=\dfrac{4,5\times8}{3}=12$
7. $15\times0,4=6$ cm
8. $\dfrac{250-200}{200}\times100=25\%$
9. $135$ min
10. Longueur $=\dfrac{60}{5}=12$ cm, périmètre $=2\times(12+5)=34$ cm

### Semaine 15

> [!exercice] Semaine 15 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $2\times 3^2 - 4$
> 2. `FR` Calculer : $\dfrac{3}{4}+\dfrac{5}{6}$
> 3. `REL` Calculer : $(-3-5)\times(-2)$
> 4. `Ch4` Rendre irréductible la fraction $\dfrac{36}{48}$.
> 5. `Ch5` Un robinet débite 15 L en 4 minutes. Quel est son débit en L/min ?
> 6. `Ch6` Factoriser : $(2x-1)^2-(2x-1)(x+3)$
> 7. `Ch7` Le théorème de Thalès s'applique dans quelle configuration (2 conditions) ?
> 8. `Ch8` Une fonction $f$ associe à un nombre $x$ son double diminué de 3. Écrire $f(x)$ en fonction de $x$.
> 9. `Ch8` Calculer $f(5)$ pour $f(x)=2x-3$.
> 10. `AP` Calculer l'aire d'un disque de rayon 4 cm (valeur exacte, puis arrondie au dixième avec $\pi\approx3,14$).

#### Corrigé — Semaine 15 — Fiche A
1. $18-4=14$
2. $\frac{9}{12}+\frac{10}{12}=\frac{19}{12}$
3. $(-8)\times(-2)=16$
4. $36=2^2\times3^2$, $48=2^4\times3$ → PGCD $=2^2\times3=12$ ; $\dfrac{36}{48}=\dfrac{3}{4}$
5. $\dfrac{15}{4}=3,75$ L/min
6. $(2x-1)\left[(2x-1)-(x+3)\right]=(2x-1)(x-4)$
7. Deux droites sécantes en un point, coupées par deux droites parallèles (configuration du triangle ou du papillon).
8. $f(x)=2x-3$
9. $f(5)=2\times5-3=7$
10. $\pi\times4^2=16\pi$ cm² $\approx 50,2$ cm²

> [!exercice] Semaine 15 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $5\times2^2-3$
> 2. `FR` Calculer : $\dfrac{2}{3}+\dfrac{5}{9}$
> 3. `REL` Calculer : $(-6-2)\times(-3)$
> 4. `Ch4` Rendre irréductible la fraction $\dfrac{28}{42}$.
> 5. `Ch5` Un robinet débite 24 L en 6 minutes. Quel est son débit en L/min ?
> 6. `Ch6` Factoriser : $(3x+1)^2-(3x+1)(2x-4)$
> 7. `Ch7` Que permet de démontrer la réciproque du théorème de Thalès ?
> 8. `Ch8` Une fonction $g$ associe à un nombre $x$ son triple augmenté de 2. Écrire $g(x)$.
> 9. `Ch8` Calculer $g(4)$ pour $g(x)=3x+2$.
> 10. `AP` Calculer l'aire d'un disque de rayon 6 cm (valeur exacte, puis arrondie au dixième avec $\pi\approx3,14$).

#### Corrigé — Semaine 15 — Fiche B
1. $20-3=17$
2. $\frac{6}{9}+\frac{5}{9}=\frac{11}{9}$
3. $-8\times(-3)=24$
4. $28=2^2\times7$, $42=2\times3\times7$ → PGCD $=2\times7=14$ ; $\dfrac{28}{42}=\dfrac{2}{3}$
5. $\dfrac{24}{6}=4$ L/min
6. $(3x+1)\left[(3x+1)-(2x-4)\right]=(3x+1)(x+5)$
7. Elle permet de démontrer que deux droites sont parallèles.
8. $g(x)=3x+2$
9. $g(4)=3\times4+2=14$
10. $\pi\times6^2=36\pi$ cm² $\approx 113,0$ cm²

### Semaine 16

> [!exercice] Semaine 16 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $5^2 - 2\times(8-3)$
> 2. `FR` Calculer et simplifier : $\dfrac{9}{5}-\dfrac{4}{5}$
> 3. `REL` Calculer : $(-18)\div(-3)+(-2)$
> 4. `Ch2` $I$ est le milieu de $[BC]$ dans un triangle $ABC$ isocèle en $A$. Que peut-on dire de la droite $(AI)$ par rapport à $(BC)$ ?
> 5. `Ch5` Une baignoire de 150 L se remplit à un débit de 12 L/min. Combien de temps faut-il pour la remplir, en min ?
> 6. `Ch7` Deux triangles ont leurs angles égaux deux à deux ($58°$, $47°$, $75°$). Sont-ils semblables ?
> 7. `Ch8` Sur un graphique, l'image de $-3$ par une fonction $f$ est $6$. Écrire cette égalité avec la notation $f(\ldots)=\ldots$
> 8. `PUI` Calculer $10^3 \times 10^{-5}$ sous la forme d'une seule puissance de 10.
> 9. `CONV` Convertir $128\,000$ cm³ en L.
> 10. `AP` Calculer le volume d'un cube d'arête 5 cm.

#### Corrigé — Semaine 16 — Fiche A
1. $25-10=15$
2. $\frac{9}{5}-\frac{4}{5}=\frac{5}{5}=1$
3. $6+(-2)=4$
4. $(AI)$ est la médiatrice de $[BC]$ : elle est perpendiculaire à $(BC)$ et passe par son milieu (dans un triangle isocèle, la médiane issue du sommet principal est aussi hauteur).
5. $\dfrac{150}{12}=12,5$ min
6. Oui, ils sont semblables (critère AA : angles égaux deux à deux).
7. $f(-3)=6$
8. $10^{3-5}=10^{-2}$
9. $128\,000$ cm³ $=128$ L
10. $5^3=125$ cm³

> [!exercice] Semaine 16 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $4^2 - 3\times(6-2)$
> 2. `FR` Calculer et simplifier : $\dfrac{7}{8}-\dfrac{3}{8}$
> 3. `REL` Calculer : $(-21)\div(-7)+(-5)$
> 4. `Ch2` $J$ est le milieu de $[BC]$ dans un triangle $ABC$ isocèle en $A$. Que représente la droite $(AJ)$ pour l'angle $\widehat{BAC}$ ?
> 5. `Ch5` Une piscine de 200 L se remplit à un débit de 25 L/min. Combien de temps pour la remplir, en min ?
> 6. `Ch7` Deux triangles ont pour angles $62°$, $45°$, $73°$ et $62°$, $73°$, $45°$. Sont-ils semblables ?
> 7. `Ch8` Sur un graphique, l'image de 4 par une fonction $p$ est $-1$. Écrire cette égalité avec la notation $p(\ldots)=\ldots$
> 8. `PUI` Calculer $10^{-2}\times10^6$ sous la forme d'une seule puissance de 10.
> 9. `CONV` Convertir $45\,000$ cm³ en L.
> 10. `AP` Calculer le volume d'un cube d'arête 6 cm.

#### Corrigé — Semaine 16 — Fiche B
1. $16-12=4$
2. $\frac{4}{8}=\frac{1}{2}$
3. $3+(-5)=-2$
4. $(AJ)$ est la bissectrice de l'angle $\widehat{BAC}$.
5. $\dfrac{200}{25}=8$ min
6. Oui, ils ont les mêmes angles.
7. $p(4)=-1$
8. $10^{-2+6}=10^4$
9. $45\,000$ cm³ $=45$ L
10. $6^3=216$ cm³

### Semaine 17

> [!exercice] Semaine 17 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $7\times 4 - 3\times 6$
> 2. `FR` Calculer : $1-\dfrac{2}{7}$
> 3. `REL` Calculer : $(-5)+(-3)-(-8)$
> 4. `Ch3` Développer : $(x+6)(x-6)$
> 5. `Ch6` Factoriser : $x^2+10x+25$
> 6. `Ch7` Dans une configuration de Thalès, $\dfrac{AM}{AB}=\dfrac{AN}{AC}=\dfrac{2}{5}$. Si $BC=15$ cm, calculer $MN$.
> 7. `Ch9` Résoudre l'équation $3x+5=17$.
> 8. `Ch9` Résoudre l'équation $2x-3=5x+9$.
> 9. `PROP` Calculer 35% de 80.
> 10. `CONV` Convertir 45 min en heure décimale.

#### Corrigé — Semaine 17 — Fiche A
1. $28-18=10$
2. $\frac{7}{7}-\frac{2}{7}=\frac{5}{7}$
3. $-5-3+8=0$
4. $x^2-36$
5. $(x+5)^2$
6. $\dfrac{MN}{BC}=\dfrac{2}{5}$ donc $MN=15\times\dfrac{2}{5}=6$
7. $3x=12$ donc $x=4$
8. $2x-5x=9+3$ soit $-3x=12$ donc $x=-4$
9. $0,35\times80=28$
10. $\dfrac{45}{60}=0,75$ h

> [!exercice] Semaine 17 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $9\times3-4\times5$
> 2. `FR` Calculer : $1-\dfrac{3}{8}$
> 3. `REL` Calculer : $(-6)+(-4)-(-9)$
> 4. `Ch3` Développer : $(x+7)(x-7)$
> 5. `Ch6` Factoriser : $x^2+8x+16$
> 6. `Ch7` Dans une configuration de Thalès, $\dfrac{AM}{AB}=\dfrac{AN}{AC}=\dfrac{3}{4}$. Si $BC=20$ cm, calculer $MN$.
> 7. `Ch9` Résoudre l'équation $4x-1=15$.
> 8. `Ch9` Résoudre l'équation $3x+7=8x-3$.
> 9. `PROP` Calculer 15% de 220.
> 10. `CONV` Convertir 30 min en heure décimale.

#### Corrigé — Semaine 17 — Fiche B
1. $27-20=7$
2. $\frac{8}{8}-\frac{3}{8}=\frac{5}{8}$
3. $-10+9=-1$
4. $x^2-49$
5. $(x+4)^2$
6. $MN=20\times\dfrac{3}{4}=15$
7. $4x=16$ donc $x=4$
8. $3x-8x=-3-7$ soit $-5x=-10$ donc $x=2$
9. $0,15\times220=33$
10. $0,5$ h

### Semaine 18

> [!exercice] Semaine 18 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $9^2-40$
> 2. `FR` Calculer et simplifier : $\dfrac{3}{8}\times\dfrac{4}{9}$
> 3. `REL` Calculer : $(-7)+(-2)\times(-3)$
> 4. `Ch4` Calculer PGCD(28, 42).
> 5. `Ch8` $g$ est une fonction telle que $g(2)=-1$. Quel est l'antécédent de $-1$ par $g$ ?
> 6. `Ch9` Résoudre l'inéquation $2x+3>11$.
> 7. `Ch10` Une fonction affine est définie par $f(x)=3x-2$. Calculer $f(4)$.
> 8. `Ch10` Une fonction linéaire $g$ vérifie $g(5)=20$. Déterminer son coefficient directeur.
> 9. `AP` Calculer l'aire d'un rectangle de périmètre 30 cm et de longueur 9 cm.
> 10. `LEC` Une fonction affine passe par les points $(0\,;-2)$ et $(3\,;4)$. Calculer son coefficient directeur.

#### Corrigé — Semaine 18 — Fiche A
1. $81-40=41$
2. $\frac{12}{72}=\frac{1}{6}$
3. $-7+6=-1$
4. $28=2^2\times7$, $42=2\times3\times7$ → PGCD $=2\times7=14$
5. L'antécédent de $-1$ par $g$ est $2$.
6. $2x>8$ donc $x>4$
7. $f(4)=3\times4-2=10$
8. $g(x)=ax$ donc $5a=20$ soit $a=4$
9. $P=2(L+l)=30$ donc $L+l=15$, soit $l=15-9=6$ ; aire $=9\times6=54$ cm²
10. Coefficient directeur $=\dfrac{4-(-2)}{3-0}=\dfrac{6}{3}=2$

> [!exercice] Semaine 18 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $7^2-30$
> 2. `FR` Calculer et simplifier : $\dfrac{2}{5}\times\dfrac{5}{6}$
> 3. `REL` Calculer : $(-8)+(-3)\times(-2)$
> 4. `Ch4` Calculer PGCD(24, 36).
> 5. `Ch8` $f$ est une fonction telle que $f(-1)=3$. Quel est l'antécédent de 3 par $f$ ?
> 6. `Ch9` Résoudre l'inéquation $3x-2\le 10$.
> 7. `Ch10` Une fonction affine $f(x)=-4x+5$. Calculer $f(2)$.
> 8. `Ch10` Une fonction linéaire $g$ vérifie $g(4)=12$. Déterminer son coefficient directeur.
> 9. `AP` Calculer l'aire d'un rectangle de périmètre 26 cm et de longueur 8 cm.
> 10. `LEC` Une fonction affine passe par les points $(0\,;1)$ et $(2\,;9)$. Calculer son coefficient directeur.

#### Corrigé — Semaine 18 — Fiche B
1. $49-30=19$
2. $\frac{10}{30}=\frac{1}{3}$
3. $-8+6=-2$
4. $24=2^3\times3$, $36=2^2\times3^2$ → PGCD $=2^2\times3=12$
5. L'antécédent de 3 par $f$ est $-1$.
6. $3x\le12$ donc $x\le4$
7. $f(2)=-8+5=-3$
8. $g(x)=ax$ donc $4a=12$ soit $a=3$
9. $P=2(L+l)=26$ donc $L+l=13$, soit $l=13-8=5$ ; aire $=8\times5=40$ cm²
10. Coefficient directeur $=\dfrac{9-1}{2-0}=\dfrac{8}{2}=4$

### Semaine 19

> [!exercice] Semaine 19 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $6^2 \div 4 + 3$
> 2. `FR` Calculer : $\dfrac{5}{9}-\dfrac{2}{9}+\dfrac{1}{3}$
> 3. `REL` Calculer : $(-4)\times 3-(-6)$
> 4. `Ch2` Le triangle $MNP$ vérifie $MN^2+NP^2=MP^2$. Que peut-on en conclure ?
> 5. `Ch5` Une voiture consomme 6 L aux 100 km. Combien consomme-t-elle pour parcourir 250 km ?
> 6. `Ch6` Factoriser : $4x^2-1$
> 7. `Ch9` Résoudre l'équation $\dfrac{x}{3}+1=4$.
> 8. `Ch10` Une fonction linéaire a pour coefficient directeur $-2$. Calculer l'image de 5.
> 9. `PUI` Écrire $6,2\times10^{-3}$ en écriture décimale.
> 10. `AP` Calculer l'aire puis le périmètre d'un rectangle de longueur 15 cm et de largeur 4 cm.

#### Corrigé — Semaine 19 — Fiche A
1. $\dfrac{36}{4}+3=9+3=12$
2. $\frac{5}{9}-\frac{2}{9}+\frac{3}{9}=\frac{6}{9}=\frac{2}{3}$
3. $-12+6=-6$
4. D'après la réciproque du théorème de Pythagore, le triangle $MNP$ est rectangle en $N$.
5. $\dfrac{6\times250}{100}=15$ L
6. $(2x-1)(2x+1)$
7. $\dfrac{x}{3}=3$ donc $x=9$
8. $g(x)=-2x$ donc $g(5)=-10$
9. $0,0062$
10. Aire $=15\times4=60$ cm² ; périmètre $=2\times(15+4)=38$ cm

> [!exercice] Semaine 19 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $8^2\div4+5$
> 2. `FR` Calculer : $\dfrac{4}{9}-\dfrac{1}{9}+\dfrac{2}{3}$
> 3. `REL` Calculer : $(-5)\times2-(-4)$
> 4. `Ch2` Un triangle $XYZ$ vérifie $XY^2+YZ^2=XZ^2$. Que peut-on en conclure ?
> 5. `Ch5` Une voiture consomme 7 L aux 100 km. Combien consomme-t-elle pour parcourir 350 km ?
> 6. `Ch6` Factoriser : $9x^2-4$
> 7. `Ch9` Résoudre l'équation $\dfrac{x}{4}-2=1$.
> 8. `Ch10` Une fonction linéaire a pour coefficient directeur 3. Calculer l'image de $-2$.
> 9. `PUI` Écrire $4,1\times10^{-2}$ en écriture décimale.
> 10. `AP` Calculer l'aire puis le périmètre d'un rectangle de longueur 11 cm et de largeur 3 cm.

#### Corrigé — Semaine 19 — Fiche B
1. $\dfrac{64}{4}+5=16+5=21$
2. $\frac{4}{9}-\frac{1}{9}+\frac{6}{9}=\frac{9}{9}=1$
3. $-10+4=-6$
4. D'après la réciproque du théorème de Pythagore, le triangle $XYZ$ est rectangle en $Y$.
5. $\dfrac{7\times350}{100}=24,5$ L
6. $(3x-2)(3x+2)$
7. $\dfrac{x}{4}=3$ donc $x=12$
8. $g(x)=3x$ donc $g(-2)=-6$
9. $0,041$
10. Aire $=11\times3=33$ cm² ; périmètre $=2\times(11+3)=28$ cm

### Semaine 20

> [!exercice] Semaine 20 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $8^2-6\times7$
> 2. `FR` Calculer : $\dfrac{7}{15}+\dfrac{1}{5}$
> 3. `REL` Calculer : $(-9)+(-9)\div 3$
> 4. `Ch3` Développer : $2(x-1)^2$
> 5. `Ch7` $ABC$ et $ADE$ sont deux triangles tels que $\widehat{A}$ est commun et $(DE)\parallel(BC)$. Si $AD=3$, $AB=9$, $DE=4$, calculer $BC$.
> 6. `Ch9` Résoudre l'inéquation $-2x+5\le 1$ (attention au sens de l'inégalité).
> 7. `Ch10` Une fonction affine $f(x)=ax+b$ vérifie $f(0)=5$ et $f(2)=1$. Déterminer $a$ et $b$.
> 8. `Ch11` Dans un triangle rectangle en $A$, $\widehat{B}=30°$ et l'hypoténuse $BC=10$ cm. Calculer $AC$ (côté opposé à $\widehat{B}$) à l'aide du sinus.
> 9. `Ch11` Écrire la formule donnant le cosinus d'un angle dans un triangle rectangle.
> 10. `PROP` Une population de 2 000 habitants augmente de 3% en un an. Calculer la population après un an.

#### Corrigé — Semaine 20 — Fiche A
1. $64-42=22$
2. $\frac{7}{15}+\frac{3}{15}=\frac{10}{15}=\frac{2}{3}$
3. $-9+(-3)=-12$
4. $2(x^2-2x+1)=2x^2-4x+2$
5. $\dfrac{BC}{DE}=\dfrac{AB}{AD}$ donc $BC=\dfrac{DE\times AB}{AD}=\dfrac{4\times9}{3}=12$
6. $-2x\le-4$ donc $x\ge2$ (on divise par un nombre négatif, le sens change)
7. $f(0)=b=5$ ; $f(2)=2a+5=1$ donc $2a=-4$ soit $a=-2$
8. $\sin(30°)=\dfrac{AC}{BC}$ donc $AC=BC\times\sin(30°)=10\times0,5=5$ cm
9. $\cos(\text{angle})=\dfrac{\text{côté adjacent}}{\text{hypoténuse}}$
10. $2\,000\times1,03=2\,060$ habitants

> [!exercice] Semaine 20 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $9^2-5\times8$
> 2. `FR` Calculer : $\dfrac{5}{12}+\dfrac{1}{4}$
> 3. `REL` Calculer : $(-12)+(-8)\div4$
> 4. `Ch3` Développer : $3(x+2)^2$
> 5. `Ch7` $ABC$ et $ADE$ sont semblables, $\widehat A$ commun, $(DE)\parallel(BC)$. $AD=4$, $AB=6$, $BC=9$. Calculer $DE$.
> 6. `Ch9` Résoudre l'inéquation $-3x+2>11$.
> 7. `Ch10` Une fonction affine $f(x)=ax+b$ vérifie $f(0)=-2$ et $f(3)=7$. Déterminer $a$ et $b$.
> 8. `Ch11` Dans un triangle rectangle en $A$, $\widehat B=35°$ et l'hypoténuse $BC=9$ cm. Écrire l'équation permettant de calculer $AC$ (côté opposé à $\widehat B$) à l'aide du sinus.
> 9. `Ch11` Écrire la formule donnant la tangente d'un angle dans un triangle rectangle.
> 10. `PROP` Une population de 1 500 habitants diminue de 4% en un an. Calculer la population après un an.

#### Corrigé — Semaine 20 — Fiche B
1. $81-40=41$
2. $\frac{5}{12}+\frac{3}{12}=\frac{8}{12}=\frac{2}{3}$
3. $-12+(-2)=-14$
4. $3(x^2+4x+4)=3x^2+12x+12$
5. $DE=\dfrac{BC\times AD}{AB}=\dfrac{9\times4}{6}=6$
6. $-3x>9$ donc $x<-3$
7. $f(0)=b=-2$ ; $f(3)=3a-2=7$ donc $3a=9$ soit $a=3$
8. $\sin(35°)=\dfrac{AC}{BC}$ donc $AC=9\times\sin(35°)$
9. $\tan(\text{angle})=\dfrac{\text{côté opposé}}{\text{côté adjacent}}$
10. $1\,500\times0,96=1\,440$ habitants

### Semaine 21

> [!exercice] Semaine 21 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $5\times(6-2)^2$
> 2. `FR` Calculer : $\dfrac{1}{2}+\dfrac{1}{3}+\dfrac{1}{6}$
> 3. `REL` Calculer : $(-2)^3+(-1)^4$
> 4. `Ch4` Décomposer 84 en produit de facteurs premiers.
> 5. `Ch6` Factoriser : $(3x+2)^2-(3x+2)(x-5)$
> 6. `Ch9` Résoudre l'équation $5(x-1)=2x+7$.
> 7. `Ch11` Dans un triangle rectangle en $A$, $AB=6$ cm et $AC=8$ cm. Calculer $\tan(\widehat{B})$.
> 8. `Ch12` Un sac contient 4 boules rouges et 6 boules vertes. On tire une boule au hasard. Quelle est la probabilité de tirer une boule rouge ?
> 9. `Ch12` Calculer la moyenne pondérée de la série : 12 (effectif 3), 15 (effectif 5), 18 (effectif 2).
> 10. `AP` Calculer l'aire d'un disque de rayon 10 cm (valeur exacte).

#### Corrigé — Semaine 21 — Fiche A
1. $(6-2)^2=16$, donc $5\times16=80$
2. $\frac{3}{6}+\frac{2}{6}+\frac{1}{6}=\frac{6}{6}=1$
3. $-8+1=-7$
4. $84=2^2\times3\times7$
5. $(3x+2)\left[(3x+2)-(x-5)\right]=(3x+2)(2x+7)$
6. $5x-5=2x+7$ donc $3x=12$ soit $x=4$
7. $\tan(\widehat B)=\dfrac{\text{opposé}}{\text{adjacent}}=\dfrac{AC}{AB}=\dfrac{8}{6}=\dfrac{4}{3}$
8. $\dfrac{4}{10}=\dfrac{2}{5}=0,4$
9. $\dfrac{12\times3+15\times5+18\times2}{3+5+2}=\dfrac{36+75+36}{10}=\dfrac{147}{10}=14,7$
10. $\pi\times10^2=100\pi$ cm²

> [!exercice] Semaine 21 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $6\times(8-5)^2$
> 2. `FR` Calculer : $\dfrac{1}{3}+\dfrac{1}{4}+\dfrac{1}{6}$
> 3. `REL` Calculer : $(-3)^3-(-2)^2$
> 4. `Ch4` Décomposer 90 en produit de facteurs premiers.
> 5. `Ch6` Factoriser : $(2x-3)^2-(2x-3)(x+4)$
> 6. `Ch9` Résoudre l'équation $4(x+2)=3x+11$.
> 7. `Ch11` Dans un triangle rectangle en $A$, $AB=9$ cm et $AC=12$ cm. Calculer $\tan(\widehat C)$.
> 8. `Ch12` Un sac contient 5 boules jaunes et 7 boules bleues. Quelle est la probabilité de tirer une boule jaune ?
> 9. `Ch12` Calculer la moyenne pondérée de la série : 10 (effectif 4), 13 (effectif 4), 16 (effectif 2).
> 10. `AP` Calculer l'aire d'un disque de rayon 7 cm (valeur exacte).

#### Corrigé — Semaine 21 — Fiche B
1. $(8-5)^2=9$, donc $6\times9=54$
2. $\frac{4}{12}+\frac{3}{12}+\frac{2}{12}=\frac{9}{12}=\frac{3}{4}$
3. $-27-4=-31$
4. $90=2\times3^2\times5$
5. $(2x-3)\left[(2x-3)-(x+4)\right]=(2x-3)(x-7)$
6. $4x+8=3x+11$ donc $x=3$
7. $\tan(\widehat C)=\dfrac{\text{opposé}}{\text{adjacent}}=\dfrac{AB}{AC}=\dfrac{9}{12}=\dfrac{3}{4}$
8. $\dfrac{5}{12}$
9. $\dfrac{10\times4+13\times4+16\times2}{4+4+2}=\dfrac{40+52+32}{10}=\dfrac{124}{10}=12,4$
10. $\pi\times7^2=49\pi$ cm²

### Semaine 22

> [!exercice] Semaine 22 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $100-(4+3\times2)$
> 2. `FR` Calculer et simplifier : $\dfrac{4}{7}\div\dfrac{2}{3}$
> 3. `REL` Calculer : $(-3)^2-4\times(-2)$
> 4. `Ch5` Une voiture roule à 90 km/h. Quelle distance parcourt-elle en 20 minutes ?
> 5. `Ch7` Quelle est la différence essentielle entre le théorème de Thalès et sa réciproque (ce que l'on suppose / ce que l'on démontre) ?
> 6. `Ch10` Une fonction affine $f$ a pour coefficient directeur 3 et passe par $(0\,;-1)$. Écrire $f(x)$.
> 7. `Ch11` Dans un triangle rectangle, l'hypoténuse mesure 13 cm et un angle aigu $\widehat B$ vérifie $\cos(\widehat B)=\dfrac{5}{13}$. Calculer le côté adjacent à $\widehat B$.
> 8. `Ch12` On lance un dé à 6 faces. Quelle est la probabilité d'obtenir un nombre pair ?
> 9. `Ch13` Une homothétie de rapport $k=3$ transforme un segment de longueur 4 cm. Quelle est la longueur de son image ?
> 10. `Ch13` Une homothétie de rapport $k=-2$ transforme une aire de 5 cm². Quelle est l'aire de son image ?

#### Corrigé — Semaine 22 — Fiche A
1. $100-(4+6)=100-10=90$
2. $\frac{4}{7}\times\frac{3}{2}=\frac{12}{14}=\frac{6}{7}$
3. $9+8=17$
4. $20$ min $=\dfrac{1}{3}$ h, donc distance $=90\times\dfrac{1}{3}=30$ km
5. Le théorème de Thalès part du parallélisme pour obtenir l'égalité des rapports ; sa réciproque part de l'égalité des rapports (avec alignement) pour démontrer le parallélisme.
6. $f(x)=3x-1$
7. $\cos(\widehat B)=\dfrac{\text{adjacent}}{\text{hypoténuse}}$ donc adjacent $=13\times\dfrac{5}{13}=5$ cm
8. $\dfrac{3}{6}=\dfrac{1}{2}$
9. $4\times3=12$ cm
10. L'aire est multipliée par $k^2=4$ (le signe de $k$ n'affecte pas une aire), donc $5\times4=20$ cm²

> [!exercice] Semaine 22 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $80-(6+2\times3)$
> 2. `FR` Calculer et simplifier : $\dfrac{5}{6} \div \dfrac{5}{9}$
> 3. `REL` Calculer : $(-4)^2-3\times(-1)$
> 4. `Ch5` Un scooter roule à 45 km/h. Quelle distance parcourt-il en 40 minutes ?
> 5. `Ch7` Qu'est-ce que l'on suppose (l'hypothèse) dans le théorème de Thalès (sens direct) ?
> 6. `Ch10` Une fonction affine $g$ a pour coefficient directeur $-1$ et passe par $(0\,;4)$. Écrire $g(x)$.
> 7. `Ch11` Dans un triangle rectangle, l'hypoténuse mesure 10 cm et un angle aigu $\widehat C$ vérifie $\sin(\widehat C)=0,6$. Calculer le côté opposé à $\widehat C$.
> 8. `Ch12` On lance un dé à 6 faces. Quelle est la probabilité d'obtenir un multiple de 3 ?
> 9. `Ch13` Une homothétie de rapport $k=4$ transforme un segment de 2,5 cm. Quelle est la longueur de son image ?
> 10. `Ch13` Une homothétie de rapport $k=-3$ transforme une aire de 4 cm². Quelle est l'aire de son image ?

#### Corrigé — Semaine 22 — Fiche B
1. $80-(6+6)=80-12=68$
2. $\frac{5}{6}\times\frac{9}{5}=\frac{45}{30}=\frac{3}{2}$
3. $16+3=19$
4. $40$ min $=\dfrac{2}{3}$ h, donc distance $=45\times\dfrac{2}{3}=30$ km
5. On suppose le parallélisme de deux droites pour en déduire l'égalité des rapports de longueurs.
6. $g(x)=-x+4$
7. $\sin(\widehat C)=\dfrac{\text{opposé}}{\text{hypoténuse}}$ donc opposé $=10\times0,6=6$ cm
8. Multiples de 3 sur un dé : 3 et 6, donc $\dfrac{2}{6}=\dfrac{1}{3}$
9. $2,5\times4=10$ cm
10. Aire $\times k^2=4\times9=36$ cm²

### Semaine 23

> [!exercice] Semaine 23 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $3\times 4^2-15$
> 2. `FR` Calculer : $\dfrac{5}{6}-\dfrac{1}{4}$
> 3. `REL` Calculer : $(-15)\div(-5)\times(-2)$
> 4. `Ch3` Développer à l'aide d'une identité remarquable : $(x-7)^2$
> 5. `Ch6` Factoriser à l'aide d'une identité remarquable : $9x^2-30x+25$
> 6. `Ch9` Résoudre l'inéquation $\dfrac{x}{2}-1<3$.
> 7. `Ch11` Dans un triangle rectangle en $A$, $\widehat B=40°$ et le côté opposé $AC=5$ cm. Écrire l'équation permettant de calculer l'hypoténuse $BC$.
> 8. `Ch12` Une urne contient 20 jetons dont 5 sont gagnants. Quelle est la probabilité de ne pas gagner ?
> 9. `Ch13` $O$ est le centre d'une homothétie et $M'$ est l'image de $M$. Que peut-on dire des points $M$, $O$ et $M'$ ?
> 10. `AP` Calculer le volume d'un cube dont l'aire d'une face est 36 cm².

#### Corrigé — Semaine 23 — Fiche A
1. $48-15=33$
2. $\frac{10}{12}-\frac{3}{12}=\frac{7}{12}$
3. $\dfrac{-15}{-5}=3$, donc $3\times(-2)=-6$
4. $x^2-14x+49$
5. $(3x-5)^2$
6. $\dfrac{x}{2}<4$ donc $x<8$
7. $\sin(40°)=\dfrac{AC}{BC}$ donc $BC=\dfrac{5}{\sin(40°)}$
8. Probabilité de gagner $=\dfrac{5}{20}=\dfrac{1}{4}$, donc probabilité de ne pas gagner $=\dfrac{3}{4}$
9. $M$, $O$ et $M'$ sont alignés (la droite $(MM')$ passe par le centre $O$).
10. Le côté du cube mesure $\sqrt{36}=6$ cm, donc le volume est $6^3=216$ cm³

> [!exercice] Semaine 23 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $2\times5^2-20$
> 2. `FR` Calculer : $\dfrac{7}{8}-\dfrac{1}{6}$
> 3. `REL` Calculer : $(-24)\div(-6)\times(-3)$
> 4. `Ch3` Développer à l'aide d'une identité remarquable : $(x+9)^2$
> 5. `Ch6` Factoriser à l'aide d'une identité remarquable : $4x^2-12x+9$
> 6. `Ch9` Résoudre l'inéquation $\dfrac{x}{3}+2\ge5$.
> 7. `Ch11` Dans un triangle rectangle en $A$, $\widehat B=55°$ et le côté adjacent $AB=6$ cm. Écrire l'équation permettant de calculer l'hypoténuse $BC$ à l'aide du cosinus.
> 8. `Ch12` Une urne contient 25 jetons dont 10 sont gagnants. Quelle est la probabilité de ne pas gagner ?
> 9. `Ch13` $O$ est le centre d'une homothétie de rapport $k=1$ et $M'$ est l'image de $M$. Que peut-on dire de $M$ et $M'$ ?
> 10. `AP` Calculer le volume d'un cube dont l'aire d'une face est 64 cm².

#### Corrigé — Semaine 23 — Fiche B
1. $50-20=30$
2. $\frac{21}{24}-\frac{4}{24}=\frac{17}{24}$
3. $4\times(-3)=-12$
4. $x^2+18x+81$
5. $(2x-3)^2$
6. $\dfrac{x}{3}\ge3$ donc $x\ge9$
7. $\cos(55°)=\dfrac{AB}{BC}$ donc $BC=\dfrac{6}{\cos(55°)}$
8. Probabilité de gagner $=\dfrac{10}{25}=\dfrac{2}{5}$, donc probabilité de ne pas gagner $=\dfrac{3}{5}$
9. $M=M'$ (une homothétie de rapport 1 est l'identité).
10. Le côté du cube mesure $\sqrt{64}=8$ cm, donc le volume est $8^3=512$ cm³

### Semaine 24

> [!exercice] Semaine 24 — Fiche A (15 min, sans calculatrice)
> 1. `CM` Calculer : $2^4-3\times5$
> 2. `FR` Calculer : $\dfrac{2}{9}+\dfrac{1}{3}-\dfrac{1}{9}$
> 3. `REL` Calculer : $(-6)-(-6)+(-6)$
> 4. `Ch1` Développer et réduire : $-3(2x-1)+4x$
> 5. `Ch4` Le nombre 132 est-il divisible par 3 ? Justifier.
> 6. `Ch8` Une fonction $h$ vérifie $h(-2)=3$ et $h(1)=3$. Que peut-on dire des antécédents de 3 par $h$ ?
> 7. `Ch10` Deux fonctions affines ont pour coefficients directeurs 2 et $-0,5$. Leurs représentations graphiques sont-elles parallèles ?
> 8. `Ch14` Un pavé droit a pour dimensions 4 cm, 5 cm et 6 cm. Calculer son volume.
> 9. `Ch14` Une pyramide a une base carrée de côté 6 cm et une hauteur de 10 cm. Calculer son volume avec $V=\dfrac{\mathcal{A}_{base}\times h}{3}$.
> 10. `AP` Calculer l'aire totale des faces d'un cube d'arête 4 cm.

#### Corrigé — Semaine 24 — Fiche A
1. $16-15=1$
2. $\frac{2}{9}+\frac{3}{9}-\frac{1}{9}=\frac{4}{9}$
3. $-6+6-6=-6$
4. $-6x+3+4x=-2x+3$
5. $1+3+2=6$, et 6 est divisible par 3, donc 132 est divisible par 3.
6. $-2$ et $1$ sont deux antécédents de 3 par $h$.
7. Non : deux droites sont parallèles si et seulement si leurs coefficients directeurs sont égaux ; ici $2\neq-0,5$.
8. $4\times5\times6=120$ cm³
9. Aire de la base $=6^2=36$ cm², donc $V=\dfrac{36\times10}{3}=120$ cm³
10. $6\times4^2=6\times16=96$ cm²

> [!exercice] Semaine 24 — Fiche B (15 min, sans calculatrice)
> 1. `CM` Calculer : $3^3-4\times6$
> 2. `FR` Calculer : $\dfrac{5}{6}-\dfrac{1}{2}+\dfrac{1}{3}$
> 3. `REL` Calculer : $(-8)+(-8)-(-8)$
> 4. `Ch1` Développer et réduire : $-2(3x-2)+5x$
> 5. `Ch4` Le nombre 315 est-il divisible par 9 ? Justifier.
> 6. `Ch8` Une fonction $k$ vérifie $k(3)=-2$ et $k(-1)=-2$. Que peut-on dire des antécédents de $-2$ par $k$ ?
> 7. `Ch10` Deux fonctions affines ont pour coefficients directeurs $-3$ et $-3$. Leurs représentations graphiques sont-elles parallèles ?
> 8. `Ch14` Un pavé droit a pour dimensions 3 cm, 7 cm et 5 cm. Calculer son volume.
> 9. `Ch14` Une pyramide a une base rectangulaire de 4 cm sur 6 cm et une hauteur de 9 cm. Calculer son volume avec $V=\dfrac{\mathcal{A}_{base}\times h}{3}$.
> 10. `AP` Calculer l'aire totale des faces d'un cube d'arête 3 cm.

#### Corrigé — Semaine 24 — Fiche B
1. $27-24=3$
2. $\frac{5}{6}-\frac{3}{6}+\frac{2}{6}=\frac{4}{6}=\frac{2}{3}$
3. $-8-8+8=-8$
4. $-6x+4+5x=-x+4$
5. $3+1+5=9$, et 9 est divisible par 9, donc 315 est divisible par 9.
6. $3$ et $-1$ sont deux antécédents de $-2$ par $k$.
7. Oui : les coefficients directeurs sont égaux ($-3=-3$), donc les droites sont parallèles.
8. $3\times7\times5=105$ cm³
9. Aire de la base $=4\times6=24$ cm², donc $V=\dfrac{24\times9}{3}=72$ cm³
10. $6\times3^2=54$ cm²

### Semaine 25

> [!exercice] Semaine 25 — Fiche A (15 min, sans calculatrice) — révision finale
> 1. `CM` Calculer : $7^2-3\times(8-5)$
> 2. `FR` Calculer : $\dfrac{3}{4}-\dfrac{1}{6}$
> 3. `REL` Calculer : $(-8)\times(-3)+(-10)$
> 4. `Ch3` Développer : $(2x+5)(3x-1)$
> 5. `Ch4` Calculer PGCD(36, 54).
> 6. `Ch6` Factoriser : $16x^2-25$
> 7. `Ch9` Résoudre l'équation $4x-7=2x+5$.
> 8. `Ch11` Écrire la formule permettant de calculer $\sin(\widehat B)$ dans un triangle rectangle en $A$.
> 9. `Ch12` Un sac de 15 jetons contient 6 jetons bleus. Quelle est la probabilité de tirer un jeton bleu ?
> 10. `Ch13` Une homothétie de rapport $k=2$ transforme un volume de 10 cm³. Quel est le volume de son image ?

#### Corrigé — Semaine 25 — Fiche A
1. $49-9=40$
2. $\frac{9}{12}-\frac{2}{12}=\frac{7}{12}$
3. $24-10=14$
4. $6x^2-2x+15x-5=6x^2+13x-5$
5. $36=2^2\times3^2$, $54=2\times3^3$ → PGCD $=2\times3^2=18$
6. $(4x-5)(4x+5)$
7. $4x-2x=5+7$ donc $2x=12$ soit $x=6$
8. $\sin(\widehat B)=\dfrac{\text{côté opposé}}{\text{hypoténuse}}=\dfrac{AC}{BC}$
9. $\dfrac{6}{15}=\dfrac{2}{5}$
10. Le volume est multiplié par $k^3=8$, donc $10\times8=80$ cm³

> [!exercice] Semaine 25 — Fiche B (15 min, sans calculatrice) — révision finale
> 1. `CM` Calculer : $6^2-4\times(9-6)$
> 2. `FR` Calculer : $\dfrac{5}{6}-\dfrac{1}{3}$
> 3. `REL` Calculer : $(-7)\times(-2)+(-5)$
> 4. `Ch3` Développer : $(3x-4)(2x+3)$
> 5. `Ch4` Calculer PGCD(48, 72).
> 6. `Ch6` Factoriser : $25x^2-9$
> 7. `Ch9` Résoudre l'équation $5x-3=3x+9$.
> 8. `Ch11` Écrire la formule permettant de calculer $\cos(\widehat B)$ dans un triangle rectangle en $A$.
> 9. `Ch12` Un sac de 20 jetons contient 8 jetons rouges. Quelle est la probabilité de tirer un jeton rouge ?
> 10. `Ch13` Une homothétie de rapport $k=3$ transforme un volume de 5 cm³. Quel est le volume de son image ?

#### Corrigé — Semaine 25 — Fiche B
1. $36-12=24$
2. $\frac{5}{6}-\frac{2}{6}=\frac{3}{6}=\frac{1}{2}$
3. $14-5=9$
4. $6x^2+9x-8x-12=6x^2+x-12$
5. $48=2^4\times3$, $72=2^3\times3^2$ → PGCD $=2^3\times3=24$
6. $(5x-3)(5x+3)$
7. $5x-3x=9+3$ soit $2x=12$ donc $x=6$
8. $\cos(\widehat B)=\dfrac{AB}{BC}$ (côté adjacent sur hypoténuse)
9. $\dfrac{8}{20}=\dfrac{2}{5}$
10. Le volume est multiplié par $k^3=27$, donc $5\times27=135$ cm³
