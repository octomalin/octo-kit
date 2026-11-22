# [Nom de l'app]

[Une phrase : ce que fait l'app et pour qui.]

## Commandes

- Lancer en local : `[npm run dev]`
- Construire : `[npm run build]`
- Tester : `[npm test]`

## Stack

- [Vanilla JS / React / Vue], [Vite]
- Stockage : [aucun / localStorage / API]
- [Bibliothèques clés]

## Arborescence

```
[index.html]
[src/main.js     point d'entrée]
[src/components/ composants]
[src/lib/        fonctions utilitaires, sans DOM]
```

## Règles

- JavaScript moderne (modules ES, `const`/`let`, pas de `var`).
- La logique métier reste dans `src/lib/`, testable sans navigateur.
- Interface en français, accessible au clavier, lisible sur mobile d'abord.
- Si l'app appelle une API d'IA : la clé est fournie par l'utilisateur et n'est jamais commitée.
- [Règle propre au projet]

## À ne pas faire

- [Ex. : ne pas ajouter de framework pour une app d'un seul écran]
