# Instructions pour Claude Code

## Commits automatiques

Après chaque modification du code validée par l'utilisateur (ex: fonctionnalité corrigée, testée, ou explicitement approuvée), effectuer automatiquement, **sans demander confirmation** :

1. `git add` des fichiers modifiés concernés
2. `git commit` avec un message clair, concis et en français décrivant le changement
3. `git push` vers `origin main`

Cette autorisation est permanente pour ce dépôt et couvre les push vers `origin main`. Ne pas redemander confirmation à chaque fois.

## Fichiers à ne jamais commiter

Ne jamais ajouter ni commiter de fichiers `.json` de projets exportés (ex: `mes-projets-immobilier-*.json`, `projet-*.json`) ni le dossier `_sauvegardes/`, même s'ils sont présents dans le répertoire de travail. Ces fichiers contiennent des données personnelles et sont exclus via `.gitignore`. Si l'un d'eux apparaît comme non suivi (`git status`), l'ignorer et ne pas l'ajouter.
