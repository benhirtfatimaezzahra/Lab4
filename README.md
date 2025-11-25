# Gestion des Notes Étudiants

Ce projet Python permet de saisir et analyser les notes d'étudiants avec validation des entrées, calcul de moyenne et détermination du statut d'admission.

Le programme illustre les concepts fondamentaux de Python : boucles, conditions, gestion des exceptions, listes et fonctions.

---

## Fonctionnalités

- Saisie interactive de notes (jusqu'à 10 par défaut)
- Option d'arrêt anticipé avec la commande `stop`
- Validation robuste des entrées utilisateur
- Gestion des erreurs (valeurs vides, non numériques)
- Seuil d'admission paramétrable (10.0 par défaut)
- Affichage détaillé par étudiant :
  - Numéro de l'étudiant
  - Note obtenue
  - Statut : **Admis** ou **Refusé**
- Synthèse globale :
  - Nombre total de notes saisies
  - Moyenne générale formatée
  - Mention : **Moyenne satisfaisante** ou **Moyenne insuffisante**

---

## Architecture
```
exo_complet.ipynb → Notebook Jupyter contenant :
- Fonction saisir_notes(seuil, max_notes)
- Boucle while avec compteur manuel
- Validation des entrées avec try/except
- Traitement et affichage des résultats
- Calcul de moyenne et détermination des mentions
```

---

##  Installation

Cloner le projet :
```bash
git clone https://github.com/benhirtfatimaezzahra/Lab4.git
```

Ouvrir le notebook avec Jupyter :
```bash
cd Lab4
jupyter notebook exo_complet.ipynb
```

Ou utilisez JupyterLab :
```bash
jupyter lab exo_complet.ipynb
```

---
## Démonstration

Une vidéo illustrant le fonctionnement du programme peut être ajoutée dans le dépôt :


https://github.com/user-attachments/assets/ada37a93-51e7-40d2-afb0-94e2d430b46d


## Auteur

**Nom :** Benhirt Fatima Ezzahra  
**Cours :** Introduction à Python  
**Date :** Novembre 2025  
**Encadré par :** Pr. Mohamed LACHGAR
