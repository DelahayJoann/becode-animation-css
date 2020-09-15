# Animation CSS

## Quoi?
Réaliser des animations en utilisant les propriétés css transition et animation.

## Pourquoi?
Apprentissage lors de la formation BeCode

## Comment?
__PAS DE JAVASCRIPT__ <br>
En utilisant exclusivement la propriété transition
__Contrainte__: Ne fonctionne que sur Firefox pour les raisons ci-dessous.<br>

## Quand ressort-il?
Actuellement, seul Firefox permet d'animer le redimensionnement de la taille des rows ou columns dans un Grid.
Les autres navigateur ne feront aucune transition. Les changements seront immédiats pour le redimensionnement de Grid.
Afin de contourner ce problème qui faisait apparaitre des soucis d'animation entre celles qui fonctionnent et celle-là qui ne fonctionne pas,
j'ai du omettre l'utilisation de la propriété générique: «transition-duration» et n'utiliser que celles avec le préfixe pour assigner une durée que sur Firefox.
