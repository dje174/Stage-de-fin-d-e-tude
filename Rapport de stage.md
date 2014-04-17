#Structure Rapport de stage
##Raspberry Design Février - Mai 2014

### 01. Remerciements

Un grand merci tout d'abord à Renaud Charpentier de m'avoir accepté dans le cadre de mon stage de fin d'étude en technique infographique, spécialisation web dans son entreprise Raspberry Design SPRL. Je remercie également Étienne Denoël, sous-traitant de Renaud Charpentier m'ayant aider plusieurs fois sur certains des projets durant mon stage.

Je remercie également mon professeur superviseur, Pierre Worontzoff pour m'avoir conseillé dans la rédaction de mon rapport de stage.


### 02. Introduction 

Baccalauréat en troisième année à la Haute École de la Province de Liège à Seraing en Techniques Graphiques, j'ai effectué un stage en entreprise de 12 semaines chez Raspberry Design SPRL. Le stage s'est déroulé du 10 février au 02 mai 2014.

Ce que j'attendais de ce stage:

- D'être confronté au monde du travail, par là, je parle d'une expérience différente des bancs de l'école;
- D'appronfondir etaccroitre mes compétences déjà acquises au cours de mes études tant au niveau technique que créatif;
- De découvrir de nouvelles techniques et méthodes autour de ma spécialisation;
- Être forcé à travailler avec des échéances pour les projets, ce qui est totalement différent des projets dont on nous habitue à l'école;
- Découvrir comment se passent les contacts entre les clients et un infographiste;


Après avoir envoyer mon CV dans plusieurs entreprises, Renaud à directement répondu et organisé un entretien. Après m'être renseigner un peu plus sur l'entreprise, j'ai choisi ce lieu de stage pour plusieurs raisons:

- Raspberry Design est une société de communication, identité visuelle, ils créent une image autour d'une marque ou d'un produite, et je trouvais très intéressant d'être dans cet esprit de conception total autour d'un produit (logo, packaging, imprimés, site internet etc);
- Diversifier et étendre mes compétences sachant que j'allais apprendre deux nouveaux CMS, Silverstripe et Drupal. Ces deux CMS sont très utilisés et très demandés par les employeurs.
- Raison personnelle mais utile, l'entreprise se trouve seulement à 20min de transport en communs de mon domicile.
- Le fait qu'ils ne soient que deux personnes dans un bureau prédictait une bonne ambiance de travail.

### 03. À propos de la société
##### 03.01 Historique

Société créée en 2009 par Renaud Charpentier, ancien étudiant de la Haute École de la Province de Liège en techniques graphiques, spécialisation web. C'est après l'obtention de son diplôme qu'il décida de se lancer en tant qu'indépendant dans le dévelopement de sites webs mais aussi d'identités visuelles et donc dans tout ce qui est 2D, imprimés etc. La société est située dans le domaine des Hauts-Sarts à Herstal dans les locaux de l'entreprise de nettoyage Gestanet. Société également client de Raspberry Design.

##### 03.02 Services

Le service principal de la société est le développement web. Avec la possibilité de développer toute sorte de site, tel qu'un site vitrine, catalogue, e-commerce, e-business, intranet ou même de petite application web spécifique à une requète bien spécifique (application de gestion etc).

Il propose également de créer une réelle identité autour d'une marque ou d'une entreprise, premettant de réfleter l'image de la société du client. Toute une série de services découlent donc de ce dernier, comme l'imprimé publicitaire, l'imprimé textile, le lettrage et le packaging.

##### 03.03 Clients et secteurs d'activités

Petit à petit l'entreprise agrandi son réseau et ses clients. Réalisant principalement des projets pour des particuliers et entreprises (commercant, restaurateur, entreprise nottayage, exportation etc.) mais aussi pour de plus gros clients ayant plus d'influence comme des le club de Brugge, Gestanet, HEC Ulg. Il travaille également avec d'autre entreprise comme DJM Web qui est une entreprise de communication visuelle qui se trouve à Visé.

##### 03.04 Mon rôle dans la société

### 04. Les CMS utilisées dans les projets
##### 04.01 Découverte de Silverstripe
###### 04.01.01 Découverte du CMS Silverstripe
N'ayant jamais utiliser ni appris sur ce CMS, Renaud ma d'abord laissé une matinée pour réaliser quelques tutoriaux de prises en main disponible gratuitement sur le site du CMS. Cela m'a été d'une grande aide pour pouvoir alors entamer le projet.
###### 04.01.02 Le projet
Développement de *Mis En Valeurs* qui une société de coaching de décoration. C'est un site vitrine avec des pages "Accueil", "Services", "Tarifs", "Réalisations", "Contact" et "Blog". Un fichier Illustrator était fournis avec le design a réaliser. La partie créative du développement était donc déjà faite.

