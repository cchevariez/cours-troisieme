---
chapitre: 3
tags:
  - maths/troisieme
---

# Le développement

## La distributivité

Développer, c'est **réécrire** une expression sous une autre forme. Ce n'est pas un calcul, c'est une transformation d'écriture. On l'apprend d'abord avec des **formes**, sans aucun nombre ni lettre : c'est le geste qui compte.

### Temps 1 — le principe, avec des formes

#### Le schéma

![[schema_distributivite.svg|800]]

> [!demonstration] Le schéma en mouvement
> ![[schema_distributivite.mp4]]

> [!propriete] Principe
> Un facteur devant une parenthèse :
> $$\square \times (\bigcirc + \triangle) = \square\times\bigcirc + \square\times\triangle$$
> Deux facteurs :
> $$(\square + \lozenge) \times (\bigcirc + \triangle) = \square\times\bigcirc + \square\times\triangle + \lozenge\times\bigcirc + \lozenge\times\triangle$$
>
> **Chaque forme de gauche multiplie chaque forme de la parenthèse.**

#### S'entraîner avec les formes

> [!exercice] Exercice 1
> Développer les expressions suivantes :
> - $\lozenge \times (\bigcirc + \triangle)$
> - $\triangle \times (\square + \bigcirc)$
> - $(\square + \lozenge) \times (\bigcirc + \triangle)$
> - $(\bigcirc + \triangle) \times (\lozenge + \square)$

> [!demonstration] Correction animée
> ![[dev_formes.mp4]]

> [!exercice] Exercice 2
> Développer les expressions suivantes :
> - $\bigcirc \times (\square + \triangle)$
> - $\square \times (\square + \bigcirc)$
> - $(\lozenge + \triangle) \times (\square + \bigcirc)$

### Temps 2 — le même principe, avec des nombres et des lettres

Le geste est acquis avec les formes. On remplace maintenant chaque forme par un nombre ou une lettre : **le développement est exactement le même**.

| Avec des formes | Avec des lettres | Avec des nombres |
|---|---|---|
| $\square \times (\bigcirc + \triangle)$ | $k \times (a + b)$ | $3 \times (x + 4)$ |
| $\square\times\bigcirc + \square\times\triangle$ | $k\times a + k\times b$ | $3\times x + 3\times 4$ |
| | | $= 3x + 12$ |

> [!propriete] Propriété — Distributivité
> Pour tous nombres $k,a,b,c$ et $d$ :
> $$k(a+b) = k \times a + k \times b$$
> $$(a+b)(c+d) = ac + ad + bc + bd$$

> [!demonstration] Le schéma, avec des lettres
> ![[distributivite_simple.mp4]]
>
> ![[distributivite_double.mp4]]

On peut aussi voir la double distributivité comme un calcul d'aire :

![[doubled.png|360]]

#### Développer (facteurs positifs)

> [!methode] Méthode — Développer
> 1. Repérer la forme : un seul terme devant la parenthèse ($k(a+b)$) ou une somme ($(a+b)(c+d)$).
> 2. Distribuer selon le schéma : chaque terme de gauche multiplie chaque terme de la parenthèse.
> 3. Réduire (regrouper les termes semblables).

> [!exercice] Exercice 3
> Développer et réduire les expressions suivantes :
> - $3(x+4)$
> - $2x(x+5)$
> - $(x+2)(x+3)$
> - $(2x+1)(x+4)$

> [!demonstration] Correction animée
> ![[dev_positif.mp4]]

> [!exercice] Exercice 4
> Développer et réduire les expressions suivantes :
> - $5(2x+3)$
> - $x(3x+7)$
> - $(x+4)(2x+1)$
> - $(3x+2)(x+5)$

#### Réécrire les soustractions

Dès qu'une parenthèse contient une soustraction, on **réécrit d'abord** l'expression pour n'avoir que des additions — avec l'outil du chapitre 1 : $a - b = a + (-b)$.

> [!methode] Méthode — Réécrire avant de développer
> Tant qu'il reste une soustraction, on la remplace par une addition : $a - b = a + (-b)$.
> On obtient une expression qui ne contient que des additions ; certains termes sont des nombres négatifs. On peut alors appliquer le schéma comme d'habitude.

