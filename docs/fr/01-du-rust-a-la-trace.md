# Du programme Rust à la trace RISC-V

SP1 prouve l'exécution d'un programme compilé pour RISC-V plutôt qu'un circuit écrit à la main.
Le runtime et l'exécuteur produisent une trace structurée des instructions, de la mémoire et des appels système.
Les AIR du cœur imposent ensuite les transitions valides entre lignes de cette trace.
Cette séparation permet de garder un programme invité ordinaire tout en isolant la logique de preuve.
Les précompiles déplacent les opérations coûteuses vers des tables spécialisées sans changer le résultat attendu.
La propriété prouvée reste limitée au binaire invité et aux entrées publiques effectivement engagées.

Suite : [02 — AIR et interactions](02-air-et-interactions.md).
