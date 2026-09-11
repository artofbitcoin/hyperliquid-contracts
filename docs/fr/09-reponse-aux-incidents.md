# 9 — Réponse aux incidents et récupération

La pause doit préciser si elle bloque dépôts, retraits, changements de validateurs ou seulement une catégorie d’actifs.
Un retrait déjà signé pendant la pause nécessite une règle claire lors de la reprise.
La rotation d’urgence conserve un journal de l’ancien ensemble, du nouveau seuil et de la hauteur d’activation.
La réconciliation compare nonces consommés, messages signés, paiements EVM et passifs de la chaîne source.
Tout écart doit être classé avant relance : retard, doublon, signature invalide ou déficit réel.
La récupération ne doit jamais réinitialiser le nonce pour rendre l’historique plus simple.
Ce parcours est documentaire : aucune installation, compilation, transaction ou exécution de tests.
Les hypothèses peuvent être confrontées à Bridge2.sol, Signature.sol et aux tests du dépôt.
