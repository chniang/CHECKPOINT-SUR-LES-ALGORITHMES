# 🧠 Algorithmes Classiques en Python

Ce dépôt contient plusieurs **algorithmes fondamentaux** en Python, utilisés pour :
- La recherche dans une liste
- Le calcul de puissances
- Le tri d’éléments à l’aide de différentes méthodes

---

## 📌 1. Recherche binaire

```python
def recherche_binaire(liste, element):
    ...
```

🔍 Permet de rechercher efficacement un élément dans une liste **triée**.  
✅ Complexité : **O(log n)**  
🔸 Exemple :
```python
recherche_binaire([1, 2, 3, 5, 8], 6)  # False
recherche_binaire([1, 2, 3, 5, 8], 5)  # True
```

---

## ⚡ 2. Calcul de puissance

```python
def puissance(a, b):
    return a ** b
```

💡 Calcule `a` à la puissance `b`.  
Exemple : `puissance(3, 4)` → `81`

---

## 🔁 3. Tri à bulles (Bubble Sort)

```python
def tri_a_bulles(liste):
    ...
```

🔄 Méthode de tri simple mais peu efficace sur de grandes listes.  
✅ Complexité : **O(n²)**  
🔸 Exemple :
```python
tri_a_bulles([29, 13, 22, 37, 52]) → [13, 22, 29, 37, 52]
```

---

## 🔀 4. Tri par fusion (Merge Sort)

```python
def tri_par_fusion(liste):
    ...
```

⚙️ Algorithme efficace basé sur le principe du **"diviser pour régner"**.  
✅ Complexité : **O(n log n)**  
🔸 Exemple :
```python
tri_par_fusion([29, 13, 22, 37, 52]) → [13, 22, 29, 37, 52]
```

---

## 🚀 5. Tri rapide (Quick Sort)

```python
def tri_rapide(liste):
    ...
```

💨 Algorithme de tri très rapide dans la majorité des cas.  
✅ Complexité moyenne : **O(n log n)**  
🔸 Exemple :
```python
tri_rapide([29, 13, 22, 37, 52]) → [13, 22, 29, 37, 52]
```

---

## 👨‍💻 Auteur

**Cheikh Niang**  
📧 cheikhniang159@gmail.com  
📆 Avril 2025

---

