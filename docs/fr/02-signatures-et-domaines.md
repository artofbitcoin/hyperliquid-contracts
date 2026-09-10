# Signatures et séparation de domaines

Signature.sol centralise la récupération ou la vérification de signataires pour les opérations autorisées.
Une signature sûre engage la chaîne, le contrat, le type d'action, les paramètres et un nonce.
Sans séparation de domaine, une autorisation valide dans un contexte peut être rejouée dans un autre.
L'ordre des champs et leur encodage doivent être identiques côté signataire et côté contrat.
La malléabilité et les valeurs invalides de v, r ou s doivent être rejetées à la frontière.
Le signataire récupéré n'est utile que s'il est ensuite comparé au rôle attendu pour cette action.

Suite : [03 — Rejeu](03-rejeu-et-etat.md).
