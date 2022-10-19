# Jeu de la vie 

L'objectif de ce Kata est d'implémenter les règles du jeu de la vie

## Jeu de la vie

- Toute cellule vivante avec moins de deux cellules voisines vivantes meurt pour cause de sous population
- Toute cellule vivante avec deux ou trois cellules voisines vivantes reste en vie
- Toute cellule vivante avec plus de trois cellules voisines vivantes meurt pour cause de sur population
- Toute cellule morte avec exactement trois cellules voisines vivantes naît, c’est la reproduction

Selon l'état courant de la cellule et le nombre de ses voisins, déterminer son état final.

## Consignes ou conseils

- Commencez par développer une solution implémentant la 1ère règle, puis la 2ème, puis la 3ème... etc. Ne pas chercher à respecter toutes les règles du premier coup.
- A chaque nouvelle règle implémentée doit correspondre au moins 1 nouveau test !
- A chaque nouvelle règle implémentée, refactorez votre code en vérifiant qu'il respecte les bonnes pratiques ci-dessous.



# ANNEXES : Bonnes pratiques YAGNI, SOLID, Object Calisthenics et TDD

## YAGNI

Principe d'extreme programming qui déclare que les programmeurs ne devraient pas ajouter de fonctionnalité à un logiciel tant que celle-ci n'est pas absolument nécessaire.

https://fr.wikipedia.org/wiki/YAGNI


## SOLID

1. Single responsibility principle
2. Open/closed principle
3. Liskov substitution principle
4. Interface segregation principle
5. Dependency inversion principle

[Documentation SOLID](https://gitlab.insee.fr/craftsmanship/documentation/-/wikis/concepts/SOLID)

## 9 OC Rules

1. Only One Level Of Indentation Per Method
2. Don't Use The ELSE Keyword
3. Wrap All Primitives And Strings
4. First-Class Collections
5. One Dot Per Line
6. Don't Abbreviate
7. Keep All Entities Small
8. No Classes With More Than Two Instance Variables
9. No Getters/Setters/Properties

[Documentation OC](https://gitlab.insee.fr/craftsmanship/documentation/-/wikis/concepts/Objects-Calisthenics)

## TDD

1.  Ecrire le test
2.  Le faire compiler
3.  Regardez-le échouer
4.  Le faire réussir