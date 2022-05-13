# OmfProject
OCR - Projet N°3 Ohmyfood - Dynamisez une page web avec des animations CSS

lien vers le site : https://jeajule.github.io/OmfProject/

🟣 Objectifs

Développer un site proposant le menu de 4 grands restaurants parisiens.
Permettre la réservation en ligne et la composition de menus.

🟣 Livrables

 Identité graphique :

    Colorimétire :
      Primaire :   #9356DC
      Secondaire : #FF79DA
      Tertiaire :  #99E2D0
  
  
    Polices :
      Logo et titres : Shrikhand
      Texte : Roboto
  
  
Approche mobile-first mais le site devar néamoins être responsive Desktop, tablette, mobile). Compatible Chrome et Firefox.
  
 Contenu des pages

    Page d’accueil (x1)
      XX  ● Affichage de la localisation des restaurants. 
      XX  ● Une courte présentation de l’entreprise.
      XX  ● Une section contenant les 4 menus sous forme cartes. 
      XX  ●   Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

    Pages de menu (x4)
        ● 4 pages contenant chacune le menu d’un restaurant. 

    Footer
      XX  ● Le footer est identique sur toutes les pages.
      XX  ● Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

    Header
      XX  ● Le header est présent sur toutes les pages.
      XX  ● Sur la page d’accueil, il contient le logo du site.
      XX  ● Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil


Effets graphiques et animations

Les effets accessibles au clic ou au survol devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

    Boutons
      XX  ● Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
            L’ombre portée devra également être plus visible.
      XX  ● Un bouton "J’aime" en forme de cœur est présent sur la maquette.
            Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.
    
    Page d’accueil
      XX  ● Quand l’application aura plus de menus, un “loading spinner” sera nécessaire.
            Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 
            1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran,
            et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas définit,
            toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.
   
    Pages de menu
      XX  ● À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps.
            Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. 
      XX  ● Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître
            une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version,
            l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, 
            il devra être rogné avec des points de suspension. 
