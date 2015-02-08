---
layout: doc
title: Étude de terrain avec les Field Papers
otherguides: "Les autres niveaux"
---

Dans ce chapitre, nous allons voir comment nous pouvons enregistrer les
coordonnées des lieux sans GPS. Nous allons utiliser un outil appelé [Field Papers](http://fieldpapers.org/)
qui vous permet d'imprimer une carte d'une zone géographique, dessiner dessus, y
ajouter des notes et ensuite charger cette version du document dans JOSM, où vous pouvez
ajouter vos informations dans OpenStreetMap. 


## Aperçu des Field Papers

Avant de regarder en détail les Field Papers, voici un aperçu de
la façon dont le processus fonctionne :

1. Sur le site Field Papers, localisez la zone que vous souhaitez cartographier.
Imprimez une carte de cette zone. Vous pouvez choisir d'imprimer avec la carte
OpenStreetMap ou vous pouvez choisir d'imprimer avec l'imagerie aérienne
(si elle est disponible dans votre région).  
![Page d'accueil de FieldPapers](/images/homepage.png)

1. Utilisez votre carte imprimée pour faire le relevé de la zone géographique.
Ajoutez plus d'endroits en les dessinant sur ​​la carte.
Tracez des lignes pour les routes, les formes des bâtiments, etc. 
Rédigez des notes sur chaque emplacement directement sur la carte ou
écrivez les nombres sur la carte correspondant aux numéros de votre
fiche de cueillette, où vous pouvez écrire des informations plus
détaillées sur chaque objet.  
![Example de fieldpaper imprimé](/images/fieldp.png)

1. Numérisez votre papier dans l'ordinateur. Si vous n'avez pas de scanner,
vous pouvez prendre une photo de l'article, si votre appareil est capable
de prendre des photos de haute qualité. Téléchargez l'image sur le site Field Papers.

1. Dans JOSM, chargez le papier manuellement. Utilisez les objets dessinés comme
une référence pour les ajouter numériquement dans OpenStreetMap.  
![Fieldpaper numérisé affiché comme fond dans JOSM](/images/fieldpaperjosm.png)


## Comment ça fonctionne les Field papers?

Si vous suivez le processus décrit ci-haut, vous collecterez des coordonnées
géographiques précises des lieux sans rien de plus
que le papier. Comment est-ce possible?

![code QR](/images/paper_qrc.png)


Lorsque vous imprimez un Field Paper, le document est livré avec un code-barres
carré sur le bas de la page. Ce code à barres permet au site Field Paper de
déterminer l'emplacement exact de la carte que vous utilisez pour l'étude terrain.
Plus tard, lorsque vous chargez le document dans JOSM, tous les objets que vous
avez dessiné seront montrés à leurs emplacements réels. C'est comme utiliser un
GPS pour collecter des informations précises, sauf qu'un bout de apier suffit !

Maintenant, nous allons apprendre à créer et utiliser les Field Paper. 

## Créer et Imprimer

-   Ouvrez votre navigateur web - par exemple Firefox, Chrome, Opera, ou
    Internet Explorer.
-   Dans la barre d'adresse en haut de la fenêtre, tapez la commande suivante
    texte et appuyez sur Entrée :
      [fieldpapers.org](http://fieldpapers.org/)
-   Le site Web devrait ressembler à quelque chose comme ceci :

![Page d'accueil de FieldPapers](/images/homepage.png)

-   Pour l'instant le site n'est accessible qu'en anglais, mais une version 
    française devrait arriver dans quelques mois.

-   Cliquez sur **Make yourself an Atlas** Pour sélectionner la 
    zone géographique à imprimer.

![Création d'un nouvel atlas](/images/makeatlas.png)

-   Vous allez être redirigé(e) vers cette page :

![Adresse de l'atlas](/images/makeyourselfanatlas.png)

-   Cliquez le nom de la zone qui vous intéresse et dans la boîte puis
    sur "Start there".

-   La carte que vous voyez montre la zone que vous désirez imprimer.
    Vous pouvez faire bouger la carte de la même manière que vous le 
    feriez sur le site d'OpenStreetMap, en utilisant le clic gauche
    de la souris pour faire glisser et la molette pour zoomer.
    Cliquez sur les boutons (+) et (-) dans le coin en haut à gauche 
    pour ajuster votre niveau de zoom.

![Zoomer et dé-zoomer](/images/zoominout.png)

-   Juste en dessous de la carte il y a quelques options supplémentaires.
    La première option est pour sélctionner l'orientation de la feuille
    de papier. Vous avez le choix entre portrait et paysage (à l'italienne).

![Choix de l'orientation de l'atlas](/images/choosetile.png)

-   L'option suivante vous permet de choisir le type de données que vous
    désirez utiliser dans votre Field Paper. Vous pouvez sélectionner
    différentes options qui vont influencer l'aspect de la carte.
    Pour l'instant nous allons choisir
    **Black and White**.

![Choix du noir et blanc](/images/blackandwhite.png)

-   Vous devez vous assurer que la fenêtre montre bien ce que vous
    voulez cartographier. Utilisez les contrôles pour redimentionner
    les pages de votre Field Paper et ajuster le nombre de pages.
    Assure-vous que vos pages couvrent pas de trop grandes zones sinon
    elles manqueront de précision et ne seront pas vraiment utiles.
    Si vous vous plantez, pas de panique vous pourrez recommencer.

-   Bon, allez, on imprime maintenant ! Si vous avez trouvé la zone
    qui vous intéresse et avez sélectionné les options pour que votre
    carte rende bien, alors vous êtes prêt. Cliquez sur "Next" à côté
    de la liste de choix déroulants.

![Suivant](/images/labelnext.png)

-   Donnez un nom à la carte. Vous pouvez aussi ajouter du texte qui
    apparaitra sur chaque feuille.

![Nom de l'atlas](/images/name.png)

-   La prochaine option vous permet de sélectionner la disposition.
    Vous pouvez ajouter une grille UTM (Transverse Universelle de Mercator)
    sur chaque carte si vous voulez. Vous pouvez cliquer sur "Maps Only"
    qui est déjà sélectionné par défaut.

![Mise en page](/images/layout.png)

-   Cliquer sur "Finished!"
-   Votre impression est en train de se préparer. Elle apparaîtra sur l'écran
    dès qu'elle sera prête.
    Ça prend quelques minutes en fonction du nombre de pages.

![Génération de l'atlas](/images/preparingyouratlas.png)

-   Quand l'impression est prète, cliquez sur "Download map PDF for print".
    L'imprimé du Field Paper devrait alors être téléchargé.

![Téléchargement du pdf](/images/downloadpdf.png)

-   Quand le téléchargement est terminé, ouvrez le fichier PDF.
    Branchez votre ordinateur à une imprimante et imprimez les pages.
    Si tout se déroule bien, votre carte devrait maintenant être imprimée sur papier.

## Cartographier avec les Field Papers

-   Amenez vos Field Papers à l'extérieur, dans la zone où effectuer l'Étude terrain
    et utilisez-les comme guide vous déplacant et identifiant de nouvelles places qui ne sont pas sur la carte.
-   Tracez des lignes pour les routes, des polygones pour les immeubles, etc. Écrivez des notes relatives à chaque
    localisation directement sur la carte, ou écrivez un numéro sur la carte qui permet le lien avec une description dans votre chahier de notes,
    où vous pouvez ajouter des informations détaillées relativement à chaque objet.
-   Lorsque vous êtes satisfaits avec vos additions sur la carte papier, alors
    vous pouvez les ajouter digitalement dans OpenStreetMap.

## Numériser et Envoyer

-   Les Field Papers sont très utiles pour cartographier avec rien d'autre que
    du papier, mais ne sont pas 100% magie. Nous allons toujours avoir besoin
    d'importer l'imprimé annoté dans JOSM, ajouter l'information numérique et sauvegarder
    les modifications dans OpenStreetMap.
-   La première étape est de numériser votre Field Paper à partir de votre ordinateur.
    Vous pouvez faire cela en connectant un numériseur à votre ordinateur,
    numériser l'imprimé annoté et sauvegarder comme un fichier image.  Si vous n'avez pas
    de numériseur, vous pouvez prendre une photo de l'imprimé. Vous devez cependant faire
    attention à prendre une photo de très bonne qualité.  Assurez-vous que le papier est à plat
    et votre appareil photo directement au-dessus de l'imprimé. Assurez-vous d'inclure le code barre
    dans chaque image, étant donné que les Field Papers ne fonctionnent pas sans ce code.	 
    Voici ci-dessous un exemple d'une image numérisée (ou photo) :

![Feuille de terrain numérisée](/images/scrnsht.png)

-   Une fois que vos Field Papers sont numérisés et sauvegardés sur un ordinateur,
    démarrez votre navigateur internet et retournez à la page [fieldpapers.org](http://fieldpapers.org),
    tout comme vous avez fait auparavant.
-   Cliquez sur l'onglet "Upload".

![Menu Télécharger](/images/upload.png)

-   Cliquez sur "Choose File" et allez chercher 
    la photo/le scan de vos Field Papers.


![uploadfp](/images/uploadfp.png)

-   Cliquez sur "Upload"
-   Ça peut prendre quelques minutes pour transférer votre image en fonction de 
    la rapidité de votre connexion à Internet.
    Une fois terminé, vous devriez voir quelque chose comme ça :

![Choisir un fichier](/images/asd.png)

## Ajouter le plugin Field paper

-   Avant de pouvoir ouvrir le Field Papers dans JOSM, il faut installer le 
    plugin Field Papers pour JOSM (JOSM Field Papers Plugin).

>   Les plugins ajoutent des fonctionnalités à JOSM. 
>   Le plugin Field Papers permet de charger l'image en fond d'écran, 
>   un peu comme s'il s'agissait d'une photo satéllite.

<!-- link to josm plugins section here -->
-   Ouvrez JOSM et allez dans Edit -> Preferences
-   Cliquez dans l'onglet Plugins
-   Trouvez le plugin Fieldf Papers et cochez la cas à côté. Cliquez sur OK.

![Greffon FieldPapers pour JOSM](/images/plugin.png)

-   Redémarrez JSOM.

## Ouvrir dans JOSM

-   Maintenant vous pouvez charger votre Field Paper et l'utiliser pour 
    ajouter les informations que vous avez collectées à OpenStreetMap.
    Retournez sur le site [fieldpapers.org](http://fieldpapers.org)
    dans votre navigateur web comme précédemment.
-   Cliquez sur l'onglet "Watch" puis sur "Snapshots".
-   Localisez votre numérisation dans la liste et cliquez dessus. 
    Vous devriez voir quelque chose comme :

![Pages numérisées](/images/watchsnapshot.png)

-   Pour télécharger l'image dans JOSM, vous devez copier le ID 
    correspondant à votre image sur le site de Field Paper.
    Dans la barre URL au haut de votre navigateur internet, sélectionnez le texte et saisir
    CTRL+C sur votre clavier pour copier. Le texte devrait être similaire à ceci : 
    [http://fieldpapers.org/snapshot.php?id=zqw8m33x#16/14.6582/121.1098](http://fieldpapers.org/snapshot.php?id=zqw8m33x#16/14.6582/121.1098)

![Identifiant Fieldpaper](/images/fieldpaperid.png)

-   Dans le menu du haut de JOSM, cliquez sur "Field Papers". Puis sur "Scanned Map..."

![Scanned map](/images/scannedmap.png)

-   Pressez CTRL+V sur votre clavier pour coller le texte que vous avez 
    copié sur le site Field Papers.

![Snapshot](/images/fsnapshot.png)

-   Cliquez sur OK.
-   Si tout s'est bien passé, votre Field Paper devrait s'afficher dans JOSM.
    Dans le chapitre suivant, nous allons voir comment ajouter dans OpenStreetMap
    les lieux que vous avez cartographié.

![Fieldpaper scan as a JOSM background](/images/fieldpaperjosm.png)

Vous pouvez aussi utiliser votre imagerie venant de Field Papers dans 
d'autres éditeurs de carte OSM comme les éditeurs en ligne iD et Potlatch2
en cliquant les liens "Edit in iD" ou "Edit in Potlatch"
sur la page des Field Papers numérisés.

![Edit in iD or P2](/images/editinidorpot.png)

![Snapshot layer in iD](/images/id.png)

## Répétez!

-   Après avoir ajouté vos modifications dans OSM, ils seront finalement sauvegardés
    sur la carte. De cette façon, la prochaine fois que vous voulez améliorer la carte,
    vous pouvez imprimer un nouveau Field Paper qui contiendra les changements déjà effectués.
    En répétant cette procédure, la carte deviendra de mieux en mieux, à chaque fois que vous cartographiez!

## Sommaire

Félicitations! Dans ce chapitre, vous avez appris la procédure et le mode de fonctionnement des Field Paper.
Vous avez appris comment imprimer, cartographier et numériser un Field Paper.
Dans le prochain chapitre, nous allons voir comment ajouter dans OSM les lieux  que nous avons cartographié
et vous aurez appris l'ensemble de la procédure d'édition de carte.