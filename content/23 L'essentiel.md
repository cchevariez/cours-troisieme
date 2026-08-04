---
chapitre: 23
tags:
  - maths/troisieme
---

# L'essentiel

## Calcul numérique

> [!propriete] Propriété
> Soit $a$ et $b$ deux nombres et $n$ et $p$ deux entiers, alors :
> - $a^n \times a^p = a^{n+p}$
> - $(a^n)^p = a^{n \times p}$
> - $(a \times b)^n = a^n \times b^n$
> - $\left(\dfrac{a}{b} \right)^n = \dfrac{a^n}{b^n}$
> - $\dfrac{a^n}{a^p} = a^{n-p}$

> [!methode] Méthode — Des identités remarquables
> Lorsque l'on ne repère pas un facteur commun, il peut y avoir une identité remarquable :
> $$\boxed{a^2+2ab+b^2=(a+b)^2}$$
> $$\boxed{a^2-2ab+b^2=(a-b)^2}$$
> $$\boxed{a^2-b^2=(a+b)(a-b)}$$
> Il s'agit alors de repérer quelle identité utiliser puis d'identifier $a$ et $b$ pour factoriser en utilisant les formules ci-dessus.

> [!methode] Méthode — Manipulation de pourcentage
> Règles :
> 1. **Quantité relative à un pourcentage.** Ex : sur 170 personnes, 23% ont moins de 40 ans. $$\frac{23}{100} \times 170$$ Attention : le « de » en français se traduit par $\times$.
> 2. **Calculer un pourcentage de...** $$pourcentage = \frac{partiel}{total} \times 100$$ Ex : 12 élèves sur 30 sont ... $$pourcentage = \frac{12}{30}\times 100$$
> 3. **Pourcentage d'un pourcentage.** On multiplie les deux pourcentages entre eux. Ex : 70% des Français ont un téléphone. 20% des téléphones sont des iPhones. Donc $70\% \times 20\% = 14\%$ des Français ont un iPhone.

> [!methode] Méthode — Grandeurs composées
> Grandeurs composées de plusieurs grandeurs. Formules classiques :
> $$v = \frac{d}{t}$$
> $$D = \frac{V}{t}$$
> Attention aux unités, conversions obligatoires. $1m^3= 1000L$.
>
> Ex : Calculer la vitesse en $km/h$. Distance 600 m / temps : 37 min.
> $d = 600m = 0,6km$
> $t = 37min = \frac{37}{60} = 0,62h$
> $v = \frac{0,6}{0,62} = 0,97$ km/h
>
> Ex : Un véhicule roule à 60 km/h. Quel temps met-il pour parcourir 3200 m ?
> 1. Conversion si nécessaire : $3200m = 3,2km$.
> 2. Transformer la formule :
>     $$v = \frac{d}{t}$$
>     $$v \times t = d$$
>     $$t = \frac{d}{v}$$
> 3. Tu choisis ta formule et tu remplaces.

## Géométrie

### Thalès

Si pas de parallélisme, bien penser que si deux droites sont perpendiculaires à une même troisième alors elles sont parallèles.

![[thalesconf.png]]

### Pythagore

Si pas de triangle rectangle et pas assez de longueurs, bien penser que tout triangle inscrit dans un demi-cercle est rectangle.

### Trigonométrie

> [!exemple] Exemple
> $$cos(\widehat{BAC})=\frac{AB}{AC}$$
> $$sin(\widehat{BAC})=\frac{BC}{AC}$$
> $$tan(\widehat{BAC})=\frac{BC}{AB}$$
> $$cos^2(\widehat{A}) + sin^2(\widehat{A}) = 1$$
> $$tan(\widehat{A}) = \frac{sin(\widehat{A})}{cos(\widehat{A})}$$
>
> ![[tri_1.png]]

### Statistiques

> [!definition] Définition — Médiane
> La médiane $M_e$ d'une série est telle que :
> - au moins 50% des données ont des valeurs inférieures ou égales à $M_e$
> - au moins 50% des données ont des valeurs supérieures ou égales à $M_e$
