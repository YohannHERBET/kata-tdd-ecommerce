# Kata TDD (Test-Driven Development) en PHP

## Contexte
L'entreprise `Noelas` souhaite améliorer la gestion du panier utilisateur sur son site e-commerce.
Ils souhaitent également ajouter des contraintes métiers suite à des piratages récents.

En tant qu'expert, ils vous font appel pour répondre efficacement à leurs besoins.

Les règles à suivre pour améliorer le panier utilisateur sont les suivantes :

1. Le panier d'un utilisateur est unique et vide par défaut lors de la création de son compte.
2. Le panier utilisateur peut contenir plusieurs occurrences du même produit, ainsi que différents produits.
3. Il est interdit d'ajouter un produit au panier si la quantité choisie est inférieur ou égale à 0.
5. Il doit être possible de retirer un produit du panier ou de réduire la quantité d'un produit dans le panier.
6. `Exemples` :
    - Si l'utilisateur ajoute 4 fois le même produit, il doit y avoir un seul produit dans le panier avec une quantité de 4.
    - Si l'utilisateur retire 1 quantité de ce produit, il doit rester 3 quantités du produit dans le panier.
    - Si l'utilisateur ajoute encore le même produit 2 fois, il doit y avoir un seul produit dans le panier avec une quantité de 5.
    - L'utilisateur ne peut pas supprimer plus de produits qu'il n'en a dans son panier. Par exemple, s'il a 5 quantités
   d'un produit dans son panier, il ne peut pas demander la suppression de 6.
    - Il doit être possible de calculer le prix total du panier.

## Objectif
L'objectif est d'implémenter ces règles en suivant la méthodologie `TDD (Test Driven Development)` pour améliorer la
gestion du panier utilisateur sur le site e-commerce de l'entreprise `Noelas` en utilisant PHP.

---

Thank you Ulrich Geraud A. :)
