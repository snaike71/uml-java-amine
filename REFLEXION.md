# REFLEXION

## Choix d'implémentation

J'ai implémenté les classes Java selon le diagramme UML fourni :
- Classes simples (Bar, Baz, Qux) sans attributs
- Classe Grault avec relation vers Foo
- Classe Corge avec relation bidirectionnelle vers Foo
- Classe Foo avec toutes les relations (association, agrégation, composition)

## Difficultés rencontrées

- Gestion des relations bidirectionnelles pour éviter les boucles infinies
- Configuration de l'environnement Java/Maven
- Compréhension des différents types de relations UML

## Améliorations possibles

- Ajouter des validations dans les setters
- Gérer les cas d'erreur dans les relations
- Ajouter des tests supplémentaires

## Résultat

Tous les tests passent (5/5).