# *Ohmyfood!*

*Ohmyfood!* est le 3ème projet du parcours formation "Développeur Web" de l'école *OpenClassRooms*.  
L'objectif de ce projet est d'intégrer et de dynaliser une page web avec des animations CSS en utilisant le préprocesseur SASS.

## Présentation de l'entreprise

*Ohmyfood!* est une entreprise de commande de repas en ligne. Leur concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants car leur menu est préparé à l’avance. Plus de perte de temps à consulter la carte!

Ils souhaitent proposer à leurs clients les menus de restaurants gastronomiques.  
Développé à *New-York* dans un premier temps, ils souhaitent également élargir leur concept à la capitale de la gastronomie : *Paris*.

![image e-ohmyfood](/images/screenshot.png)

## Objectifs

Dans ce projet, entreprise *Ohmyfood* nous a mandaté pour réaliser les objectifs suivants :  

* Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens;  
* Phase 2 : Permettre la réservation en ligne et la composition de menus.

Brief complet [e-ohmyfood](/images/Brief%20projet%20Ohmyfood!.pdf)

## Fonctionnement

* Technologie 
 
  * Le développement se fait en CSS, sans JavaScript
  * Aucun framework n'est utilisé 
  * Utilisation du préprocesseur SASS;
  * Aucun code CSS n'est appliqué via un attribut dans la balise HTML;
  * Tout le code est versionné sur GitHub et le site est accessible sur GitHub Pages.

* Compatibilité

  * L’ensemble du site est en responsive sur mobile, tablette et desktop;
  * Les pages sont validées W3C en HTML et CSS;
  * Le site est parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

## Livrables attendus

### Contenu des pages

* Page d'accueil (x1)

  * Affichage de la localisation des restaurants.   
    À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu;
  * Une courte présentation de l’entreprise;
  * Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

* Page de menu (x4)

  * 4 pages contenant chacune le menu d’un restaurant.

* Footer

  * Le footer est identique sur toutes les pages;
  * Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

* Header

  * Le header est présent sur toutes les pages;
  * Sur la page d’accueil, il contient le logo du site;
  * Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.
  
### Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette.

* Boutons

  * Au survol, la couleur de fond des boutons principaux s’éclaircie légèrement.
    L’ombre portée est également visible;
  * À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de coeur est présent sur la maquette. Au clic, il se remplit progressivement.  
    Pour cette version, l'effet apparaît au survol sur desktop.

* Page d'accueil 

  * Un “loading spinner” est incorporé sur cette maquette.
    Il apparaît pendant environ 3 secondes quand on arrive sur la page d'accueil, couvre l'intégralité de l'écran, et utilise les animations CSS (pas de librairie).  
    Le design de ce loader n’est pas défini, mais il est cohérent avec la charte graphique du site.

* Page de menu

  * À l’arrivée sur la page, les plats apparaîssent progressivement avec un léger décalage dans le temps.  
    Ils apparaîssent un par un.
  * Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. 
    Cette coche coulisse de la droite vers la gauche. Pour cette première version, l’effet apparaît au survol sur desktop. Si l’intitulé du plat est trop long, il dst rogné avec des points de suspension.

### Identité graphique

* Polices

  * Logo et titres : Shrikhand
  * Texte : Roboto

* Couleurs 

  * Primaire : #9356DC
  * Secondaire : #FF79DA
  * Tertiaire : #99E2D0

  __Conclusion__ : venez visiter la 1ère version du site __*Ohmyfood*__ sans plus attendre!!! [Ohmyfood_by_Dan] (https://dandev33300.github.io/ohmyfood_by_dan/)