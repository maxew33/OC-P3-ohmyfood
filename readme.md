# ohmyfood

## identité graphique
- Polices
  * logo et titre: Shrikhand
  * texte: roboto

- Couleurs
  * Primaire: violet #9356DC
  * Secondaire: rose #FF79DA
  * Tertiaire: turquoise #99E2D0

## fonctionnement
- Technologies
  * Développement en CSS, pas de JS
  * Aucun framework mais SASS possible (et encouragé)
  * Aucun CSS dans une balise HTML
  * code versionné sur Github et accessible via Github Pages.

## compatibilité
- support
  * mobile first
  * mise en page libre pour desktop et tablette
  * responsive sur mobile, tablette et desktop

- navigateur
  * compatible avec les dernières versions desktop de chrome et firefox

## contenu des pages
- Page d'accueil
  * Affichage de la localisation des restaurants
  * Courte présentation de l'entreprise
  * Section contenant les 4 menus sous forme de carte (au clic sur la carte => redirection vers la page du menu)

- Pages du menu
  * 4 pages contenant chacune le menu d'un restaurant

- Footer
  * le même sur toutes les pages
  * au clic sur contact, renvoi vers adresse mail.

- Header
  * présent sur toutes les pages
  * accueil => logo du site
  * pages de menu => bouton de retour vers la page d'accueil

## Effets graphiques et animations
- Boutons
  * au survol => couleur de fond s'éclaircit légérement, ombre portée plus visibles
  * bouton "j'aime" se remplit progressivement au clic

- Accueil
  * loader spinner, apparait pendant 1 à 3 secondes et couvre l'intégralité de l'écran

- Pages de menu
  * apparition progressive des palts avec un léger décalage dans le temps
  * au clic, apparition d'une coche qui coulisse de droite à gauche. Si nom du plat trop long => rognage avec points de suspensions

