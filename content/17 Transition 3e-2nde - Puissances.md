---
chapitre: 17
tags:
  - maths/troisieme
  - transition-3-2
---

# Transition 3e→2nde : Puissances

## Définitions et notations

> [!definition] Définition — Puissance
> $a$ désigne un nombre relatif et $n$ un nombre entier. Le produit $\underbrace{a \times a \times \ldots \times a}_{\textrm{n fois}}$ de $n$ facteurs égaux à $a$ est une puissance de $a$ et est notée $a^n$.

> [!remarque] Remarque
> Voici quelques cas particuliers :
> - $a^0 = 1$
> - $a^1 = a$
> - $a^2$ se lit « $a$ au carré »
> - $a^3$ se lit « $a$ au cube »

> [!exercice] Exercice 1
> Calculer les puissances suivantes :
> - $3^5$
> - $(-2)^3$
> - $10^4$

> [!definition] Définition — Puissance d'un exposant négatif
> $a$ désigne un nombre relatif non nul et $n$ un entier. $a^{-n}$ désigne l'inverse de $a^n$ :
> $$a^{-n} = \frac{1}{a^n}$$

> [!remarque] Remarque
> $a^{-1} = \dfrac{1}{a^1}= \dfrac{1}{a}$

> [!exercice] Exercice 2
> Calculer les puissances suivantes :
> - $3^{-2}$
> - $(-2)^{-3}$
> - $10^{-4}$

## Règles de calcul

> [!propriete] Propriété
> Soit $a$ et $b$ deux nombres et $n$ et $p$ deux entiers, alors :
> - $a^n \times a^p = a^{n+p}$
> - $(a^n)^p = a^{n \times p}$
> - $(a \times b)^n = a^n \times b^n$
> - $\left(\dfrac{a}{b} \right)^n = \dfrac{a^n}{b^n}$
> - $\dfrac{a^n}{a^p} = a^{n-p}$

> [!exercice] Exercice 3
> Écrire sous la forme d'une puissance de 5 :
> - $A = 5^4 \times 5^2$
> - $B = 5^5 \times 5^{-2}$
> - $C = \dfrac{5^5}{5^{3}}$
> - $D = (5^4)^4$
> - $E = (5^{-4})^3$
> - $F = \dfrac{5^7\times 5^{-3}}{5^2 \times 5^5}$

## Écriture scientifique

> [!definition] Définition — Écriture scientifique
> Écrire un nombre décimal en écriture scientifique, c'est l'écrire sous la forme suivante :
> $$a\times 10^n$$
> avec $a$ un nombre décimal compris entre 1 et 10 (exclu) et $n$ un entier relatif.

> [!exemple] Exemple
> Voici quelques exemples d'écriture scientifique :
> - $200 = 2 \times 100 = 2\times 10^2$
> - $3500 = 3,5 \times 1000 = 3,5 \times 10^3$
> - $25\,800\,000 = 2,58 \times 10\,000\,000 = 2,58\times 10^7$
> - $0,02 = 2 \times 0,01 = 2 \times 10^{-2}$
> - $0,00038 = 3,8 \times 0,0001 = 3,8 \times 10^{-4}$

> [!exercice] Exercice 4
> Convertir les nombres suivants en écriture scientifique :
> - 458 000 000
> - 0,00000546
> - 25

> [!exercice] Exercice 5
> Effectuer les calculs suivants et donner le résultat sous forme d'écriture scientifique.
> - $A = 2,8 \times 10^6 \times 3 \times 10^{12}$
> - $B = \dfrac{4,2 \times 10^4}{3 \times 10^{-5}}$

## Problèmes

**Sans calculatrice**

> [!exercice] Exercice 6
> L'aire globale de la Terre est d'environ $5\times 10^8$ $km^2$. L'aire des océans est d'environ $3,5 \times 10^8$ $km^2$.
> 1. Déterminer la surface de terre émergée.
> 2. Déterminer le pourcentage que représentent les océans par rapport à la surface globale de la Terre.

