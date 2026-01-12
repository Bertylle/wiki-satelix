---
pour: ADV
intitulé: Commandes contenant au moins un produit non-suivi en stock
commentaire: Articles non pris en charge par le WMS - Utiliser les procédures historiques
---

> [!failure] **Commande avec articles non-suivi en stock**
>  Les articles **non gérés en stock** ne sont **jamais visibles sur les terminaux logistiques**.  
Ils ne doivent donc **ni être réceptionnés ni préparés** via le WMS.
> 
> Même si le **bon de livraison fournisseur est affiché à l’écran**, la réception **ne peut pas être finalisée** lorsqu’aucun article en suivi de stock n’est présent dans la commande :   **aucune ligne d’article n’est proposée à la réception**, ce qui bloque automatiquement la validation par le préparateur.
>  <p align="center">
>   <img src="reception_article_non_suivi_stock.jpeg" width="400">
> </p>
> 
>  - [ ] PHOTO DU TERMINAL → Module Réception Fournisseur → Ouverture d'un BL avec aucun article a scanner → photo du message d'erreur lorsqu'on essaye de finaliser la réception. #photo 

> [!warning] Règle à retenir — Articles non gérés en stock
> A son arrivée à l'entrepôt, la marchandise doit être **contrôlée physiquement**, validée sur les documents papier, puis **prise en charge par l’ADV** pour la mise à jour administrative, **sans impact sur le stock**.
> 
>  **Les étapes recommandées sont :**
> - Florian **contrôle physiquement la marchandise** à la réception  
> - Il **valide les quantités sur les documents papier** (BL fournisseur)  
> - Les documents sont **transmis à Damien ou Coralie**  
> - Damien ou Coralie **transforment immédiatement la commande en BL**
> - Florian prépare ces commandes avec les BL papier d'après les **procédures historiques**.

---
##### Menus
[[00BC • Création BC|↩️ Retour à la création d'un bon de commande]]
[[00_Home/Accueil|↑ Retour à l'accueil]]