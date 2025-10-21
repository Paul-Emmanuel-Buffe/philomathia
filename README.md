# 📘 Philomathia — Veille Mathématique

> “La déraisonnable efficacité des mathématiques dans les sciences de la nature est une chose presque mystérieuse.”  
> — *Eugene Wigner*

---

## 🧠 Introduction

Ce document présente les notions mathématiques fondamentales nécessaires à la compréhension et à la pratique de la **Data Science** et de **l’Intelligence Artificielle**.  
Chaque notion est expliquée de façon **rigoureuse** puis **vulgarisée**, afin de relier les concepts abstraits à des images concrètes du monde réel.

---

## 1️⃣ Vecteur

### 🧩 Définition rigoureuse
Un **vecteur** est un objet mathématique défini par une **direction**, un **sens** et une **longueur (norme)**.  
En algèbre linéaire, c’est une **liste ordonnée de nombres** représentant une position ou une grandeur dans un espace donné.

### 💬 Vulgarisation / Image simple
Un vecteur, c’est comme une **flèche** qui indique une direction et une distance : “aller 3 mètres vers le nord”.  
Dans un espace 2D, il peut être noté `(x, y)`.

### 🧮 Exemple concret
Le vecteur **v = (3, 4)** représente un déplacement de 3 unités à droite et 4 vers le haut.  
Sa longueur est `√(3² + 4²) = 5`.

---

## 2️⃣ Matrice

### 🧩 Définition rigoureuse
Une **matrice** est un tableau rectangulaire de nombres, organisé en **lignes** et **colonnes**.  
Elle sert à représenter des systèmes linéaires, des transformations géométriques ou des ensembles de données.

### 💬 Vulgarisation / Image simple
Une matrice, c’est comme une **grille de données**, un peu comme un tableau Excel : chaque case contient une valeur.  
En Data Science, chaque ligne peut représenter un individu, chaque colonne une variable.

### 🧮 Exemple concret
\[
A =
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
\]
est une matrice 2×2.

---

## 3️⃣ Probabilité & loi de probabilité

### 🧩 Définition rigoureuse
La **probabilité** mesure la chance qu’un événement se produise, entre 0 (impossible) et 1 (certain).  
Une **loi de probabilité** décrit la répartition des probabilités sur un ensemble d’événements possibles.

### 💬 Vulgarisation / Image simple
La probabilité, c’est la **mesure du hasard**.  
Si tu jettes une pièce, il y a une chance sur deux d’obtenir “pile”.

### 🧮 Exemple concret
La probabilité d’obtenir un “6” en lançant un dé à 6 faces est de `1/6`.  
La **loi uniforme** associe à chaque face la même probabilité.

---

## 4️⃣ Variables indépendantes

### 🧩 Définition rigoureuse
Deux variables sont **indépendantes** si la connaissance de la valeur de l’une **n’affecte pas** la probabilité de l’autre.

### 💬 Vulgarisation / Image simple
Si la **météo** n’influence pas ton **résultat d’examen**, alors ces deux événements sont indépendants.

### 🧮 Exemple concret
Lancer un dé et tirer une carte d’un jeu de 52 cartes : les résultats n’ont aucun lien → indépendants.

---

## 5️⃣ Espérance, variance et écart type

### 🧩 Définition rigoureuse
- **Espérance** : moyenne théorique d’une variable aléatoire.  
- **Variance** : mesure de la dispersion des valeurs autour de la moyenne.  
- **Écart-type** : racine carrée de la variance.

### 💬 Vulgarisation / Image simple
L’espérance, c’est le **centre** d’une distribution.  
La variance et l’écart-type montrent **à quel point les valeurs s’éloignent** de cette moyenne.

### 🧮 Exemple concret
Pour les notes [10, 12, 14] :
- moyenne = 12  
- variance = 2,67  
- écart-type ≈ 1,63

---

## 6️⃣ Corrélation linéaire

### 🧩 Définition rigoureuse
La **corrélation linéaire** mesure la **force et le sens** du lien entre deux variables quantitatives.  
Elle varie entre -1 et +1.

### 💬 Vulgarisation / Image simple
C’est comme voir si deux choses “bougent ensemble”.  
Exemple : plus on étudie, meilleures sont les notes → corrélation positive.

