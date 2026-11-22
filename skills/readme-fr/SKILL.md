---
name: readme-fr
description: Créer ou mettre à jour le README d'un projet en français à partir du code réel. À utiliser quand on demande d'écrire, refaire, compléter ou mettre à jour le README ou la documentation d'accueil d'un dépôt.
---

# README en français

1. Lis le code avant d'écrire : fichiers de dépendances (`package.json`, `requirements.txt`…), point d'entrée, scripts, `CLAUDE.md` s'il existe.
2. Structure du README, dans cet ordre (supprime une section si elle est vide) :
   - **Titre + une phrase** qui dit ce que fait le projet et pour qui.
   - **Démo** : emplacement pour un GIF ou une capture (`![Démo](docs/demo.gif)`).
   - **Installation** : commandes exactes, copiables.
   - **Utilisation** : 1 à 3 exemples concrets.
   - **Configuration** : variables d'environnement dans un tableau (nom, rôle, exemple) ; jamais de vraie clé.
   - **Licence**.
3. Style : français clair, phrases courtes, tutoiement, pas de superlatifs (« révolutionnaire », « ultime »).
4. N'invente rien : une commande ou une option qui n'existe pas dans le code n'apparaît pas. Si une info manque, laisse `[à compléter]` et signale-le.
5. Pour une mise à jour, conserve ce que l'auteur a écrit et ne modifie que ce qui est devenu faux ou manquant.