Les contraintes principales ici étaient que le client doit pouvoir gérer son contenu textuel et images directement via l'interface administrative du CMS pour éviter de devoir contacter le développeur à chaque besoin d'un changement. Le site après développement des pages, devait être un site **one-page** avec les pages chargées via jQuery par un appel Ajax. Il fallait également que les ancres du menu menent directement au menu de la page dont elles correspondent. Pour cela, il a fallu calculer le haut de chaque page moins la hauteur du menu de sorte à ce que l'on soit redirigé directement vers l'endroit concerné du menu.

Il a fallu ensuite développé le site avec les **médias queries** pour l'affichage sur tout type d'écrans. Les dimensions vont de 320px à 2000px, d'une très petite dimension à une très grande permet de s'adapter et d'acquérir de l'expérience sur la façon de dispositionner les boîtes et fonctions de la surface disponible et de la largueur d'écran disponible.

Mise en place également d'une mini-application pour la page des tarifs qui consiste en un formulaire pour calculer la valeur d'un bien. Avec un tableau de données administrable via l'interface du CMS (ici pour que l'admin insère des prix) et caché pour le client qui sélectionnera mettra seulement un chiffre dans un champs texte qui sera ensuite multiplier par la donnée cachée pour calculer un total du bien. Le tout réalisé via jQuery pour que le résultat du formulaire soit instantané.

La dernière étape et pas des moindre, les tests utilisateurs en plus de vérification dans Woorank, GTMetrix et la validation HTML via le site du W3C.

###### 04.01.03 Mon opnion sur le CMS
Silverstripe est une découverte assez impressionnante, c'est un CMS assez facile à prendre en main quand on manipule déjà d'autres CMS et PHP, très pratique et surtout très personnalisable au niveau de l’interface admin du site. Ce qui est très pratique quand on doit administrer des fonctionnalité pour le client dans l'interface.

##### 04.02 Découverte de Drupal
###### 04.02.01 Découverte du CMS Drupal 
Drupal est un très puissant CMS très répandu et utilisé par de nombreux organisme à travers le monde (Sites gouvernementaux, blog, e-commerces etc). Il est libre et open-source. N'ayant jamais eu l'occasion d'approcher ce CMS, qui est un peu plus difficile à prendre en main que d'autres, Renaud m'a une fois de plus laisser le temps de suivre quelques tutoriels et autres formations pour bien m'initier au CMS avant de commencer le projet en question. Cela m'a vraiment bien aider, j'ai suivi le tutoriel "Atelier Drupal" de Cyprien Roudet qui explique Drupal pour quelqu'un n'ayant jamais utilisé le CMS. Apprentissage de l'interface graphique, gestion de contenu via l'interface, interêts d'utilisation des modules essentiels, création de module et création d'un thème.
###### 04.02.02 Initiation à la création de module
Utiliser les modules de Drupal, c'est bien mais une fois les bases assimiler, l'idéal est de créer ses propres modules pour comprendre l'interêt de ceux-ci et des vastes possibilités qu'ils apportent. Car si l'on veut une fonctionnalité particulière qui n'existe pas déjà dans un autre module mais surtout que l'on veut éviter les modules trop lourds qui chargent beaucoup de librairies diverses et qui dépendent d'autres modules etc. J'ai donc suivit le tutoriel d'"Atelier Drupal" qui propose le développement d'un petit module et qui explique les bases de la conception d'un module.
###### 04.02.03 Initiation à la création de thème 
###### 04.02.04 Le projet
###### 04.02.05 Mon opnion sur le CMS
Drupal est un outil très puissant, très personnalisable, certes il peu paraitre effrayant à appréhender les premières fois, mais on remarque juste qu'il est très vaste et que les possibilités sont énormes. Les ressources disponibles sont énormes j'ai été impréssionner par la gestion du contenu via l'interface admin qui supprime tout contact avec du SQL.

### 05. Intégration HTML et CSS

La plupart de l'intégration HTML dans les projets que j'ai réalisé s'est faite via des vues avec les CMS Silverstripe et Drupal. Cela s'est basé sur l'apprentissage des fonctionnements de ces deux CMS sensiblement pareil au niveau du fonctionnement puisqu'ils découlent tous deux d'une architecture PHP de type MVC (Modèles - Vues - Controlleurs). Bien sur, de l'un à l'autre, la syntaxe n'est pas pareil et l'un bénéficie de certaines option prédéfinie que l'autre ne possède pas et vice-versa.

