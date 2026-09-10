# Enveloppes SNARK pour la vérification EVM

SP1 peut envelopper une preuve récursive dans un SNARK Groth16 ou PLONK vérifiable efficacement sur l'EVM.
La preuve STARK assure l'exécution générale tandis que l'enveloppe SNARK réduit le coût de vérification sur chaîne.
Le contrat doit connaître la clé ou son empreinte attendue et reconstruire correctement les entrées publiques.
Changer de version de circuit sans synchroniser le vérificateur brise cette chaîne de confiance.
Cette composition illustre le compromis : transparence et scalabilité en amont, preuve succincte à la frontière EVM.
Le périmètre est documentaire ; aucune nouvelle installation, compilation ou exécution n'a été réalisée.
La suite de tests du dépôt reste la référence pour vérifier l'implémentation.
