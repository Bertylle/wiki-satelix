---
pour: ADV
intitulé: Présentation des infos attribuables aux commandes
commentaire: |-
  1. Possibilité de mail automatique du BL à un commercial client, 
  2. Ne pas utiliser le champ commentaire pour transmettre des infos importantes
---

## Présentation des infos libres ^haut
Des champs libres d’en-tête peuvent être renseignés si nécessaire pour notifier les préparateurs avec des informations complémentaires. Les infos libres sont accessibles via le bouton `Informations → Infos libres`

![](acces_infos_libres.gif)

---
[⬇️Actions à suivre](01BC • Informations supplémentaires#^bas.md)

---
> **note.upper():** Référence client
> Indiquer dans ce champ le numéro de la commande côté client pour que celui-ci puisse mieux tracer ses commandes de son côté.

> **note.upper():** Préparateur
> Possibilité d'attribuer la préparation à un préparateur dans la liste : NL, JC, FLH, MDE.
> > **warning.upper():** Les autres prépateurs ne voient pas la PL sur leur terminal.

> **note.upper():** Instruction de livraison
> Pré-requis Satelix pour la gestion avec le transporteur, l'ADV ne doit pas y toucher.

> **note.upper():** Priorité
> Définit le niveau d’urgence de la commande.
> - **100 — Urgente**  
>   La commande apparaît en tête de la liste des préparations (PL) sur le terminal.
> - **0 — Standard**  
>   La commande est enregistrée et sera préparée après les commandes prioritaires.
> > **info.upper():** Rappel, sur les terminaux, les PL sont triées par :
> > - priorité
> > - date de livraison
> > - mode d'expédition pour que le mode Enlèvement apparaisse en haut.
> >
> [En savoir plus sur l'affichage des PL sur le terminal](0 Priorite.md)

> **note.upper():** Description marchandise
Champ obligatoire pour la création d'étiquette transporteur Schenker.
Possibilité de pré-remplir ce champs côté ADV en amont sinon rempli par les préparateurs.

> **note.upper():** Livraison avant 13h
> A renseigner pour Schenker

> **note.upper():** Photo
Possibilité de visualiser ici la photo du colisage prise par les préparateurs.

> **note.upper():** Livraison directe `dom6tm`
Mettre sur `oui` si la livraison doit être livrée au siège de Dom6TM.
[En savoir plus sur Dom6TM](En savoir plus sur Dom6TM.md)

> **note.upper():** Commentaire
> Possibilité d'indiquer un commentaire qui sera affiché une seule et unique fois lorsque le préparateur ouvre la préparation de livraison.
> > **todo.upper():** Recommandation d'utilisation
> Ne pas mettre de message d'importance capitale ici car **impossibilité** de relire le commentaire ultérieurement.
> 
> > **bug.upper():** AMÉLIORATION 
> > - [ ] Sur le terminal, possibilité de revoir le commentaire dans le détail de la PL ou sur l'écran final de la PL. #amelioration
> > - [ ] PHOTO DU TERMINAL → Module Préparation de Livraison → Ouvrir une PL → Afficher la page des informations relatives à la PL pour vérifier que les commentaires n'apparaissent pas. #photo

---
[⬆️ Revenir en haut](01BC • Informations supplémentaires#Présentation des infos libres haut.md)

##### Actions à suivre ^bas
[→ Cas d’une commande contenant une pièce issue d’un kit](03BC • Commande piece kit.md)
[→ Cas d’une commande groupée pour plusieurs références client](03BC • Commande groupee.md)
[→ Cas d'une commande client avec commande fournisseur associée](03 Commande fournisseur liée.md)

##### Menus
[↩️ Retour à la création d'un bon de commande](00BC • Création BC.md)
[↑ Retour à l'accueil](00_Home/Accueil.md)