Pour le CSS, j'étais libre d'utilisé les outils que je voulais, j'ai fais les premiers projets en CSS simple jusqu'au moment ou j'ai finalement utilisé SASS avec un compilateur pour un comfort de travail plus accru. Pour les projets **Mis En Valeurs** et **Gestanet**, j'ai du utiliser les **médias queries** pour que le site soit accessible sur le maximum de supports.

### 06. Templating et mise en page dans Illustrator
##### 06.01 La partie inspiration
Dans la réalisation d'un layout, le pré-projet que l'on va montrer au client pour qu'il valide le futur design de son site, l'une des partie très importante est l'inspiration. Cela m'apprend à chercher de l'inspiration la où il y en a et trouver différents sites pour s'inspirer de portfolio existant. Tout artiste se doit de s'inspirer de ce que font les autres, où du moins s'informer, allez voir les dernières tendances, les choses à faire ou à ne pas faire. Renaud m'a conseillé d'aller prendre inspiration la plupart du temps sur des banques de thèmes telles que ThemesForest, ThemesKing et d'autres. Pour démarrer un projet et voir dans quelle direction on se dirige, c'est très important et parfois un gain de temps énorme.

##### 06.02 La charte colorimétrique
Lorsque l'on travail pour un client, et surtout si le client dispose déjà d'une certaine identité visuelle (logo, carte de visite, packaging), il faut impérativement suivre le code couleurs ainsi que le style du logo existant. Et réaliser ensuite le template en rapport avec les couleurs imposée par le client.

##### 06.03 La mise en page
Créer un layout avant un projet dans Illustrator ou autre programme de mise en page est quelque chose que je n'avais pas l'habitude de faire mais qui au long de ce stage, s'est avérer devenir pour moi une chose indispensable. J'ai également appronfondit ma maîtrise du logiciel **Illustrator** qui est assez pratique pour la réalisation de template. L'utilisation de repères est bien entendu l'une des choses les plus importantes pour moi pour que tout soit bien structuré et symétrique. Et cela même si l'on ne fait pas un simple design en blocs.

##### 06.04 Les projets

J'ai du réaliser plusieurs templates pour plusieurs clients:

###### Raspberry Design
Refonte du site de **Raspberry Design** (www.raspberrydesign.be). Il s'agit de mettre à jour le style graphique du site existant datant de 2011. 
Première étape dans l'établissement de la refonte graphique, chercher de l'inspiration. La deuxième partie était de concevoir un fichier **Illustrator** de la refonte. Ici, un one-page. Avec comme contrainte de respecter le code colorimétrique du logo de l'entreprise, qui est constitué de rose et vert flash.
Le site se compose de 5 pages "Accueil", "Services", "Portfolio", "À propos" et "Contact".

###### Club de foot F.C. Warsage
Refonte graphique et réalisation d'un template du site du club de football **F.C. Warsage** qui est un club de la région de Visé. La première étape à été une fois de plus l'inspiration et pour ce faire j'ai été m'inspirer de sites de clubs de footballs existants, pour voir comment ils mettent en page leurs informations, comment ils les font ressortir et les mettent en valeurs. Le logo est circulaire et vert clair, je dois donc respecter ces teintes. Utilisation d'un outil très utile qui est **Color Scheme Designer** pour trouver des couleurs qui soit vont bien ensembles ou qui sont complémentaires.

Pour cette refonte, je devais seulement refaire la page d'accueil pour avoir une idée de quel sera le style global du design. Une fois achevée, on ma ensuite demandé de faire 2 autres pages d'accueil avec une mise en page différente pour pouvoir proposer plusieurs démarche au client. Cela fait vraiment rendre compte à quel point c'est parfois difficile de réaliser plusieurs mise en page avec le même contenu mais différentes l'unes de l'autre. C'est par contre un super exercice qui développe i et qui est vraiment bénéfique.

###### Coté Bar Coté Cuisine
Refonte graphique et réalisation d'un template pour le restaurant "Coté Bar Coté Cuisine" qui se trouve à Visé. Il s'agit d'une mise à jour du site réalisé par Raspberry Design en 2010.

Après la partie d'inspiration, j'ai réalisé la page d'accueil avec un grand slider et de grandes images pour accueillir l'utilisateur avec des photos du restaurant pour qu'il sache directement à quoi s'attendre, le style de l'endroite etc, avec un menu en bas qui redirigeras vers les pages classiques du site.