> [!exercice] Exercice 7
> À la naissance, notre cerveau est constitué d'environ cent milliards de neurones, chacun d'entre eux étant connecté à dix mille de ses semblables.
> 1. Écrire le nombre de neurones d'un cerveau de nouveau-né en écriture scientifique.
> 2. Déterminer le nombre de connexions dans un cerveau. Le résultat sera donné en écriture scientifique.

Les notions de racine carrée et de puissance sont étroitement liées. Nous rappellerons donc dans un premier temps les propriétés des puissances.

## La racine carrée

> [!definition] Définition — Racine carrée
> Pour un nombre $a \geq 0$, on note $a^{\frac{1}{2}} = \sqrt{a}$.

> [!remarque] Remarque
> Faisons un petit retour sur le théorème de Pythagore. Lorsqu'à la fin de l'utilisation de ce théorème vous tombiez sur :
> $$AB^2 = 12$$
> alors on trouvait :
> $$AB = \sqrt{12}$$
> Maintenant que vous êtes plus savants, nous allons voir pourquoi et comment ça marche. Faisons la même opération mais avec plus d'étapes pour comprendre : une égalité reste vraie si on applique les mêmes modifications sur les deux membres (côtés) de l'égalité.
> $$AB^2 = 12$$
> $$\sqrt{AB^2} = \sqrt{12}$$
> $$(AB^2)^{\frac{1}{2}} = \sqrt{12}$$
> $$AB^{2\times\frac{1}{2}} = \sqrt{12}$$
> $$AB^1 = \sqrt{12}$$
> $$AB = \sqrt{12}$$
> Tous ces détails de rédaction sont évidemment superflus dans le cas d'une résolution d'exercice, mais ils vous permettent de comprendre comment la racine carrée permet de faire « disparaître » le carré.

Maintenant que vous savez qu'une racine carrée est une puissance, la racine carrée hérite donc de toutes les propriétés des puissances. Nous allons donc reprendre les propriétés et les appliquer à la racine carrée :

> [!propriete] Propriété
> Voici les propriétés fondamentales des puissances appliquées aux racines carrées :
> 1. $a^n \times b^n = (ab)^n$ pour les racines carrées on a donc : $\sqrt{a} \times \sqrt{b} = a^{\frac{1}{2}} \times b^{\frac{1}{2}} = (ab)^{\frac{1}{2}} = \sqrt{ab}$
> 2. $(a^n)^p = a^{n \times p}$ pour les racines carrées on a donc : $(\sqrt{a})^2 = (a^{\frac{1}{2}})^2 = a^{\frac{1}{2} \times 2} = a^1 = a$

> [!exemple] Exemple
> Voici quelques exemples d'utilisation de ces propriétés :
> - On peut multiplier deux racines carrées : $$\sqrt{3} \times \sqrt{5} = \sqrt{3 \times 5} = \sqrt{15}$$
> - Développons $A = (\sqrt{3}+\sqrt{7})^2$ :
>     $$A = (\sqrt{3}+\sqrt{7})^2$$
>     $$A = (\sqrt{3})^2+ 2\times\sqrt{3}\times\sqrt{7} +(\sqrt{7})^2$$
>     $$A = 3 + 2\times\sqrt{3\times 7} + 7$$
>     $$A = 10 + 2\sqrt{21}$$
> - On peut simplifier l'écriture d'une racine carrée en faisant apparaître des carrés grâce à la décomposition : $$\sqrt{75} = \sqrt{5\times5\times3} = \sqrt{5^2 \times 3} = \sqrt{5^2} \times \sqrt{3} = 5\sqrt{3}$$

> [!exercice] Exercice 8
> Simplifier le plus possible les racines suivantes :
> 1. $\sqrt{192}$
> 2. $\sqrt{162}$
> 3. $\sqrt{175}$

> [!exercice] Exercice 9
> Développer les expressions suivantes :
> 1. $A = (\sqrt{2}-\sqrt{7})^2$
> 2. $B = (x-\sqrt{7})^2$
> 3. $C = (\sqrt{2}x-\sqrt{7})^2$
> 4. $D = (\sqrt{2}-\sqrt{7})(\sqrt{2}+\sqrt{7})$
