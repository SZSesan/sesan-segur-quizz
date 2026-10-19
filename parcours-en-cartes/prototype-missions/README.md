# Parcours et missions CPTS · Prototype V9 enrichi

Ce prototype ajoute l’atelier territorial et la fiche de discours CPTS avant la refonte du pack global.

## Accès

Ouvrir `index.html`, puis choisir l’atelier et inscrire le groupe. L’espace animateur est dans `Animateur_CPTS.html`.

Les deux fichiers HTML autonomes fournis dans la conversation fonctionnent hors connexion. Les pages du site chargent les mêmes plateaux à partir de ressources conservées dans le sous-dossier base ; elles nécessitent une connexion pour le chargement initial.

## Contenu repris des planches

- Les trois frises patient de la V9 restent disponibles.
- La fiche « Quel discours auprès des CPTS ? » reprend les arguments, les objections et réponses, la phrase pour convaincre, les ressources et la confiance sur dix avec justification.
- L’atelier territorial reprend la recherche de médecin traitant, les soins non programmés de ville et la prévention. Chaque mission conserve les trois colonnes de la planche : solution / fonctionnalité, utilité pour la mission, questions / objections et réponses.
- Plusieurs cartes, usages précis et jokers peuvent être choisis. Les fiches et logos du kit sont conservés.
- Les notes des services portent sur la pertinence, la facilité d’usage, le gain de temps et la difficulté d’équipement. Pour cette dernière dimension, cinq signifie une difficulté élevée. Le baromètre de confiance, distinct, va de zéro à dix et reste vide tant que le groupe ne l’a pas évalué.

Les trois missions durent trente minutes chacune. La fiche de discours se renseigne pendant ces séquences. Pour les ateliers parcours, la planche de discours correspond à la séquence séparée de quarante-cinq minutes du support.

Les acteurs à embarquer, la démarche d’aller-vers et les pistes de discussion sont des compléments proposés pour l’animation. Les réponses et les notes ne sont pas préremplies.

## Enregistrement et restitution

Les saisies sont enregistrées dans le navigateur. Exporter le JSON pour conserver et transmettre le travail du groupe. Il n’y a pas de synchronisation automatique entre appareils. Le courriel préparé nécessite de joindre le fichier manuellement.

Les essais sont enregistrés dans un espace distinct de la V9 actuelle. Le prototype importe les anciennes sauvegardes V9 et conserve leurs parcours. Les nouveaux fichiers sont destinés à l’espace animateur de ce prototype, afin de préserver les rubriques CPTS.

La consolidation intègre les missions, le discours CPTS, les notes et leurs groupes d’origine. Le JSON, le CSV, les comptes rendus HTML et la génération de PowerPoint utilisent les saisies enregistrées. Le fichier de démarrage d’une table conserve les inscriptions et affectations, sans les réponses de l’atelier.

## Exemple fictif

`DEMO_Missions_CPTS.json` contient une table de démonstration avec des participants et des échanges fictifs. L’importer dans le jeu ou dans l’espace animateur. Les exemples servent à tester le fonctionnement et à discuter les usages, sans constituer un corrigé validé.

## Sources

Support fourni « Planches ateliers 1 à 4 », dix-huit diapositives : les missions sont reprises des diapositives 16 à 18, la fiche de discours des diapositives 5, 10 et 15. Les parcours, les fiches outils et les visuels proviennent du pack V9 existant. Le guide Word et le diaporama global ne sont pas refaits à ce stade.

## Vérifications

La chaîne de saisie, de sauvegarde, d’import et d’export a été vérifiée pour les missions et pour le parcours patient. Les compteurs de trente et quarante-cinq minutes, les notes manquantes et la valeur zéro du baromètre sont distingués. Le rendu dans un navigateur n’a pas fait l’objet d’un contrôle visuel automatisé dans cet environnement.
