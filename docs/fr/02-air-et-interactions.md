# AIR et interactions entre tables

Le cœur SP1 décompose l'exécution en puces : processeur, mémoire, contrôle de flux et opérations arithmétiques.
Chaque puce décrit des contraintes polynomiales locales dans une AIR.
Les interactions relient les événements dispersés entre tables, notamment lectures et écritures mémoire.
Cette modularité facilite l'ajout de précompiles mais impose de vérifier la cohérence globale des multiensembles.
Une trace bien formée ne suffit donc pas : les bus logiques doivent aussi s'équilibrer.
Le code de machine et les AIR constituent la référence pour comprendre les invariants réellement imposés.

Suite : [03 — Engagements et FRI](03-engagements-et-fri.md).
