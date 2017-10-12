# Geométrie

## Objectifs

- Mise en oeuvre de la POO 
- Matérialisation des notions de classes abstraites, d'interfaces, d'héritage
- Représentation UML avec le diagramme de classes
- Matérialisation du polymorphisme

## Contexte métier

Nous allons nous intéresser à modéliser et implémenter quelques concepts géométriques avec UML et Java.

Les éléments ciblés seront : 

- les carrés, rectangles
- les cubes, pavés droits

L'un des objectifs sera de permettre, à partir des dimensions définies pour chaque élément, de déterminer leur périmètre / surface / volume.

## Déroulé

Première partie : sur papier / document texte

- Etape 1 : pour chaque élément couvert par le métier, identifier les caractéristiques nécessaires à sa construction
- Etape 2 : identifier les comportements communs à un sous-ensemble d'éléments couvert par le métier, et les associer à une ou plusieurs interfaces
- Etape 3 : identifier les abstractions pouvant être mises en place pour matérialiser des liens sémantiques entre plusieurs éléments métier et/ou mutualiser des définitions / comportements / fragments de code

Seconde partie : implémentation

- Etape 4 : implémenter la réflexion menée précédemment en Java
- Etape 5 : mettre en place des scénarios de tests unitaires permettant de valider les fonctionnalités de calcul de périmètre, surface, volume

Troisième partie : réflexion

- Etape 6 : mise en commun en groupe / réflexion
- Etape 7 : le cas échéant, améliorer / refactorer le code et s'assurer que les tests unitaires restent passant

Quatrième partie : modélisation

- Etape 8 : réaliser une représentation UML du modèle métier en utilisant un diagramme de classe
- Etape 9 : compléter la représentation UML en enrichissant le métier avec de nouvelles entités au choix, voire de nouveaux comportements

Bonus : approfondissement

- Etape 10 : modéliser la notion d'espace à 3 dimensions, de point, de segment
- Etape 11 : modéliser les comportements suivants sur un espace à 3 dimensions
  - Placer un point
  - Placer un segment
  - Placer une surface
  - Placer un volume
- Etape 12 : implémenter la modélisation menée précédemment en Java
