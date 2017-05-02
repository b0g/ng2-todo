# Projet Ng2 TODO (WIC 2016/2017)
    Boris GALLET et Karine GUIDUCCI

## Prérequis

Pour ce projet nous avons utilisé le navigateur chrome sous Ubuntu (Version 58 64-bit)
    Attention : chromium browser ne fonctionne pas


## Lancement :

Pour lancer le projet en mode développement :
```
git clone https://github.com/b0g/ng2-todo.git
cd ng2-todo
npm install
npm install -g @angular/cli
ng serve
```

Ce projet utilise [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

---

## Fonctionnalitées

### Synthèse vocale

Un service de synthèse vocal à été implémenté, permettant de lire les tâches

### Reconnaissance vocale

En ce qui concerne la reconnaissance vocale, nous n'avons pas réussi à implémenter
de grammaire de phrases, nous n'avons donc pas pu tester cette fonctionnalité.

En ce qui concerne l'utilisation de l'application, nous considérons qu'une liste
de commande sera dicté précisément, et connus par l'utilisateur :

    * Ajouter une tâche
    * Modifier une tâche & Supprimer une tâche
        - Une tâche devra être sélectionnée vocalement, il se peut qu'il y ait des erreurs
        - dire "annuler" en cas de mauvais fonctionnement
    * Combien de tâches me reste-t-il à faire ?
    * Qu'est-ce qu'il me reste à faire ?
    * Valider toutes les tâches
    * Lire toutes les tâches
    * Supprimer les tâches effectuées

---

## Liens utiles :

Nous avons utilisé [SpeechRecognition MDN](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition)
