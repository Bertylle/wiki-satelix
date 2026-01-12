> > **info.upper():** Sur les terminaux, les PL sont triées par :
> > - priorité
> > - date de livraison
> > - mode d'expédition pour que le mode Enlèvement apparaisse en haut.
> > > **example.upper():** Exemple concret
> > > 1. **Dom6TM**
> > >    Priorité : 100
> > >    Date de livraison : 15/01/2025
> > >    Mode d'expédition : TNT
> > > 2. **ABH 44**
> > >    Priorité : 0
> > >    Livraison prévue : 10/01/2025
> > >    Mode d'expédition : ENLEVEMENT
> > > 3. **TRADIMEN EURL**
> > >    Priorité : 0
> > >    Livraison prévue : 10/01/2025
> > >    Mode d'expédition : SCHENKER
> > > 
> > > - [ ] PHOTO DU TERMINAL → Module Préparation de Livraison → La liste des PL en cours avec les priorités #photo  
> 
> > **question.upper():** A vérifier
> > - [ ] Les PL s'affichent bien par ordre de priorité sur les terminaux. #averifier
> > - [ ] Priorité : 100 = faible priorité et la PL s'affiche en bas ? OU Priorité : 100 = grande priorité et la PL s'affiche en haut ? #averifier