(TODO : convertir en MARKDOWN...)

# FormatagePhotoSiteWeb

### Liste des opérations à effectuer pour préparer des photos afin de les insérer le plus efficacement possible dans les pages d'un site Web.

* Testé avec GIMP sous OpenSuse Leap ; photos uploadées sur serveur Web NGINX avec CMS GRAV

Liste des commandes à réaliser successivement :

1. ouvrir la photo avec GIMP

1. rogner les parties indésirables :

    1. outils > outils de sélection > sélection rectangulaire > définir le cadre de la sélection avec le curseur
    
    1. image > rogner selon la sélection

1. éventuellement ajouter des traits sur la photo ou gommer ou flouter une zone :

    1. outils > outil de peinture > crayon ou pinceau ou gomme...
    
    1. tracer les traits (shift pour des lignes droites)
    
    si besoin, modifier préalablement la taille ou l'aspect du trait :
    outil > nlle boîte à outils > crayon (ou autre...) (2 clics) > taille du trait etc. > enregistrer

1. définir l'échelle et la taille de la photo :

    1. en bas de la fenêtre principale de GIMP, définir l'affichage à 100%
    
    1. image > échelle et taille de l'image > définir la largeur (400 à 600 px environ)
       (la hauteur se calcule automatiquement)
       
    1. choisir la résolution xy (75 px/inch env.)
    
    1. cliquer sur "échelle" pour appliquer et sortir

1. exporter pour le Web :

    1. fichier > exporter sous > donner un nouveau nom avec l'extension ".jpg"
    
    1. en bas de la fenêtre : sélectionner le type de fichier (selon l'extension)
    
    1. cliquer sur "exporter"
    
    1. dans la fenêtre "Exporter l'image comme JPEG" cliquer sur "Afficher l'aperçu..."
       afin de voir l'effet de la compression en direct
       
    1. régler la qualité avec le curseur (50% à 95% environ) en cherchant la taille minimale
       permettant d'avoir une image satisfaisante sans excès de qualité
       
    1. cliquer sur "exporter"

1. fermer "GIMP" sans conserver les modifications
