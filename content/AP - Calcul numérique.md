---
tags:
  - maths/troisieme
---

# AP - Calcul numérique

**Objectif :** revoir les priorités opératoires (l'ordre dans lequel on effectue les calculs), à raison d'un exercice court chaque jour pendant 10 jours. Compte 10 à 15 minutes par jour.

> [!methode] Méthode — Priorités opératoires
> Dans un calcul, on effectue dans l'ordre : 1) les parenthèses, 2) les puissances, 3) les multiplications et divisions (de gauche à droite), 4) les additions et soustractions (de gauche à droite).

## Jour 1 — Sans parenthèses

> [!exemple] Exemple
> $$E = 5 + 3 \times 4$$
>
> $$E = 5 + 12$$
>
> $$E = 17$$

> [!exercice] Jour 1 (10-15 min)
> Calculer :
> - $A = 6 + 4 \times 5$
> - $B = 20 - 3 \times 4$
> - $C = 2 \times 6 + 3 \times 5$

> [!correction]- Correction — Jour 1
> - $$A = 6 + 4 \times 5$$
> - $$A = 6 + 20$$
> - $$A = 26$$
> - $$B = 20 - 3 \times 4$$
> - $$B = 20 - 12$$
> - $$B = 8$$
> - $$C = 2 \times 6 + 3 \times 5$$
> - $$C = 12 + 3 \times 5$$
> - $$C = 12 + 15$$
> - $$C = 27$$

## Jour 2 — Sans parenthèses (renforcement)

> [!exercice] Jour 2 (10-15 min)
> Calculer :
> - $A = 30 - 2 \times 9 + 4$
> - $B = 5 \times 3 + 4 \times 2 - 6$
> - $C = 18 \div 3 + 5 \times 2$

> [!correction]- Correction — Jour 2
> - $$A = 30 - 2 \times 9 + 4$$
> - $$A = 30 - 18 + 4$$
> - $$A = 12 + 4$$
> - $$A = 16$$
> - $$B = 5 \times 3 + 4 \times 2 - 6$$
> - $$B = 15 + 4 \times 2 - 6$$
> - $$B = 15 + 8 - 6$$
> - $$B = 23 - 6$$
> - $$B = 17$$
> - $$C = 18 \div 3 + 5 \times 2$$
> - $$C = 6 + 5 \times 2$$
> - $$C = 6 + 10$$
> - $$C = 16$$

> [!demonstration]- Correction animée — méthode
> ![[ap_numerique_priorites_base.mp4]]

## Jour 3 — Parenthèses simples

> [!exemple] Exemple
> $$E = (5 + 3) \times 4$$
>
> $$E = 8 \times 4$$
>
> $$E = 32$$
>
> Les parenthèses imposent de calculer $5+3$ avant de multiplier.

> [!exercice] Jour 3 (10-15 min)
> Calculer :
> - $A = (9 - 4) \times 6$
> - $B = 8 \times (3 + 5) - 7$
> - $C = (12 - 7) \times (6 - 2)$

> [!correction]- Correction — Jour 3
> - $$A = (9 - 4) \times 6$$
> - $$A = 5 \times 6$$
> - $$A = 30$$
> - $$B = 8 \times (3 + 5) - 7$$
> - $$B = 8 \times 8 - 7$$
> - $$B = 64 - 7$$
> - $$B = 57$$
> - $$C = (12 - 7) \times (6 - 2)$$
> - $$C = 5 \times (6 - 2)$$
> - $$C = 5 \times 4$$
> - $$C = 20$$

## Jour 4 — Parenthèses imbriquées

> [!exemple] Exemple
> $$E = 3 \times \big(5 + (9 - 4)\big)$$
>
> $$E = 3 \times (5 + 5)$$
>
> $$E = 3 \times 10$$
>
> $$E = 30$$
>
> On calcule toujours la parenthèse la plus à l'intérieur en premier.

> [!exercice] Jour 4 (10-15 min)
> Calculer :
> - $A = 2 \times \big(7 + (10 - 6)\big)$
> - $B = \big(15 - (4 + 3)\big) \times 3$
> - $C = 5 + \big(2 \times (8 - 5)\big)$

> [!correction]- Correction — Jour 4
> - $$A = 2 \times \big(7 + (10 - 6)\big)$$
> - $$A = 2 \times (7 + 4)$$
> - $$A = 2 \times 11$$
> - $$A = 22$$
> - $$B = \big(15 - (4 + 3)\big) \times 3$$
> - $$B = (15 - 7) \times 3$$
> - $$B = 8 \times 3$$
> - $$B = 24$$
> - $$C = 5 + \big(2 \times (8 - 5)\big)$$
> - $$C = 5 + (2 \times 3)$$
> - $$C = 5 + 6$$
> - $$C = 11$$

## Jour 5 — Puissances et priorités

> [!exemple] Exemple
> $$E = 2 + 3^2 \times 2$$
>
> $$E = 2 + 9 \times 2$$
>
> $$E = 2 + 18$$
>
> $$E = 20$$
>
> On calcule d'abord la puissance, avant la multiplication.

> [!exercice] Jour 5 (10-15 min)
> Calculer :
> - $A = 4 + 2^3 \times 3$
> - $B = 5^2 - 3 \times 4$
> - $C = (2 + 3)^2 - 10$

> [!correction]- Correction — Jour 5
> - $$A = 4 + 2^3 \times 3$$
> - $$A = 4 + 8 \times 3$$
> - $$A = 4 + 24$$
> - $$A = 28$$
> - $$B = 5^2 - 3 \times 4$$
> - $$B = 25 - 3 \times 4$$
> - $$B = 25 - 12$$
> - $$B = 13$$
> - $$C = (2 + 3)^2 - 10$$
> - $$C = 5^2 - 10$$
> - $$C = 25 - 10$$
> - $$C = 15$$

## Jour 6 — Nombres relatifs

> [!exemple] Exemple
> $$E = -8 + 3 \times (-4)$$
>
> $$E = -8 + (-12)$$
>
> $$E = -20$$
>
> Le produit se calcule avant l'addition, comme d'habitude.

> [!exercice] Jour 6 (10-15 min)
> Calculer :
> - $A = -9 + 4 \times (-3)$
> - $B = -5 \times (-6) + 2$
> - $C = 7 - 3 \times (-4)$

> [!correction]- Correction — Jour 6
> - $$A = -9 + 4 \times (-3)$$
> - $$A = -9 + (-12)$$
> - $$A = -21$$
> - $$B = -5 \times (-6) + 2$$
> - $$B = 30 + 2$$
> - $$B = 32$$
> - $$C = 7 - 3 \times (-4)$$
> - $$C = 7 - (-12)$$
> - $$C = 7 + 12$$
> - $$C = 19$$

## Jour 7 — Relatifs et parenthèses (attention au piège)

> [!exemple] Exemple
> $$E = -10 - (3 - 8)$$
>
> $$E = -10 - (-5)$$
>
> $$E = -10 + 5$$
>
> $$E = -5$$
>
> Piège classique : $-(-5) = +5$, pas $-5$. Soustraire une parenthèse, c'est ajouter son opposé.

> [!exercice] Jour 7 (10-15 min)
> Calculer :
> - $A = -12 - (4 - 9)$
> - $B = -6 \times \big(5 - 2 \times (-3)\big)$
> - $C = -15 - \big(2 \times (-4) - (6 - 9)\big)$

> [!correction]- Correction — Jour 7
> - $$A = -12 - (4 - 9)$$
> - $$A = -12 - (-5)$$
> - $$A = -12 + 5$$
> - $$A = -7$$
> - $$B = -6 \times \big(5 - 2 \times (-3)\big)$$
> - $$B = -6 \times \big(5 - (-6)\big)$$
> - $$B = -6 \times 11$$
> - $$B = -66$$
> - $$C = -15 - \big(2 \times (-4) - (6 - 9)\big)$$
> - $$C = -15 - \big(-8 - (-3)\big)$$
> - $$C = -15 - (-5)$$
> - $$C = -15 + 5$$
> - $$C = -10$$

> [!demonstration]- Correction animée — méthode
> ![[ap_numerique_signe_parenthese.mp4]]

## Jour 8 — Mélange complet

> [!exercice] Jour 8 (10-15 min)
> Calculer :
> - $A = -4 \times \big(9 - 3 \times (-2)\big)$
> - $B = 2^3 - 5 \times (-2) + 1$
> - $C = -20 - \big(3 \times (-5) - (4 - 10)\big)$

> [!correction]- Correction — Jour 8
> - $$A = -4 \times \big(9 - 3 \times (-2)\big)$$
> - $$A = -4 \times \big(9 - (-6)\big)$$
> - $$A = -4 \times 15$$
> - $$A = -60$$
> - $$B = 2^3 - 5 \times (-2) + 1$$
> - $$B = 8 - 5 \times (-2) + 1$$
> - $$B = 8 - (-10) + 1$$
> - $$B = 8 + 10 + 1$$
> - $$B = 19$$
> - $$C = -20 - \big(3 \times (-5) - (4 - 10)\big)$$
> - $$C = -20 - \big(-15 - (-6)\big)$$
> - $$C = -20 - (-9)$$
> - $$C = -20 + 9$$
> - $$C = -11$$

## Jour 9 — Consolidation

> [!exercice] Jour 9 (10-15 min)
> Calculer :
> - $A = -3 \times \big(8 - 2 \times (-4)\big)$
> - $B = 3^2 - 6 \times (-3) + 2$
> - $C = -18 - \big(4 \times (-3) - (5 - 11)\big)$

> [!correction]- Correction — Jour 9
> - $$A = -3 \times \big(8 - 2 \times (-4)\big)$$
> - $$A = -3 \times \big(8 - (-8)\big)$$
> - $$A = -3 \times 16$$
> - $$A = -48$$
> - $$B = 3^2 - 6 \times (-3) + 2$$
> - $$B = 9 - 6 \times (-3) + 2$$
> - $$B = 9 - (-18) + 2$$
> - $$B = 9 + 18 + 2$$
> - $$B = 29$$
> - $$C = -18 - \big(4 \times (-3) - (5 - 11)\big)$$
> - $$C = -18 - \big(-12 - (-6)\big)$$
> - $$C = -18 - (-6)$$
> - $$C = -18 + 6$$
> - $$C = -12$$

## Jour 10 — Bilan (type brevet, en autonomie)

> [!exercice] Jour 10 (10-15 min)
> Calculer :
> - $A = -14 + 6 \times (-3)$
> - $B = -5 \times \big(16 - 4 \times (-2)\big)$
> - $C = -11 - \big(3 \times (-4) - (5 - 9)\big)$
> - $D = 2^3 + 3 \times (-5) - 4$

> [!correction]- Correction — Jour 10
> - $$A = -14 + 6 \times (-3)$$
> - $$A = -14 + (-18)$$
> - $$A = -32$$
> - $$B = -5 \times \big(16 - 4 \times (-2)\big)$$
> - $$B = -5 \times \big(16 - (-8)\big)$$
> - $$B = -5 \times 24$$
> - $$B = -120$$
> - $$C = -11 - \big(3 \times (-4) - (5 - 9)\big)$$
> - $$C = -11 - \big(-12 - (-4)\big)$$
> - $$C = -11 - (-8)$$
> - $$C = -11 + 8$$
> - $$C = -3$$
> - $$D = 2^3 + 3 \times (-5) - 4$$
> - $$D = 8 + 3 \times (-5) - 4$$
> - $$D = 8 + (-15) - 4$$
> - $$D = -7 - 4$$
> - $$D = -11$$
