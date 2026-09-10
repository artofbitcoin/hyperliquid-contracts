# Rejeu, ordre et transitions d'état

Un nonce consommé transforme une autorisation signée en capacité utilisable une seule fois.
L'état doit être marqué avant tout appel externe susceptible de réentrer, selon le modèle checks-effects-interactions.
Les transferts asynchrones nécessitent des états intermédiaires explicites plutôt qu'un simple booléen terminé.
Une reprise après échec ne doit ni bloquer définitivement les fonds ni permettre une double finalisation.
L'ordre des messages entre Hyperliquid et HyperEVM fait partie de la propriété de sécurité.
Les tests de bridge sont la meilleure carte des séquences adverses anticipées par les auteurs.

Suite : [04 — Jetons](04-jetons-et-appels-externes.md).
