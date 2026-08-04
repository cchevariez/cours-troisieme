---
chapitre: 4
tags:
  - maths/troisieme
---

# Arithmétique

## Division euclidienne

> [!definition] Définition — Les entiers naturels
> Un nombre entier naturel est un nombre positif sans partie décimale. L'ensemble des entiers naturels est noté $\mathbb{N}$.
> $$\mathbb{N} = \{0;1;2;3;\ldots\}$$

> [!definition] Définition — Division euclidienne
> Effectuer la division euclidienne d'un entier $a$ (le dividende) par un entier $b$ (le diviseur) non nul, c'est trouver deux entiers $q$ (le quotient) et $r$ (le reste) tels que :
> $$a = b \times q + r$$
> avec $r<b$

> [!exemple] Exemple
> Division euclidienne de 185 par 7.
>
> ![[diveucl.png]]
>
> Soit $185 = 7 \times 26 + 3$

> [!exercice] Exercice 1
> Effectuer les divisions euclidiennes suivantes et donner l'égalité correspondante :
> 1. 127 divisé par 9
> 2. 246 divisé par 13
> 3. 589 divisé par 17
> 4. 1007 divisé par 23

## Multiples et diviseurs

> [!definition] Définition — Multiple et diviseur
> Un nombre entier $a$ est un multiple d'un nombre entier $b$ non nul lorsque le reste de la division euclidienne de $a$ par $b$ est 0.
> - On dit que $b$ est un diviseur de $a$ ou que $a$ est divisible par $b$.
> - Si l'entier $b$ divise l'entier $a$ il existe donc un entier $q$ tel que : $a = b \times q$.

> [!exercice] Exercice 2
> Compléter les phrases suivantes par les mots « multiple » ou « diviseur » :
> 1. 15 est un __________ de 3
> 2. 7 est un __________ de 56
> 3. 24 est un __________ de 8
> 4. 9 est un __________ de 63

> [!propriete] Propriété — Critères de divisibilité
> Voici les principaux critères de divisibilité :
> - Un entier est divisible par 2 quand il est pair donc quand son chiffre des unités est 0, 2, 4, 6 ou 8. Par exemple 110 est divisible par 2.
> - Un entier est divisible par 3 quand la somme de ses chiffres est divisible par 3. Par exemple 114 est divisible par 3 car 1+1+4 = 6 et 6 est divisible par 3.
> - Un entier est divisible par 5 quand son chiffre des unités est 0 ou 5. Par exemple 110 est divisible par 5.
> - Un entier est divisible par 9 quand la somme de ses chiffres est divisible par 9. Par exemple 494 est divisible par 9 car 4+9+5 = 18 et 18 est divisible par 9.
> - Un entier est divisible par 10 quand son chiffre des unités est 0. Par exemple 110 est divisible par 10.

> [!exercice] Exercice 3
> En utilisant les critères de divisibilité, indiquer si les nombres suivants sont divisibles par 2, 3, 5, 9 ou 10 :
> 1. 246
> 2. 1275
> 3. 5634
> 4. 7290

## Nombres premiers et décomposition en facteurs premiers

> [!definition] Définition — Nombres premiers
> Un nombre premier est un nombre qui n'a que deux diviseurs : 1 et lui-même.

> [!exercice] Exercice 4
> Dire si les nombres suivants sont premiers ou non. S'ils ne sont pas premiers, donner au moins un diviseur autre que 1 et lui-même :
> 1. 17
> 2. 21
> 3. 29
> 4. 33
> 5. 41

> [!exercice] Exercice 5
> Il y a 25 nombres premiers entre 0 et 100. Trouvez-les.

> [!propriete] Propriété
> Un nombre entier supérieur ou égal à 2 se décompose en produit de facteurs premiers. Cette décomposition est unique, à l'ordre des facteurs près.

> [!exemple] Exemple
> Décomposition de 1014 :
> $$1014 = 2 \times 507 = 2 \times 3 \times 169 = 2 \times 3 \times 13^2$$

> [!exercice] Exercice 6
> Décomposer en produit de facteurs premiers les nombres suivants :
> 1. 24
> 2. 45
> 3. 72
> 4. 98
> 5. 1044
> 6. 2565
> 7. 158

> [!definition] Définition — Fractions irréductibles
> Une fraction est dite irréductible lorsque le numérateur et le dénominateur n'ont pas de diviseur commun autre que 1.

> [!exemple] Exemple
> $$\frac{1014}{84} = \frac{2 \times 3 \times 13^2}{2^2 \times 3 \times 7} = \frac{13^2}{2 \times 7} = \frac{169}{14}$$

> [!exercice] Exercice 7
> Rendre irréductibles les fractions suivantes en utilisant la décomposition en facteurs premiers :
> 1. $\dfrac{24}{36}$
> 2. $\dfrac{45}{75}$
> 3. $\dfrac{72}{108}$
> 4. $\dfrac{98}{140}$