> [!exercice] Exercice 5
> Réécrire chaque expression avec uniquement des additions. **Ne pas développer.**
> - $2x(4x-3)$
> - $-3(5x-4)$
> - $(2x-3)(x-5)$
> - $(-x+4)(3x-2)$

> [!demonstration] Correction animée
> ![[reecriture_soustraction.mp4]]

> [!exercice] Exercice 6
> Réécrire chaque expression avec uniquement des additions.
> - $-5(2x-7)$
> - $-x(3x-4)$
> - $(3x-1)(2x-4)$
> - $-2x(-x+5)$

#### Développer (avec des soustractions)

> [!methode] Méthode — Développer une expression avec des soustractions
> 1. Réécrire les soustractions en additions.
> 2. Distribuer selon le schéma.
> 3. Calculer chaque produit (règle des signes : un produit par un nombre négatif est un produit par $(-1)$, chapitre 1).
> 4. Réduire.

> [!exercice] Exercice 7
> Développer et réduire les expressions suivantes :
> - $2x(4x-3)$
> - $-3(5x-4)$
> - $(2x-3)(x-5)$
> - $(-x+4)(3x-2)$

> [!demonstration] Correction animée
> ![[dev_soustraction.mp4]]

> [!exercice] Exercice 8
> Développer et réduire les expressions suivantes :
> - $4(2x+3)-5(x-1)$
> - $5x(x-3)+2x(4-x)$
> - $(3x-2)(x+5)-(x-1)(2x+3)$
> - $-2(6x-1)(2x+3)$

## Identités remarquables

> [!propriete] Propriété
> Les identités remarquables sont trois développements particuliers à connaître :
> 1. $(a+b)^2 = a^2 + 2ab + b^2$
> 2. $(a-b)^2 = a^2 - 2ab + b^2$
> 3. $(a+b)(a-b) = a^2 - b^2$

> [!exercice] Exercice 9
> Retrouver à l'aide de la double distributivité les identités remarquables.

> [!exercice] Exercice 10
> À l'aide des identités remarquables, développer les expressions suivantes :
> 1. $(3x+2)^2$
> 2. $(2x-3)^2$
> 3. $(6x-4)(6x+4)$

## Les méthodes

> [!methode] Méthode — Tester une égalité pour des valeurs données
> On peut tester l'égalité entre deux expressions littérales pour certaines valeurs de $x$. Pour ce faire il suffit de remplacer $x$ par la valeur souhaitée et calculer la valeur numérique de chacune des expressions puis de les comparer.

> [!Exercice] Exercice 11
> Soit deux expressions $A = 2x^2 - 2x +4$ et $B = 4x$. Vérifier si $A$ et $B$ sont égales pour $x = 1$ et $x = 2$.

> [!methode] Méthode — Prouver que deux expressions littérales ne sont pas égales pour toutes les valeurs de $x$
> Pour ce faire, il suffit de trouver une valeur de $x$ pour laquelle les deux expressions ne sont pas égales.

> [!Exercice] Exercice 12
> Prouver que $A = 2x^2 -2x + 4$ et $B = 4x$ ne sont pas égales.

> [!methode] Méthode — Prouver que deux expressions littérales sont égales
> Pour prouver que deux expressions sont égales, il suffit de prouver qu'elles ont la même écriture développée réduite.

> [!exercice] Exercice 13
> Prouver que les expressions $A = (2x+3)^2 - 4x^2$ et $B = 3(4x+3)$ sont égales.

> [!methode] Méthode — Utiliser les identités remarquables pour factoriser
> Pour le moment, on a utilisé les identités remarquables pour développer des expressions mais on peut les utiliser aussi dans l'autre sens pour factoriser.
>
> ![[iddevfac.png|300]]

> [!Exercice] Exercice 14
> À l'aide des identités remarquables, factoriser les expressions suivantes :
> 1. $A = 9x^2 + 12x + 4$
> 2. $B = 4x^2 - 36$
> 3. $C = 4x^2 - 16x + 16$
