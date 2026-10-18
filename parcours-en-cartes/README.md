# Parcours en cartes · V9

Atelier sur l’exercice coordonné et les usages numériques pour les équipes départementales, les CPTS, MSP et centres de santé.

## Accéder au jeu

- Accueil : https://szsesan.github.io/sesan-segur-quizz/parcours-en-cartes/
- Groupes : https://szsesan.github.io/sesan-segur-quizz/parcours-en-cartes/Jeu_groupes_V9.html
- Animateur : https://szsesan.github.io/sesan-segur-quizz/parcours-en-cartes/Animateur_consolidation_V9.html

Le dossier est autonome. L’ancien quiz à la racine du dépôt conserve ses fichiers. GitHub Pages publie la branche main à partir de la racine.

## Déroulement

Un ordinateur partagé par table ; 5 à 7 personnes conseillées, 10 maximum. Inscrire l’équipe, choisir un des trois parcours patient, puis ouvrir le plateau V9. Placer plusieurs cartes acteurs et outils aux moments clés, saisir les freins, irritants, leviers, arguments et actions, puis évaluer les services. Le compte à rebours dure 45 minutes.

Le guide Word et les supports PowerPoint sont accessibles depuis l’accueil, ainsi que les documents source et une démonstration fictive.

## Enregistrer et transmettre

La sauvegarde automatique reste dans le navigateur de chaque table. GitHub ne reçoit pas les noms ni les réponses saisis dans le jeu. Exporter un JSON pour conserver le travail, changer d’appareil ou le transmettre à l’animateur. L’envoi se fait en pièce jointe manuelle ; aucune synchronisation automatique n’est fournie.

L’animateur importe les JSON reçus, arbitre les éventuels doublons et consolide les échanges. Il peut exporter les résultats en JSON, CSV, HTML et PowerPoint éditable. Les consensus de plénière sont validés manuellement. Les notes ne constituent pas une mesure objective de performance des services.

L’espace animateur est public, sans authentification. Les données qu’il importe restent sur son appareil. Les ressources de ce dossier sont accessibles à tous les visiteurs. Conserver les vrais JSON, les exports et les listes de participants hors du dépôt public. Le .gitignore limite certains ajouts Git accidentels, mais ne protège pas les envois manuels par l’interface GitHub. Le seul JSON présent dans le dépôt contient des données de démonstration fictives.

Une ancienne partie ouverte depuis un fichier local doit être exportée en JSON, puis réimportée à l’adresse en ligne. Les données du navigateur ne migrent pas automatiquement entre les deux adresses.

## Maintenance

Les liens sont relatifs au dossier et ne nécessitent aucune compilation. Mettre à jour les fichiers de ce dossier, sans écraser l’index.html du quiz à la racine. Le fichier .nojekyll à la racine sert directement les fichiers statiques.

Les scripts du jeu et du consolidateur sont identiques au pack V9 validé ; un retour vers l’accueil a été ajouté au menu. Sources des personnages, logos et illustrations : Sources_des_visuels.txt. Licence de la bibliothèque d’export : Licence_JSZip.txt.
