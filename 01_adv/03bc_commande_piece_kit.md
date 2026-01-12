---
pour: ADV
intitulé: Création de commandes avec des pièces issus de kits
commentaire: ⚠️ CRITIQUE • Décomposer un kit immédiatement après création de la commande
---
> **warning.upper():** **La décomposition du kit est indispensable**
> 
> Lorsqu’une commande client inclut **une pièce issue d’un kit** (ex. `ANGOLO/KITFLO4`), **le kit doit impérativement être décomposé en stock avant toute préparation**.
> Cette opération consiste à :
> - sortir le kit du stock
> - injecter en stock chacune des pièces composantes
> - mettre à jour les quantités correspondantes

> **example.upper():** Exemple concret : `ANGOLO/KITFLO4`
> 
> | Article               | Stock initial | Action stock              | Stock final |
> |-----------------------|---------------|---------------------------|-------------|
> | ANGOLO/KITFLO4        | 1             | Sortie du kit             | 0           |
| ANGOLO 24/2           | 0             | Entrée composant          | 1           |
| PLAQUES 580V          | 0             | Entrée composant (×2)     | 2           |
| BRAS 580A             | 0             | Entrée composant (×2)     | 2           |
| EMETTEURS FLO4        | 0             | Entrée composant (×2)     | 2           |

> **failure.upper():** **Un kit non décomposé entraîne**
> Une pièce considérée comme manquante en stock sur le terminal logistique.
> 
> Deux cas possibles :
> 1. Le préparateur identifie l’anomalie et prévient l’ADV
> > **success.upper():** L'ADV procède à la mise à jour des quantités.
> > → La préparation peut ensuite être reprise correctement.
> 
>  2. Le préparateur ne détecte pas l’anomalie et finalise la préparation en validant le message :  _« Voulez-vous finaliser même s’il manque des pièces ? »_
>     
>     Conséquences si les articles ont pourtant été préparés physiquement :
> 	    - Incohérences de stock
> 	    - Génération d’un reliquat non justifié
> 	    - Correction manuelle lourde pour l’ADV afin de régulariser les stocks dans Satelix
> 
> Cette situation est **entièrement évitable** en procédant à la **décomposition du kit avant la préparation**.

---
##### Actions à suivre
[05 Transformation PL](05 Transformation PL.md)

##### Menus
[↩️ Retour à la création d'un bon de commande](00bc_creation_bc.md)
[↑ Retour à l'accueil](../00_home/accueil.md)