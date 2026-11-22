# [Nom du script]

[Une phrase : ce que fait le script, sur quelles données.]

## Commandes

- Installer : `[python -m venv .venv && pip install -r requirements.txt]`
- Lancer : `[python main.py --help]`
- Tester : `[pytest]`

## Stack

- Python [3.12], dépendances dans `requirements.txt`
- [Bibliothèques clés : pandas, typer, httpx…]

## Arborescence

```
[main.py        point d'entrée (CLI)]
[src/           logique métier]
[tests/         tests pytest]
```

## Règles

- Fonctions courtes, typées (`def f(x: str) -> int`), docstring d'une ligne.
- Aucune donnée personnelle ni clé API dans le code : variables d'environnement (`.env`, non versionné).
- Toute nouvelle fonction a au moins un test.
- Les messages affichés à l'utilisateur sont en français.
- [Règle propre au projet]

## Données

- Entrée : [format, emplacement]
- Sortie : [format, emplacement]
- Ne jamais modifier les fichiers d'origine : écrire à côté.

## À ne pas faire

- [Ex. : ne pas ajouter de dépendance sans me demander]
