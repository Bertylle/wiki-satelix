---
pour: ADV
intitulé: Création de commandes avec plusieurs références clients
commentaire: Créer un bon de commande par référence client, ne plus regrouper
---

> **warning.upper():** Commande avec plusieurs références clients
> Lorsqu’un client souhaite passer plusieurs commandes distinctes (par exemple pour différentes références clients finales), il est impératif de créer un bon de commande (BC) par commande.
> 
> **Chaque commande client doit correspondre à un BC unique.**  
> **Il ne faut en aucun cas regrouper plusieurs commandes clients distinctes sur un même BC.**
> 
> Cette règle permet de :
> - faciliter la préparation des colis en entrepôt,
> - éviter les erreurs de picking,
> - garantir une traçabilité claire entre commande, colis et client final.

[](../media/commande_groupee.png)

> **bug.upper():** Améliorations
> - [ ] **Côté Satelix** : regrouper automatiquement les **références articles identiques** lors de la préparation. #amelioration 
>       **Problème actuel :**  
>       Lorsqu’un même article est présent sur plusieurs références clients, le préparateur doit :
> 	      - scanner l’article à chaque occurrence,
> 	      - saisir la quantité autant de fois que l’article apparaît.
> 	  **Bénéfices attendus :**
> 	  - un picking plus fluide,
> 	  - moins de manipulations répétitives,
> 	  - réduction du risque d’erreur en préparation.