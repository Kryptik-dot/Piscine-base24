# Piscine-base24
Devoir de groupe 
# Rapport de tests – Module Base 24

## 1. Objectif
L’objectif de ce module est de gérer les conversions entre la base 24 et la base 10
afin de permettre les calculs dans une future calculatrice.

## 2. Fonctions testées
-
* char_to_value
* value_to_char
* base24_to_base10
* base10_to_base24

## 3. Jeux de tests

### 3.1 Conversion base24 → base10
| Entrée (base24) | Résultat attendu | Résultat obtenu |
|-----------------|------------------|-----------------|
| A               | 10               | 10              |
| N               | 23               | 23              |
| 1A              | 34               | 34              |

### 3.2 Conversion base10 → base24
| Entrée (base10) | Résultat attendu | Résultat obtenu |
|-----------------|------------------|-----------------|
| 34              | 1A               | 1A              |
| 0               | 0                | 0               |

## 4. Résultats
Tous les tests effectués donnent les résultats attendus.
Le module base24 fonctionne correctement pour les cas testés.

## 5. Conclusion
Le module base24 est fonctionnel et peut être utilisé pour la suite du projet,
notamment pour l’analyse et l’évaluation d’expressions arithmétiques.