### 🧮 Exemple concret
Taille et poids sont souvent corrélés positivement (~0.8).  
Âge et vitesse de réaction peuvent être corrélés négativement (~-0.6).

---

## 7️⃣ Moyenne, médiane, maximum et minimum

### 🧩 Définition rigoureuse
- **Moyenne** : somme des valeurs divisée par leur nombre.  
- **Médiane** : valeur centrale d’une série triée.  
- **Maximum / Minimum** : valeurs extrêmes.

### 💬 Vulgarisation / Image simple
La moyenne te dit **le niveau général**, la médiane te dit **le point du milieu**, et max/min te donnent **les extrêmes**.

### 🧮 Exemple concret
Pour [2, 3, 4, 9, 10] :
- moyenne = 5.6  
- médiane = 4  
- min = 2, max = 10

---

## 8️⃣ Quartiles (statistique)

### 🧩 Définition rigoureuse
Les **quartiles** divisent un ensemble de données triées en **quatre parties égales**.  
- Q1 = 25%, Q2 = 50% (médiane), Q3 = 75%.

### 💬 Vulgarisation / Image simple
Les quartiles montrent comment les données sont réparties.  
C’est comme couper une classe en quatre groupes selon leurs notes.

### 🧮 Exemple concret
Notes triées : [2, 4, 6, 8, 10, 12, 14, 16]  
Q1 = 5, Q2 = 9, Q3 = 13

---

## 9️⃣ Boxplot (diagramme en boîte)

### 🧩 Définition rigoureuse
Un **boxplot** représente graphiquement les **quartiles**, la **médiane** et les **valeurs extrêmes** d’un jeu de données.

### 💬 Vulgarisation / Image simple
C’est une **boîte** qui résume la répartition d’un ensemble de valeurs et permet de **repérer les anomalies (outliers)**.

### 🧮 Exemple concret
Un boxplot de salaires montre où se situe la majorité des employés et ceux qui gagnent beaucoup plus ou beaucoup moins.

---

## 🔟 Histogramme (statistique)

### 🧩 Définition rigoureuse
Un **histogramme** est un graphique qui montre la **distribution de fréquences** d’un ensemble de valeurs continues.

### 💬 Vulgarisation / Image simple
C’est comme un **baromètre** des données : il montre **combien de fois** une valeur ou une plage de valeurs apparaît.

### 🧮 Exemple concret
Un histogramme d’âges montre combien de personnes ont entre 20–30 ans, 30–40 ans, etc.

---

## 1️⃣1️⃣ Théorème Central Limite

### 🧩 Définition rigoureuse
Le **théorème central limite** affirme que la moyenne d’un grand nombre de variables aléatoires indépendantes suit **approximativement une loi normale**, quelle que soit leur distribution initiale.

### 💬 Vulgarisation / Image simple
C’est la **raison pour laquelle les cloches de Gauss apparaissent partout**.  
Même si les phénomènes individuels sont chaotiques, leurs moyennes se comportent comme une courbe en cloche.

### 🧮 Exemple concret
Si tu fais la moyenne de milliers de tirages de dés, la distribution de ces moyennes sera proche d’une courbe normale.

---

## 1️⃣2️⃣ Dérivée

### 🧩 Définition rigoureuse
La **dérivée** d’une fonction mesure la **variation instantanée** de cette fonction — son “taux de changement”.  
Elle correspond à la **pente de la tangente** en un point donné.

### 💬 Vulgarisation / Image simple
La dérivée, c’est la **vitesse instantanée** : à quel rythme quelque chose change à un instant précis.  
Par exemple, la dérivée de la position = vitesse.

### 🧮 Exemple concret
Si `f(x) = x²`, alors `f'(x) = 2x`.  
En `x = 3`, la pente vaut 6 → la courbe monte rapidement.

---

## 🧩 Conclusion

Les notions abordées dans cette veille constituent les **fondations mathématiques** indispensables à tout travail en **Intelligence Artificielle** et en **Analyse de données**.  
Les maîtriser, c’est non seulement comprendre les modèles, mais aussi savoir **interpréter**, **vulgariser** et **communiquer** les résultats avec rigueur et clarté.
