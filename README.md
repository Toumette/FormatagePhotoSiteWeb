# FormatagePhotoSiteWeb
Liste des opérations à effectuer pour préparer des photos afin de les insérer le plus efficacement possible dans les pages d'un site Web.

Testé avec GIMP sous OpenSuse Leap ; photos uploadées sur serveur Web NGINX avec CMS GRAV

Liste des commandes à réaliser :

1) ouvrir la photo avec GIMP

2) rogner les parties indésirables :

    a) outils > outils de sélection > sélection rectangulaire > définir le cadre de la sélection avec le curseur
    
    b) image > rogner selon la sélection

3) éventuellement ajouter des traits sur la photo ou gommer ou flouter une zone :

    a) outils > outil de peinture > crayon ou pinceau ou gomme...
    
    b) tracer les traits (shift pour des lignes droites)
    
    si besoin, modifier préalablement la taille ou l'aspect du trait :
    outil > nlle boîte à outils > crayon (ou autre...) (2 clics) > taille du trait etc. > enregistrer

4) définir l'échelle et la taille de la photo :

    a) en bas de la fenêtre principale de GIMP, définir l'affichage à 100%
    
    b) image > échelle et taille de l'image > définir la largeur (400 à 600 px environ)
       (la hauteur se calcule automatiquement)
       
    c) choisir la résolution xy (75 px/inch env.)
    
    d) cliquer sur "échelle" pour appliquer et sortir

5) exporter pour le Web :

    a) fichier > exporter sous > donner un nouveau nom avec l'extension ".jpg"
    
    b) en bas de la fenêtre : sélectionner le type de fichier (selon l'extension)
    
    c) cliquer sur "exporter"
    
    d) dans la fenêtre "Exporter l'image comme JPEG" cliquer sur "Afficher l'aperçu..."
       afin de voir l'effet de la compression en direct
       
    e) régler la qualité avec le curseur (50% à 95% environ) en cherchant la taille minimale
       permettant d'avoir une image satisfaisante sans excès de qualité
       
    f) cliquer sur "exporter"

6) fermer "GIMP" sans conserver les modifications
