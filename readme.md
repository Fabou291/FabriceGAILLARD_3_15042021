# P3 - Dynamisez une page web avec des animations CSS
https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/DW_P3/Brief%20cre%CC%81atif%20-%20Ohmyfood!.pdf
## Identité graphique

- Font : 
    - Logo et titres: Shrikhand
    - Texte: Roboto
- Couleurs :
    - primary : #9356DC
    - secondary : #FF79DA
    - tertiary : #99E2D0


## Enjeux

- Développer un site proposant le menu de 4 grands restaurants parisiens.
- Permettre la réservation en ligne et la composition de menus.


## Technologies

Le développement devra se faire en CSS, sans JavaScript.
✓ Aucun framework ne devra être utilisé
✓ Utiliser SASS
✓ Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML


## Compatibilité

✓ Le site sera developpé en utilisant l'apporche mobile-first
✓ L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
✓ Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.


## Livrable attendus

- Page d'accueil : 
    ✓ Input permettant de choisir ou saisir un lieu
    ✓ Courte présentation de l'entreprise (article ? aside ?)
    - Une section contenant les 4 menus sous forme de carte. Au click on est redirigé sur la page du menu
- 4 pages de menu
    ✓ article : contient le menu du restaurant

- Footer : 
    ✓ Identifique sur toute les pages
    ✓ Au clic sur "Contact, renvoyé sur une adresse mail

- Header :
    ✓ Présent sur toutes les pages
    ✓ Sur la page d'accueil, il contient le logo du site
    ✓ Sur les autres, un boutons de retour apparait

## Effets graphiques et animations

✓ Les effets au clic et survol seront visible sur la maquette
✓ Pas de javascript, uniquement CSS

- Boutons :
    ✓ Au survol : **couleur de fonds légèrement éclairci** et **ombre portée plus visible**
    ✓ Bouton "j'aime" en forme de coeur
        - Au clic : se rempli progressivement (pour la version desktop, au survol)

- Page d'accueil
    - Un loading spinner devra apparaitre pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de la page. Libre sur le design du loading. Tout en CSS.

- Pages de menu
    ✓ Les plats devront apparaître progressivement avec un léger décalage dans le temps (soit un par un, soit par groupe “Entrée”, “Plat” et “Dessert” )
    ✓ Pour l'ajout des plats à sa commande en cliquant dessus : Apparaît une petite coche à droite du plat. Elle devra coulisser de la droite vers la gauche. (Peut être déclanché au survol pour la version desktop)
        - /!\ Revoir peut être la pseudo class qui l'active ?

    ✓ Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.
    

