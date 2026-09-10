# Jetons et appels externes

Un transfert ERC-20 peut échouer, ne rien retourner ou appliquer des frais selon l'implémentation du jeton.
Le bridge doit interpréter correctement ces variantes et mesurer la valeur effectivement reçue si nécessaire.
Les callbacks et transferts natifs introduisent des points de réentrance autour des changements d'état.
Les adresses nulles, montants nuls et destinations non conformes doivent avoir une politique explicite.
Les approbations persistantes élargissent l'impact d'un contrat externe compromis.
La compatibilité apparente avec une interface ne garantit donc pas la conservation économique du montant.

Suite : [05 — Périmètre](05-perimetre-de-confiance.md).
