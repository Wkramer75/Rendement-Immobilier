# Rendement Immobilier

Simulateur d'investissement immobilier — une application web statique (HTML/CSS/JS, sans dépendance ni backend) pour évaluer la rentabilité d'un projet locatif.

## Fonctionnalités

- **Acquisition** : prix d'achat, frais de notaire, travaux, etc.
- **Financement** : apport, emprunt, taux, durée.
- **Revenus locatifs** : loyers, vacance locative.
- **Charges d'exploitation** : charges courantes, taxe foncière, gestion, assurances...
- **Régime & fiscalité** : comparaison de plusieurs régimes fiscaux (LMNP, SCI à l'IS, etc.) avec calcul d'imposition, amortissements, bilan comptable simplifié.
- **Projection & revente** : simulation pluriannuelle et calcul de plus-value à la revente.
- **Multi-projets** : sauvegarde automatique dans le navigateur (`localStorage`), export/import de projets au format JSON.
- **Impression / PDF** : génération d'un compte de résultat et d'un bilan imprimables.
- **Mise à jour à distance** : le fichier `source-mise-a-jour.txt` permet de pointer l'application vers une URL brute (raw) hébergeant une version plus récente de `rendement-immobilier.html`.

## Utilisation

Ouvrir `rendement-immobilier.html` directement dans un navigateur. Aucune installation ni serveur requis.

Un script `Creer le raccourci sur le Bureau (2).bat` est fourni pour créer un raccourci Windows vers l'application sur le Bureau.

## Confidentialité des données

Les données saisies (projets, hypothèses financières) restent locales au navigateur (`localStorage`) et peuvent être exportées manuellement en JSON. Les fichiers de sauvegarde (`_sauvegardes/`, `mes-projets-immobilier-*.json`, `projet-*.json`) sont exclus du dépôt via `.gitignore` car ils contiennent des données personnelles.
