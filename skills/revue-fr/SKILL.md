---
name: revue-fr
description: Faire une revue de code bienveillante, priorisée et en français sur des changements ou des fichiers. À utiliser quand on demande de « relire », « reviewer », « faire une revue » ou « donner un avis » sur du code, une branche ou une pull request.
---

# Revue de code en français

1. Délimite le périmètre : `git diff` de la branche (ou les fichiers indiqués). Lis aussi le contexte autour de chaque changement.
2. Classe chaque remarque en trois niveaux :
   - 🔴 **Bloquant** : bug, faille de sécurité, perte de données, clé ou secret exposé.
   - 🟠 **À corriger** : cas limite non géré, test manquant, code difficile à maintenir.
   - 🟢 **Suggestion** : lisibilité, nommage, petite simplification.
3. Pour chaque remarque : fichier et ligne, le problème en une phrase, un exemple concret de ce qui casse, la correction proposée (extrait de code si utile).
4. Termine par ce qui est bien fait (une ou deux phrases sincères) et un verdict : « prêt à fusionner », « prêt après corrections 🔴 » ou « à retravailler ».
5. Ne modifie pas le code toi-même pendant la revue ; propose d'appliquer les corrections ensuite.
