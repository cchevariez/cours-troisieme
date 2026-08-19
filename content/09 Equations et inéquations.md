---
chapitre: 9
tags:
  - maths/troisieme
---

# Équations et inéquations

> [!activite] Programme Scratch
> Le programme se charge automatiquement ci-dessous.
>
> <iframe src="https://cchevariez.github.io/cours-troisieme/static/scratch-player/index.html?project=equation_1.sb3" width="1000" height="650" style="border:1px solid #e4e4e4;border-radius:4px;" frameborder="0"></iframe>
>
> ![[equation_1_code.png|300]]

## Équations du second degré

### Équation produit nul

> [!definition] Définition — Équation produit nul
> On appelle équation produit nul une équation dont un membre est un produit de facteurs et dont l'autre membre est nul.

> [!exercice] Exercice 1
> En utilisant la définition ci-dessus, déterminer les équations qui sont des équations de produit nul.
> - $2x+3 = 0$
> - $(6x-4)(2x+1) = 0$
> - $(6x-4)-(2x+1) = 0$
> - $(9x+4)(2x+1) = 4$
> - $6(2x+1) = 0$
> - $0 = (-3x+5)(3x+2)$

> [!propriete] Propriété
> Un produit de facteurs est nul si et seulement si un des facteurs est nul. Autrement dit, si $a\times b = 0$, alors $a=0$ ou $b=0$.

> [!exercice] Exercice 2
> En utilisant la propriété précédente, résoudre les équations suivantes :
> - $(6x-4)(2x+1) = 0$
> - $(2x+11)(4x+1) = 0$
> - $(-2x-4)(x+1) = 0$
> - $2x(6x+14) = 0$

> [!remarque] Remarque
> Parfois il est nécessaire de factoriser afin de construire l'équation produit nul.

> [!exercice] Exercice 3
> Résoudre les équations suivantes (il n'y a pas que le facteur commun comme méthode de factorisation) :
> - $(2x+1)(6x-6) + (2x+1)(5x-4) = 0$
> - $(3x-6)(5x-3)-(3x-6)(3x+9) = 0$
> - $x^2+4x+1 = 0$
> - $(2x+6)^2 - (6x+2)^2 = 0$

### Équation du type $x^2 = a$

> [!propriete] Propriété
> L'équation $x^2 = a$ :
> - Si $a<0$ n'a pas de solution.
> - Si $a = 0$ a une seule solution : 0.
> - Si $a > 0$ a deux solutions : $\sqrt{a}$ et $-\sqrt{a}$.

> [!exercice] Exercice 4
> Prouver la propriété précédente à l'aide de l'identité remarquable $a^2-b^2 = (a+b)(a-b)$.

> [!exercice] Exercice 5
> Résoudre les équations suivantes :
> - $x^2 = 25$
> - $x^2 + 5 = 7$
> - $x^2 +49 = 0$
> - $3x^2 = 147$

## Inéquations

### Représentation d'un ensemble de nombres

Afin de représenter un ensemble de nombres, on peut utiliser un axe. En voici quelques exemples :

![[axe.png]]

> [!remarque] Remarque
> La notation sous forme d'intervalle est du programme de seconde.

> [!exercice] Exercice 6
> Représenter à l'aide d'un axe l'ensemble des nombres suivants :
> - $x>5$
> - $x \ge 4$
> - $-3 \le x \le 2$
> - $-3 < x \le 0$
> - $x<10$
> - $x>-4$

Cette représentation va nous être utile pour représenter les solutions d'une inéquation.

### Résolution d'une inéquation

Pour résoudre une inéquation, on utilise les mêmes règles que pour une équation. Mais on en rajoute une.

> [!propriete] Propriété
> Dans une inéquation, si on multiplie ou on divise les deux membres d'une inéquation par un nombre négatif, on inverse le sens de l'inégalité.

> [!exemple] Exemple
> Dans un premier temps, on utilise les règles classiques afin d'isoler $x$.
>
> $2x-4 > 6x -2$
>
> $2x-4 \colorbox{fond3}{$+4$} > 6x -2 \colorbox{fond3}{$+4$}$
>
> $2x > 6x +2$
>
> $2x \colorbox{fond3}{$-6x$} > 6x +2 \colorbox{fond3}{$-6x$}$
>
> $-4x > 2$
>
> $\dfrac{-4x}{\colorbox{fond3}{$-4$}} < \dfrac{2}{\colorbox{fond3}{$-4$}}$
>
> $x<-\dfrac{1}{2}$

> [!exercice] Exercice 7
> Résoudre les inéquations suivantes puis représenter l'ensemble des solutions sur un axe.
> - $5-2x \ge 7$
> - $3x-2>x-4$
> - $-4x+\dfrac{1}{2} \le -9$
> - $x+5 \le 4(x+1)+7$
> - $\dfrac{3x-2}{4} \le -2$
> - $\dfrac{5x+1}{6}>\dfrac{3x-3}{8}$
