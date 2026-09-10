# Récursion et compression

Une preuve d'exécution peut être fragmentée en plusieurs shards afin de maîtriser la taille des traces.
La machine de récursion vérifie ces preuves intermédiaires dans un autre programme de preuve.
Elle agrège les engagements, les valeurs publiques et la complétude des shards dans un résultat unique.
La compression réduit ainsi le coût de transport et prépare une preuve adaptée à la vérification externe.
La chaîne n'est sûre que si chaque niveau engage la bonne clé de vérification et les mêmes valeurs publiques.
Les structures de preuve compressée rendent cette frontière explicite dans le SDK et le vérificateur.

Suite : [05 — Enveloppes SNARK](05-enveloppes-snark.md).
