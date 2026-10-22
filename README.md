# NSI — La récursivité

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SamiChabbi/nsi-recursivite/main)

Notebooks Jupyter pour apprendre la récursivité, du premier exemple jusqu'aux exercices de niveau bac et à l'entrée dans « diviser pour régner ».

## Contenu

```
01_Recursivite_Cours.ipynb          cours : cas de base, trace, pile d'appels, méthode en 3 questions, listes avec un indice
02_Recursivite_Exercices.ipynb      15 exercices progressifs (⭐ à ⭐⭐⭐⭐) avec tests pour s'autocorriger
03_Recursivite_Resolutions.ipynb    résolutions : ÉNONCÉ / RÉSOLUTION / EXPLICATION PÉDAGOGIQUE
```

| Partie | Exercices | Niveau |
|:---|:---|:---|
| A — Premiers pas | factorielle, puissance, somme des chiffres, multiplication 📚 | ⭐ à ⭐⭐ |
| B — Listes et chaînes | maximum, occurrences, inverser, palindrome, binaire 📚, règles A et B 📚 | ⭐⭐ à ⭐⭐⭐ |
| C — Plusieurs appels | Fibonacci 📚, chemins dans une grille 📚, rendu de monnaie 📚, chiffres romains 📚 | ⭐⭐⭐ |
| D — Vers diviser pour régner | dichotomie 📚, trouver l'intrus 📚, tours de Hanoï, remplissage d'une zone 📚 | ⭐⭐⭐ à ⭐⭐⭐⭐ |

📚 = exercice tiré d'un sujet du bac (énoncés adaptés, sans slicing) :
- épreuve pratique 2024 (banque nationale de sujets) : sujets 9, 18, 27, 28, 30, 36 et 40 ;
- épreuve écrite 2022, Polynésie, sujet 1, exercice 1 ;
- épreuve écrite 2024, Centres étrangers 1, jour 2, exercice 1 (partie C).

## Dossier `Sujets_bac/` : exercices tombés au bac

```
Sujets_bac/01_Cours_Tableau_de_trace_et_methode.ipynb   tableau de trace (boucle, récursion), arbre des appels, réponses types
Sujets_bac/02_Exercices_bac.ipynb                        14 exercices de l'épreuve écrite (2021-2025), du plus facile au plus dur
Sujets_bac/03_Resolutions_bac.ipynb                      résolutions : ÉNONCÉ / RÉSOLUTION / EXPLICATION PÉDAGOGIQUE
```

| Niveau | Exercices (sujet d'origine) |
|:---|:---|
| 1 — Lire et comprendre | sujet 0 B 2023, Centres étrangers 2022 J2, Métropole sept. 2024 J2, Liban 2023 J1, Amérique du Nord 2022 J1 |
| 2 — Suivre et écrire | Métropole 2021 candidats libres 2 (Fisher-Yates), Polynésie 2025 J1 (baguenaudier) |
| 3 — Diviser pour régner | Métropole 2021 (tri fusion), Liban 2023 J2 (tri fusion), Amérique du Nord 2024 J2 (tri de Stooge), Asie 2024 J2 (élément majoritaire), Métropole 2021 candidats libres 1 (inversions) |
| 4 — Récursivité avec des choix | Métropole 2024 J2 (chargement optimal), sujet 0 B 2024 (pyramide, programmation dynamique) |

## Utilisation

- **En ligne :** cliquer sur le badge *Binder* ci-dessus (premier lancement : quelques minutes).
- **Sur son ordinateur :** `jupyter notebook` dans le dossier du dépôt.

Exécuter les cellules **dans l'ordre** (*Cell → Run All*). Les notebooks n'utilisent que Python standard.
