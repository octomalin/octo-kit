# 🐙 octo-kit

**Le kit de démarrage Claude Code en français.** Des modèles de `CLAUDE.md` prêts à remplir et trois skills qui font gagner du temps tous les jours.

> Ton IA oublie tout à chaque session ? Un bon `CLAUDE.md` lui donne la mémoire de ton projet.

## Ce qu'il y a dedans

| Dossier | Contenu |
| --- | --- |
| `templates/` | 3 modèles de `CLAUDE.md` : site web, script Python, app JavaScript |
| `skills/commit-fr` | Rédige des messages de commit clairs, en français, au format Conventional Commits |
| `skills/readme-fr` | Génère ou met à jour un README en français à partir du code |
| `skills/revue-fr` | Fait une revue de code bienveillante et priorisée, en français |

## Installation (2 minutes)

```bash
git clone https://github.com/octomalin/octo-kit.git
```

**Un modèle de CLAUDE.md** : copie le fichier qui correspond à ton projet à la racine du projet, renomme-le `CLAUDE.md` et remplis les `[crochets]`.

**Les skills** : copie les dossiers de `skills/` :

- dans `~/.claude/skills/` pour les avoir dans tous tes projets ;
- ou dans `.claude/skills/` à la racine d'un projet pour ce projet seulement.

Ensuite, dans Claude Code, il suffit de demander : « fais le commit », « mets à jour le README », « relis mon code ».

## Comment Octave l'a construit

Prompt de départ donné à Claude :

> Crée un kit de démarrage Claude Code en français pour des développeurs indépendants : trois modèles de CLAUDE.md (site web, script Python, app JS) avec des sections courtes à compléter, et trois skills simples (commit, README, revue de code). Tout en français, sans jargon inutile.

Puis relecture, tests sur de vrais projets et ajustements à la main. 🐙

## Contribuer

Une idée de modèle ou de skill ? Ouvre une issue ou une pull request.

---

Licence [MIT](LICENSE) · Fait par [Octomalin](https://github.com/octomalin) · Suivre Octave sur [Instagram](https://www.instagram.com/octomalin)
