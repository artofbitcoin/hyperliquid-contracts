# 6 — Quorum et rotation des validateurs

Bridge2 accepte une transition seulement si les signatures satisfont le seuil configuré.
Le seuil doit être interprété avec l’ensemble actif exact, pas avec une liste historique ou future.
Les signataires dupliqués ne doivent jamais augmenter artificiellement le poids obtenu.
Une rotation doit définir l’ordre entre activation du nouvel ensemble et validité des messages en attente.
Réduire simultanément le nombre de validateurs et le seuil peut créer une fenêtre de sécurité plus faible.
Les événements doivent permettre de reconstruire ensemble, poids et seuil associés à chaque transition.
Une procédure d’urgence ne doit pas devenir une voie permanente contournant le quorum normal.

Suite : [ordre et finalité](07-ordre-et-finalite.md).
