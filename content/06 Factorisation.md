---
chapitre: 6
tags:
  - maths/troisieme
---

# Factorisation

## Méthodes de factorisation

En général, il existe deux moyens pour factoriser une expression :
- repérer un facteur commun
- utiliser les identités remarquables

Il est généralement simple de repérer un facteur commun. C'est pourquoi je recommande de regarder systématiquement si cette méthode vous semble applicable avant d'essayer la deuxième.

### Méthode du facteur commun

> [!methode] Méthode — Du facteur commun
> Lorsqu'une expression contient dans chaque terme de la somme un facteur commun, on peut alors factoriser en utilisant la propriété :
> $$a \times b + a \times c = a \times (b+c)$$

Quelques exemples valent mieux qu'un long discours...

> [!exemple] Exemple
> $$
> \begin{align*}
> A(x) &=15x-12\\
> A(x) &=\colorbox{fond3}{3} \times 5x- \colorbox{fond3}{3}\times 4  \hspace{5mm} \textit{$\rightsquigarrow$ Le nombre 3 est le facteur commun.}\\
> A(x) &=\colorbox{fond3}{3}(5x-4)
> \end{align*}
> $$
>
> $$
> \begin{align*}
> B(x)&=5x-5\\
> B(x)&=\colorbox{fond3}{5}\times x-\colorbox{fond3}{5}\times1 \hspace{5mm} \textit{$\rightsquigarrow$ Le nombre 5 est le facteur commun : ne pas oublier le "$\times 1$" !}\\
> B(x)&=\colorbox{fond3}{5}(x-1)
> \end{align*}
> $$
>
> $$
> \begin{align*}
> C(x)&=6x^2+10x\\
> C(x)&=\colorbox{fond3}{$2x$} \times 3x+ \colorbox{fond3}{$2x$} \times 5 \hspace{5mm} \textit{$\rightsquigarrow$ $2x$ est ici le facteur commun.}\\
> C(x)&=\colorbox{fond3}{$2x$}(3x+5)
> \end{align*}
> $$
>
> $$
> \begin{align*}
> D(x)&=(3x+2)(4x-1)+(3x+2)(-6x+8)\\
> D(x)&=\colorbox{fond3}{$(3x+2)$} \times (4x-1)+\colorbox{fond3}{$(3x+2)$} \times (-6x+8) \hspace{3mm} \textit{$\rightsquigarrow$ c'est ici $(3x+2)$.}\\
> D(x)&=\colorbox{fond3}{$(3x+2)$} \left[ (4x-1)+(-6x+8) \right]\\
> D(x)&=\colorbox{fond3}{$(3x+2)$} \left[ 4x-1-6x+8 \right]\\
> D(x)&=\colorbox{fond3}{$(3x+2)$}(-2x+7)
> \end{align*}
> $$
>
> $$
> \begin{align*}
> E(x)&=(3x-4)^2-(2x-5)(3x-4)\\
> E(x)&=\colorbox{fond3}{$(3x-4)$} \times (3x-4)+(2x-5) \times \colorbox{fond3}{$(3x-4)$} \hspace{5mm}  \textit{$\rightsquigarrow$ $(3x-4)$ est le facteur commun.}\\
> E(x)&=\colorbox{fond3}{$(3x-4)$} \left[ (3x-4)\colorbox{fond5}{-}(2x-5) \right] \hspace{5mm} \textit{$\rightsquigarrow$ Attention aux changements de signes.}\\
> E(x)&=\colorbox{fond3}{$(3x-4)$} \left[ 3x-4\colorbox{fond5}{-}2x\colorbox{fond5}{+}5 \right]\\
> E(x)&=\colorbox{fond3}{$(3x-4)$}(x+1)
> \end{align*}
> $$
>
> $$
> \begin{align*}
> F(x)&=(2x-3)^2-(2x-3)\\
> F(x)&=\colorbox{fond3}{$(2x-3)$}(2x-3)-\colorbox{fond3}{$(2x-3)$}\times1 \hspace{5mm} \textit{$\rightsquigarrow$ Mettre en évidence le "$\times 1$".}\\
> F(x)&=\colorbox{fond3}{$(2x-3)$}\left[(2x-3)-1\right]\\
> F(x)&=\colorbox{fond3}{$(2x-3)$}(2x-4)
> \end{align*}
> $$

> [!exercice] Exercice 1
> Factoriser les expressions suivantes en mettant en évidence le facteur commun numérique ou monôme :
> 1. $21x+14$
> 2. $9x-9$
> 3. $8x^2+12x$
> 4. $10x^2-6x$
> 5. $6x-4$
> 6. $x^2-x$

> [!exercice] Exercice 2
> Factoriser les expressions suivantes :
> 1. $(3x+7)(2x-4)+(3x+7)(4x+2)$
> 2. $(2x-5)^2-(2x-5)(6x-1)$
> 3. $6x(x-2)-(x-2)(x-3)$
> 4. $(3x-1)(2x+9)-(3x-1)(4x-1)$
> 5. $(3x-7)(3x+7)-(3x-7)(2x+11)$
> 6. $(x-2)^2-(x-2)(3x+4)$

### Méthode des identités remarquables

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

> [!exercice] Exercice 3
> Factoriser les expressions suivantes :
> 1. $A(x)=9x^2+42x+49$
> 2. $B(x)=25x^2-60x+36$
> 3. $C(x)=9x^2-64$

> [!exercice] Exercice 4
> Factoriser les expressions suivantes à l'aide d'une identité remarquable :
> 1. $x^2+14x+49$
> 2. $x^2+20x+100$
> 3. $x^2-18x+81$
> 4. $x^2-10x+25$
> 5. $x^2-16$
> 6. $4x^2-25$

## Exercices

> [!exercice] Exercice 5
> Factoriser les expressions suivantes (en utilisant la méthode appropriée) :
> 1. $(3x-5)(4x+5)-(4x+5)(2x+7)$
> 2. $(6x-11)^2+(6x-11)(2x-5)$
> 3. $25x^2-144$
> 4. $49x^2+70x+25$
> 5. $(4x+3)(2x-7)-(2x-7)(3x+2)$
> 6. $9x^2-6x+1$
> 7. $(4x-20)(x+2)-(x-5)(12x-6)$
> 8. $64x^2-32xy+4y^2$
> 9. $\dfrac{x^2}{4}-5x+25$
> 10. $15x^2-30x+15$

> [!exercice] Exercice 6
> Factoriser les expressions suivantes :
> 1. $A(x)=(2x-5)(7+3x)-(4x^2-20x+25)$
> 2. $B(x)=(x-3)(3x+5)+(9x^2+30x+25)$
> 3. $C(x)=3(x+3)(2x+3)-(4x^2-9)$
> 4. $D(x)=(2x-1)^2-(3-5x)^2$

