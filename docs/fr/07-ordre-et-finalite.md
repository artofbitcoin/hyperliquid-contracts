# 7 — Ordre, nonce et finalité

Le nonce transforme une suite de retraits en machine d’état ordonnée.
Accepter un nonce futur créerait un trou ; accepter un nonce passé rejouerait une sortie déjà payée.
Le message signé doit engager chaîne, contrat, token, destinataire, montant et nonce.
La collecte de signatures hors chaîne doit référencer exactement le même hash canonique.
Une réorganisation de la chaîne source exige une politique de confirmation avant signature par le comité.
Le contrat destination ne peut pas détecter seul qu’un événement source a perdu sa finalité.
Pour un actif représentant Bitcoin, la finalité Bitcoin, celle de Hyperliquid et celle de l’EVM restent trois hypothèses distinctes.

Suite : [solvabilité](08-solvabilite-et-tokens.md).
