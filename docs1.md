# Documentation (docs)

Brève documentation destinée à rassembler les informations nécessaires pour comprendre, consulter et maintenir la documentation du projet.

## Aperçu
Ce dossier contient uniquement la documentation utilisateur et développeur : guides, références et notes techniques.

## Organisation des fichiers
- README.md — ce fichier d'introduction.
- /guides — guides d'utilisation et tutoriels.
- /reference — références API, commandes et schémas.
- /notes — décisions d'architecture et journal des modifications.
- /assets — images et ressources utilisées par la doc.

Exemple de structure :
```
docs/
├─ README.md
├─ guides/
├─ reference/
├─ notes/
└─ assets/
```

## Lire la documentation
1. Ouvrir README.md pour l'index.
2. Consulter les guides pour les scénarios pas à pas.
3. Référer à reference/ pour les détails techniques et les exemples.
4. Vérifier notes/ pour le contexte des décisions.

## Contribuer
- Respecter les conventions de rédaction (langue, style, ton).
- Ajouter une entrée dans notes/ pour toute modification importante.
- Proposer une PR décrivant l'objectif et les fichiers modifiés.
- Relire et valider les images dans assets/ pour lisibilité et taille.

## Conventions recommandées
- Langue principale : français.
- Formatage : Markdown standard.
- Titres : niveau cohérent (H1 unique par document).
- Exemples de code : blocs de code avec langage précisé.

## Versioning des docs
- Mettre à jour le changelog dans notes/ à chaque modification.
- Tagging des versions aligné sur les releases du projet si nécessaire.

## Support
Pour questions ou clarifications, ouvrir une issue en décrivant la section concernée et l'objectif attendu.
