# CoW Protocol : ordres et settlement

Un ordre signé précise notamment l’actif vendu, l’actif acheté, les montants, la durée et les contraintes d’exécution. Le solver propose une solution qui associe plusieurs ordres et peut utiliser des sources de liquidité externes.

Le settlement exécute les interactions dans un cadre contrôlé : il calcule les montants, applique les frais et empêche qu’un ordre soit rempli au-delà de ses limites. Les surplus peuvent être redistribués selon les règles du protocole.

Les événements et les vérifications de nonce rendent le remplissage et l’annulation observables.

[Chapitre suivant : limites](04-limites.md)
