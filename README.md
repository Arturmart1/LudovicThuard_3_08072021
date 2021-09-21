# OhMyFood

Troisième projet du parcours développeur web chez OpenClassrooms.
L'objectif est d'intégrer la maquette d'un site de restauration "OhMyFood". L'intégration est "mobile-first", c'est à dire nativement adapté aux mobiles.

# Éléments fournis par l'entreprise virtuelle:

- La maquette pour de la version smartphone est fournie.
- Toutes les images présentes sur le site sont aussi fournies.
- Les icones proviennent de [Font Awesome](https://fontawesome.com/)
- Les couleurs sont : violet #9356DC - rose #FF79DA et vert menthe #99E2D0
- La police imposée est ["Roboto"](https://fonts.google.com/specimen/Roboto)

# Cahier des charges:

- L'integration doit se faire en HTML5 & CSS3, l'utilisation de SASS est autorisée.
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.
- [Le code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte au validateur W3C HTML et CSS](https://validator.w3.org/nu/?doc=https%3A%2F%2Farturmart1.github.io%2FLudovicThuard_2_08072021%2F) (https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Farturmart1.github.io%2FLudovicThuard_2_08072021%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=fr)

# Contenu des pages, Effets graphiques et animations

Page d’accueil (x1)

- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.
Pages de menu (x4)

- 4 pages contenant chacune le menu d’un restaurant.

Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

Header

- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de coeur est présent sur la maquette. Au clic, il devra se remplir progressivement.

Page d’accueil

- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

Pages de menu

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat.
- Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

# Notes sur la réalisation du projet:

- L'integration est faite sur l'éditeur Visual Studio Code avec les plugins [Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), [Git Extension pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack).
- [SASS] a été utilisé, incluant le système 7-1 pour l'organisation des fichiers.