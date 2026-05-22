# 📒 Carnet de contacts — Mini-projet Python

> Mini-projet d'apprentissage construit dans le cadre de ma reconversion vers **Data Analyst**, jour 20 à 22.

## 🎯 Objectif du projet

Construire un gestionnaire de carnet de contacts en Python, qui consolide les notions essentielles avant d'aborder Pandas.

Le projet permet de :
- ✅ Stocker plusieurs contacts dans une structure de données
- ✅ Afficher l'ensemble du carnet de façon lisible
- ✅ Ajouter un nouveau contact
- ✅ Rechercher un contact par son nom

## 🧱 Structure des données

Le carnet est une **liste de dictionnaires** — une structure courante en data analysis :

```python
carnet = [
    {"nom": "Cartman", "prenom": "Eric", "telephone": "0456-96-17-45", "ville": "South Park - Colorado"},
    {"nom": "McCormick", "prenom": "Kenny", "telephone": "0491-22-86-07", "ville": "South Park - Colorado"},
]

## 🛠️ Concepts Python utilisés

| Concept | Où il est utilisé |
|---|---|
| Listes de dictionnaires | Structure principale du carnet |
| Fonctions avec paramètres | `afficher_carnet`, `ajouter_contact`, `rechercher_contact` |
| Boucle `for` | Parcours du carnet |
| Condition `if` | Filtre dans la recherche |
| Variable booléenne | Drapeau `trouve` dans la fonction de recherche |
| Méthode `.append()` | Ajout d'un contact |
| `len()` | Comptage des contacts |

## 🧠 Ce que j'ai appris

- L'importance de **bien définir où chercher quoi** dans des structures imbriquées (un bug sur `contact["nom"]` vs `contact["prenom"]` m'a appris cette leçon)
- Comment **structurer un projet en fonctions réutilisables** (principe DRY)
- La gestion des erreurs Python : `IndentationError`, `NameError`, `TypeError`
- La logique d'un **runtime Colab** (les variables disparaissent après redémarrage)

## 🚀 Pour aller plus loin

- Ajouter une fonction `supprimer_contact()`
- Permettre la recherche dans le nom **ET** le prénom (avec `or`)
- Persister le carnet dans un fichier CSV (préparation à Pandas)

## 👤 Auteur

**Benjamin Gravé** — En reconversion vers Data Analyst, basé à Bouillon (Belgique).