## Plus Grand Commun Diviseur (PGCD)

> [!definition] Définition — PGCD
> Le Plus Grand Commun Diviseur (PGCD) de deux nombres entiers non nuls $a$ et $b$ est le plus grand nombre entier qui divise à la fois $a$ et $b$.
> On note : PGCD($a$,$b$).

> [!propriete] Propriété
> - Si PGCD($a$,$b$) = 1, on dit que $a$ et $b$ sont premiers entre eux.
> - PGCD($a$,$b$) = PGCD($b$,$a$) (le PGCD est commutatif).
> - PGCD($a$,1) = 1 pour tout entier $a$.

### Méthode 1 : Par la liste des diviseurs

> [!methode] Méthode
> Pour calculer le PGCD de deux nombres :
> 1. Lister tous les diviseurs du premier nombre.
> 2. Lister tous les diviseurs du second nombre.
> 3. Identifier les diviseurs communs.
> 4. Le PGCD est le plus grand des diviseurs communs.

> [!exemple] Exemple
> Calculer PGCD(18, 24) :
> - Diviseurs de 18 : 1, 2, 3, 6, 9, 18
> - Diviseurs de 24 : 1, 2, 3, 4, 6, 8, 12, 24
> - Diviseurs communs : 1, 2, 3, 6
> - PGCD(18, 24) = 6

> [!exercice] Exercice 8
> Calculer les PGCD suivants en listant les diviseurs :
> 1. PGCD(12, 18)
> 2. PGCD(20, 30)
> 3. PGCD(15, 25)

### Méthode 2 : Par décomposition en facteurs premiers

> [!methode] Méthode
> Pour calculer le PGCD par décomposition :
> 1. Décomposer chaque nombre en produit de facteurs premiers.
> 2. Le PGCD est le produit des facteurs premiers communs, chacun affecté du plus petit exposant.

> [!exemple] Exemple
> Calculer PGCD(72, 48) :
> - $72 = 2^3 \times 3^2$
> - $48 = 2^4 \times 3$
> - Facteurs premiers communs : $2$ et $3$
> - PGCD(72, 48) = $2^3 \times 3^1 = 8 \times 3 = 24$

> [!exercice] Exercice 9
> Calculer les PGCD suivants en utilisant la décomposition en facteurs premiers :
> 1. PGCD(60, 84)
> 2. PGCD(90, 126)
> 3. PGCD(144, 96)

## Exercices — Type brevet

> [!exercice] Exercice 10
> Pierre a gagné 84 sucettes et 147 bonbons à un jeu. Étant très généreux, et ayant surtout très peur du dentiste, il décide de les partager avec des amis. Pour ne pas faire de jaloux, chacun doit avoir le même nombre de sucettes et le même nombre de bonbons.
> 1. Combien de personnes au maximum pourront bénéficier de ces friandises (Pierre étant inclus dans ces personnes) ? Expliquer votre raisonnement.
> 2. Combien de sucettes et de bonbons aura alors chaque personne ?

> [!exercice] Exercice 11
> 1. Trouver le PGCD de 6 209 et 4 435 en détaillant la méthode.
> 2. En utilisant le résultat de la question précédente, expliquer pourquoi la fraction $\dfrac{4435}{6209}$ n'est pas irréductible.
> 3. Donner la fraction irréductible égale à $\dfrac{4435}{6209}$.

> [!exercice] Exercice 12
> 1. Calculer le PGCD des nombres 135 et 210.
> 2. Dans une salle de bains, on veut recouvrir le mur situé au-dessus de la baignoire avec un nombre entier de carreaux de faïence de forme carrée dont le côté est un nombre entier de centimètres le plus grand possible.
>     1. Déterminer la longueur, en cm, du côté d'un carreau, sachant que le mur mesure 210 cm de hauteur et 135 cm de largeur.
>     2. Combien faudra-t-il alors de carreaux ?

> [!exercice] Exercice 13
> Pour le 1er Mai, Julie dispose de 182 brins de muguet et 78 roses. Elle veut faire le plus grand nombre de bouquets identiques en utilisant toutes ses fleurs. Combien de bouquets identiques pourra-t-elle faire ? Quelle sera la composition de chaque bouquet ?

> [!exercice] Exercice 14
> 1. Quels sont les nombres inférieurs à 10 qui possèdent exactement trois diviseurs ? Il n'est pas nécessaire de justifier.
> 2. « Je suis un nombre à trois chiffres dont la somme des chiffres vaut 13 et je possède exactement trois diviseurs. Qui suis-je ? »

> [!exercice] Exercice 15
> Déterminer le nombre entier $N$ satisfaisant simultanément aux trois conditions ci-dessous :
> - $N$ est divisible par 6
> - $N$ n'est pas divisible par 8
> - $N$ a exactement 15 diviseurs