La page d'accueil est dans un style particulier vu qu'il s'agit de bloc avec chaque fois dedans une image mise à 100% de la taille du bloc et une informations textuelles très brève écrite en blanc sur un carré noir semi-transparent. C'est une sorte de second menu qui redirige de manière pratique et agréable vers les grandes sections du site.

La page de contenu, ici présentation du restaurant, tente de reprendre les même marques graphique que le début du site. Avec une barre latérale au contenu à droite avec deux ou trois blocs comme ceux présent dans l'accueil pour proposer à nouveau à l'utilisateur les grandes sections du site pendant qu'il consulte du contenu.

Mon choix ici est de jouer fortement sur l'appui des images. Étant un site pour un restaurant, le site se doit d'être agréable, d'une qualité irréprochable et que l'utilisateur ressente ces valeurs par rapport au restaurant en lui même. Et l'appui d'images apporte encore plus à ces valeurs je trouve.

###### Gestanet SA
Refonte graphique et réalisation d'un template pour l'entreprise Gestanet qui est une entreprise de nettoyage industriel, locaux, vitre etc. La première contrainte était de travailler avec le logo existant qui a des teintes très sombre, avec un vert très foncé proche du noir qui est difficile à mettre avec d'autres couleurs plus vives. Le client est strict dans certains aspects de la mise en page. Tel que l'utilisation du vert foncé du logo et que la mise en page doit être assez simple. Cela m'apprend surtout à développer un design non selon certaines de mes envies, mais en cherchant à les adapter aux besoins et contraintes imposées par le client.

Après la réalisation de deux templates dont un en "one-page", j'ai rencontré le client qui me donna plusieurs commentaires et problèmes négatifs sur ce qui n'allait pas dans le design, tel que le manque de fraîcheur, le design est trop "plat" ainsi qu'un manque de recherche graphique un peu plus poussé.

J'ai donc chercher une fois de plus de l'inspiration sur différent site d'entreprises, mais aussi chez les concurrents direct de cette entreprise, voir ce qu'ils font, comment ils présentent leur entreprise et comment je pourrais faire encore mieux que ses concurrents en essayant d'avoir une identité graphique plus approfondie.

### 07. Interactivité avec JavaScript et jQuery

### 08. Librairies et autres Frameworks

J'ai utilisé plusieurs librairies et plugins dans les différents projets que j'ai réalisé durant mon stage.

####ChartJS
**ChartJS** (http://chartjs.devexpress.com/) est une librairie JavaScript Coté Client qui permet de générer différents styles de graphiques dynamique avec des données. Librairie utilisées pour la refonte du site de l'entreprise **Gestanet SA**, l'ancienne version du site utilisait **Google Charts** qui est la librairie de graphique dynamique de *Google*. Cependant, les librairies *Google* sont souvent assez lourdes et chargent souvent beaucoup de choses inutiles dans votre site, c'est pourquoi j'ai proposé à Renaud d'utiliser **ChartJS** qui est un peu plus légère et beaucoup plus personnalisable.

####Isotope
**Isotope** (http://isotope.metafizzy.co/) est une librairie JavaScript qui permet de trier des éléments et de les filtrer avec des animations personnalisables et très facile à mettre en place. J'ai également du utiliser cette librairie pour le stie de **Gestanet SA** pour la page des référence qui regroupe tous leurs clients avec certains provenant du secteur privé et d'autre du secteur public. D'où l'intérèt ici d'utiliser un filtre. **Isotope** permet donc de de créer un filter en fonction de classes attitrées aux éléments que l'on veut trier. Il suffit juste ensuite de régler et personnaliser les paramètres dans le code JavaScript.

####Slimbox 02
**Slimbox 02** (http://www.digitalia.be/software/slimbox) est un script permettant de charger un lightbox pour les images. Le script est écrit en utilisant le framework **Mootools JavaScripts**. Cette lightbox n'est pas tellement personnalisable et est très classique. Cependant, elle à pour particularité d'être très légère ce qui permet de meilleur performance pour votre site puisqu'elle ne pèse que **4KB**. Je l'ai utilisé pour le site **Mis En Valeurs** pour la galerie d'image de la section portfolio.

### 09. Les clients

- Mis En Valeurs
- Raspberry Design
- F.C. Warsage
- Gestanet SA
- Coté Bar Coté Cuisine
- Joia
- Interface Batterie

### 10. Conclusion et impression



