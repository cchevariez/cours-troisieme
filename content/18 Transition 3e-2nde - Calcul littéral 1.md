---
chapitre: 18
tags:
  - maths/troisieme
  - transition-3-2
---

# Transition 3e→2nde : Calcul littéral 1

## Résolution d'équation

Une équation représente une situation d'équilibre entre deux membres.
- Le membre de droite (situé à droite du $=$)
- Le membre de gauche (situé à gauche du $=$)

On note dans une équation la présence d'une inconnue (élément dont on ne connaît pas la valeur) symbolisée par une lettre, le plus souvent $x$.

Résoudre une équation consiste à déterminer la ou les valeurs de $x$. Pour résoudre une équation il y a **une seule règle** : afin de conserver l'égalité et donc l'équilibre, toute opération effectuée sur un membre de l'équation doit aussi être effectuée sur l'autre membre.

> [!exercice] Exercice 1
> Déterminer les opérations à effectuer pour résoudre chacune de ces équations :
> 1. $6x = 24$
> 2. $\dfrac{x}{4} = 12$
> 3. $x-6 = 24$
> 4. $x + 4 = 24$

> [!remarque] Remarque
> Dans l'exercice précédent une seule opération suffisait. Voyons maintenant des équations un peu plus complexes.

> [!exercice] Exercice 2
> Déterminer les opérations à effectuer pour résoudre chacune de ces équations :
> 1. $6x - 4 = 24$
> 2. $\dfrac{x}{4} + 4 = 22$
> 3. $-2x-6 = 24$
> 4. $7x - 4 = 24$

> [!remarque] Remarque
> Nous pouvons encore complexifier les équations mais le principe reste toujours le même. Je vous le rappelle : toute opération est valide tant que vous l'appliquez aux deux membres de l'équation.

> [!exercice] Exercice 3
> Résoudre les équations suivantes :
> 1. $6(x - 4) + 12 = 24$
> 2. $\dfrac{x}{4} + \dfrac{x}{3} = 22$
> 3. $-2x-6 = 6x+24$
> 4. $7x - 4 - 2(x+3) = -6x + 24$

## Développement

### La distributivité simple

> [!propriete] Propriété
> Pour tous nombres $k,a$ et $b$ :
> $$k \times (a+b) = k \times a + k \times b$$
> $$k \times (a-b) = k \times a - k \times b$$

> [!exercice] Exercice 4
> Développer et réduire les expressions suivantes :
> - $3,5(2x+3) = \ldots$
> - $-6(-5x+3)= \ldots$
> - $-2(5x-4)+3x-2= \ldots$

### La double distributivité

> [!propriete] Propriété
> Pour tous nombres $a,b,c$ et $d$ :
> $$(a+b)\times(c+d) = ac + ad + bc + bd$$
>
> ![[doubled.png]]

> [!exercice] Exercice 5
> Développer les expressions suivantes :
> - $A = (2x+3)\times(6x-2)$
> - $(-5x+3)\times(2x-3)$

> [!exercice] Exercice 6
> Développer les expressions suivantes :
> - $A = -3(x+4) + (2x-6)(-8x + 4)$
> - $B = 7(4x-4) - 8(-4x-2)$
> - $C = (6x-6)(-2x+3) + (6x+2)(-2x-1)$
> - $D = -2(6x-1)(2x+3)$
> - $E = 6x^2 +4x -(4x^2+2x-6)$

## Factorisation

La factorisation est l'opération inverse du développement. Elle va nous permettre de simplifier très fortement des expressions.

> [!propriete] Propriété
> Pour tous nombres $k,a$ et $b$ :
> $$k \times a + k \times b = k \times (a+b)$$
> $$k \times a - k \times b = k \times (a-b)$$
> $k$ est appelé le facteur commun.

> [!exercice] Exercice 7
> Cette expression est factorisable par $(n+2)$. À vous de jouer.
> $$A=\frac{5n+10}{5} + 2(n+2)$$

> [!exercice] Exercice 8
> Factoriser les expressions suivantes :
> - $A = 3(x+2) + 6x + 12$
> - $B = 6(3x-4) + 12x - 16$
> - $C = \dfrac{12x-4}{7} + 3x-1$

> [!exercice] Exercice 9
> Factoriser les expressions suivantes :
> 1. $(3x+7)(2x-4)+(3x+7)(4x+2)$
> 2. $(2x-5)^2-(2x-5)(6x-1)$
> 3. $6x(x-2)-(x-2)(x-3)$
> 4. $(15x-5)(2x+9)-(3x-1)(4x-1)$
> 5. $(3x-7)(3x+7)-(3x-7)(2x+11)$
> 6. $(x-2)^2-(x-2)(3x+4)$

## Méthode des identités remarquables

> [!methode] Méthode — Des identités remarquables
> Lorsque l'on ne repère pas un facteur commun, il peut y avoir une identité remarquable :
> $$\boxed{a^2+2ab+b^2=(a+b)^2}$$
> $$\boxed{a^2-2ab+b^2=(a-b)^2}$$
> $$\boxed{a^2-b^2=(a+b)(a-b)}$$
> Il s'agit alors de repérer quelle identité utiliser puis d'identifier $a$ et $b$ pour factoriser en utilisant les formules ci-dessus.

Poursuivons avec quelques exemples :

> [!exemple] Exemple
> Factorisons les expressions suivantes :
> 1. $x^2-22x+121$. On reconnaît la deuxième identité remarquable avec $a^2=x^2$ donc $a=x$ puis $2 \times a \times b=2 \times x \times 11$ donc $b=11$. Il reste alors $121$ qui correspond bien à $11^2$. Nous pouvons par conséquent écrire : $$x^2-22x+121=(x-11)^2$$
> 2. $36x^2-64$. Après avoir remarqué que $36x^2$ n'est pas un carré (seul le $x$ est mis au carré), on écrit : $$36x^2-64=(6x)^2-8^2=(6x-8)(6x+8) \text{ en utilisant la troisième identité}$$
> 3. $9x^2+24x+16=(3x)^2+2 \times 3x \times 4+4^2=(3x+4)^2$

Ces exemples sont volontairement largement détaillés. Rien ne vous empêchera lors de vos examens de laisser moins d'étapes de calculs (si toutefois vous n'écrivez pas directement le résultat).

> [!exercice] Exercice 10
> Factoriser les expressions suivantes :
> 1. $A(x)=9x^2+42x+49$
> 2. $B(x)=25x^2-60x+36$
> 3. $C(x)=9x^2-64$
