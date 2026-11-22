---
name: commit-fr
description: Rédiger et créer un commit Git avec un message clair en français au format Conventional Commits. À utiliser quand on demande de « faire le commit », « commiter », « écrire le message de commit » ou de valider des changements.
---

# Commit en français

1. Lance `git status` et `git diff --staged`. Si rien n'est indexé, montre les fichiers modifiés et demande lesquels inclure (ne fais pas `git add -A` sans accord).
2. Identifie le type principal du changement :
   `feat` (nouvelle fonctionnalité), `fix` (correction), `docs`, `style` (mise en forme), `refactor`, `test`, `chore` (outillage, dépendances).
3. Rédige le message :
   - Première ligne : `type(portée): résumé` en français, à l'infinitif, ≤ 60 caractères, sans point final.
     Exemple : `feat(contact): ajouter la validation du formulaire`
   - Ligne vide, puis 1 à 3 puces qui expliquent **pourquoi**, pas seulement quoi.
4. Montre le message, attends un « ok », puis lance `git commit`.
5. Si les changements mélangent plusieurs sujets, propose de les séparer en plusieurs commits.
