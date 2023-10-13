# Oh my food !
Quatrième projet du parcours "Développeur Intégrateur web" chez OpenClassroom.
L'objectif est d'intégrer la maquette d'une jeune star-up nommée "Ohmyfood" permettant la commande de repas gastronomique auprès de grands restaurants, le tout en ligne (prototype en suivant le lien ci-contre).
(https://www.figma.com/proto/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=25368-591&scaling=scale-down&page-id=0%3A1&starting-point-node-id=25368%3A591&show-proto-sidebar=1)

### Visualiser le site ici 
https://samra-git.github.io/P4_ohmyfood/

## Technologies
- Le développement devra se faire en CSS, par compilation via Sass
-  PAS de JavaScript ni Bootstraps
- Pas d'attribut style dans le HTML.


## Compatibilité
La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées. Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Lien vers la validité CSS (https://validator.w3.org/)
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.


## Contenu des pages

### Page d'accueil
- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Fonctionnement du concept.
- Une section contenant 4 images correspondantes chacune à un restaurant. Au clic de la carte, l’utilisateur est redirigé vers la page menu d'un restaurant.

### Pages de menu
- 4 pages contenant chacune le menu d’un restaurant.

### Header
- Le header est commun à toutes les pages du site, il contient le logo du site.
- Sur les pages de menu, une flèche de retour vers la page d’accueil

### Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.


## Effets graphiques
### Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic

### Page d’accueil
- Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

### Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. 
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

## Identité graphique
### Polices
- Logo et titres: Shrikhand
- Texte: Roboto
- Les icones proviennent de [Font Awesome](https://fontawesome.com/)
- Les couleurs sont : primaire #9356DC - secondaire #FF79DA - tertiaire #99E2D0


