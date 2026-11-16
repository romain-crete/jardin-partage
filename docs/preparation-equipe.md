# Préparation de l'équipe · Le Jardin partagé des Tilleuls

## Équipe

| Membre        | Compte GitHub                   | Responsabilités                                          |
| ------------- | ------------------------------- | -------------------------------------------------------- |
| CRETE Romain… | https://github.com/romain-crete | Developer, Scrum Master Developer, propriétaire du dépôt |

| … | — | Product Owner |

## Vision du produit

Objectif de produit : site vitrine jardin des tilleuls

## Horaires du sprint

- Sprint Planning : lundi 16/11 9h
- Daily écrit : mardi 17/11 9h
- Revue et rétrospective : mardi 17h

## Accords de travail

- Execution d'une routine qualitée avant PR : npm run format npm run lint npm run build
- Vérification visuelle du rendu avec npm run preview (responsive, cmde au clavier)
- Validation obligatoire de la pull request et de ses points de contrôle avant fusion de branche sur la main

## Outils collaboratifs

| Outil | Besoin de la démarche |

| github | mise en ligne |
| vscode |codage |
| Node.js |automatisation du formatage et des ctrl|

## Questions pour le Product Owner

- Y a-t-il un moyen graphique sur le site pour un habitant de repérer sa parcelle dans le jardin ?

# Critères d'acceptation de US-10 « Le compost »

Critère 1 (Fonctionnement illustré) :
La page « Le compost » explique le fonctionnement en trois étapes, et chaque image d'illustration dispose d'un texte alternatif descriptif (alt).

Critère 2 (Liste des déchets) :

Une liste claire affiche les déchets classiques acceptés et refusés, chaque élément portant explicitement le mot « oui » ou « non » pour ne pas reposer uniquement sur la couleur.

Critère 3 (L'input de recherche interactive) :

Étant donné que je saisis « plastique » dans le champ de recherche de la page compost, quand je valide, l'interface m'indique immédiatement un refus, contrairement à la saisie de « trognon de pomme » qui indique un accord.

## Product Backlog estimé

| Ordre | User story                             | MoSCoW | Points |
| ----- | -------------------------------------- | ------ | ------ |
| 1     | US-01 En-tête et navigation communs    | Must   | 3      |
| 2     | US-09 Publication sur GitHub Pages     | Must   | 3      |
| 3     | US-08 Charte graphique (thème @theme)  | Must   | 3      |
| 4     | US-02 Page d'accueil                   | Must   | 3      |
| 5     | US-07 Pied de page et mentions légales | Must   | 3      |
| 6     | US-03 Page « Les parcelles »           | Must   | 5      |
| 7     | US-05 Formulaire d'adhésion            | Should | 8      |
| 8     | US-04 Page « Agenda des ateliers »     | Should | 5      |
| 9     | US-06 Page « Contact »                 | Could  | 3      |
| 10    | US-10 Page « Le compost »              | Could  | 5      |

Référence : US-02 = 3 points · Total : 41 points · Must : 20 points, soit 49 % de l'effort
US-05 (8 points) : découpage proposé en US-05a et US-05b

## Définition de « terminé »

[ ] Les critères d'acceptation de la story sont entièrement remplis.

[ ] npm run build, npm run lint et npm run format:check passent sans aucune erreur.

[ ] La page est parfaitement lisible et responsive sur mobile (375 px) comme sur ordinateur.

[ ] La page s'utilise entièrement au clavier, avec un indicateur de focus visible sur les éléments interactifs.

[ ] Les contrastes de couleurs respectent les normes d'accessibilité et aucune information ne passe par la seule couleur.

[ ] Le code HTML est valide et s'accompagne d'attributs alt pertinents sur les images.

[ ] Règle de l'équipe : Les styles CSS respectent la charte graphique et n'utilisent pas de valeurs arbitraires hors variables.

[ ] La pull request a été relue, validée et fusionnée dans la branche main.

[ ] Le site déployé est à jour.

## Sprint 1

- Capacité : 7h
- Objectif de sprint : «Page de site déjà utile et fonctionnelle »
- User stories (… points) : US-2 (3),US-1 (3),US-7 (3)
- Plan : Romain commence par US-1, puis US-7, puis US-2
- Tâches de US :US-01 En-tête et navigation communs (120 min), US-07 Pied de page et mentions légales (120 min),US-02 Page d'accueil (180 min)
- Événements : Sprint Planning mardi 9h ; daily écrit mercredi avant 11h ; dernière fusion 15h ; revue et rétrospective mercredi 16h30 .
