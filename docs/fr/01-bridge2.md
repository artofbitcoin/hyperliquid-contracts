# Bridge2 comme frontière HyperEVM

Bridge2 organise le passage d'actifs et de messages entre Hyperliquid et l'environnement EVM.
Le contrat ne doit accepter qu'une origine autorisée et une charge utile conforme au format attendu.
Les identifiants de message et les états de consommation empêchent une seconde exécution du même transfert.
La conservation de valeur doit être vérifiée séparément pour chaque chemin de dépôt, retrait et remboursement.
Les événements servent de journal public aux indexeurs, mais ne remplacent pas les contrôles d'état du contrat.
Lire le bridge exige donc de suivre à la fois les appels externes, le stockage et les émissions d'événements.

Suite : [02 — Signatures](02-signatures-et-domaines.md).
