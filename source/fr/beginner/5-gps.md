---
layout: doc
title: Sur le terrain avec un GPS
otherguides: "Les autres niveaux"
---

Dans ce chapitre, nous allons voir ce que permet un GPS et comment il fonctionne.
Vous allez apprendre à utiliser un GPS, en particulier pour créer des cartes.
Dans ce chapitre, nous nous concentrerons sur un eTrex Vista HCx de la marque Garmin,
un modèle courant pour la cartographie.
Il existe de nombreux autres modèles de GPS avec des fonctionnalités identiques, 
donc ne craignez rien si vous en avez un autre, les principes restent les mêmes.

## Qu'est-ce qu'un GPS ?

Un GPS est similaire à un téléphone mobile, sauf qu'au lieu de recevoir des
signaux radio des compagnies de téléphone, il reçoit des signaux radio de satellites
qui tournent autour de la Terre. À partir de ces signaux, un GPS sait calculer sa
position exacte sur la planète.
Il enregistre cette position dans des coordonnées, qui sont deux grands nombres.
Le premier indique votre éloignement Est ou Ouest - c'est la longitude, en degrés.
Le second indique votre éloignement Nord ou Sud - c'est la latitude, en degrés également.
Chaque endroit de la terre a une paire de coordonnées géographiques unique.

Par exemple, -8.639298 de latitude, 116.311607 de longitude est situé à Lombok,
Indonésie.


![Le logiciel Google Earth, affichant les coordonnées de Lombok, Indonésie](/images/google-earth-lombok.png)

![Garmin eTrex Vista HCx](/images/garmin-etrex.png)

## Allumer le GPS

Avant d'allumer votre GPS, sortez à un endroit dégagé, où vous pouvez observer
le ciel facilement. Comme le GPS détermine sa position en recevant les signaux
des satellites, il fonctionne très mal en intérieur.

Sur le côté droit de votre GPS, tenez le bouton Power enfoncé. Le GPS démarre
et vous montre la page Satellites. Vous devriez voir quelque chose similaire à l'image
ci-dessous. Votre GPS cherche les signaux satellites. 
Une fois qu'il a localisé 3 satellites ou plus, il affiche sa localisation.


![Acquisition des satellites](/images/aquiring-satellites.png)

Ensuite, l'écran Satellite disparaît et le menu principal le remplace.

![Menu principal du GPS](/images/main.png)

## Les menus du GPS

-   Le GPS a des écrans et des menus différents qui vous permettent 
    d'accéder à diverses fonctionnalités. Pour changer d'écran, appuyez sur
    le bouton marqué “X”, au-dessus du bouton d'allumage, côté droit.
    Ce bouton vous permet aussi de revenir en arrière : si vous appuyez quelque part
    par erreur et que vous voulez annuler, appuyer sur le bouton “X”.
-   En appuyant plusieurs fois sur le bouton X, vous devriez pouvoir parcourir
    différents écrans, qui ressemblent à ceci :

![Tous les menus du GPS](/images/all.png)

-   Si vous retournez à la page Satellites, vous pouvez vérifier que vous êtes 
    connecté à trois satellites ou plus. Dans le coin en haut à gauche, vous voyez
    vos coordonnées, latitude et longitude.

> Pour ajouter la carte OSM dans votre GPS, téléchargez les dernières données sur [http://labs.geofabrik.de/haiti/latest.garmin-gmapsupp.zip](http://labs.geofabrik.de/haiti/latest.garmin-gmapsupp.zip).
> Dézippez “latest.garmin-gmapsupp.zip” et enregistrez le fichier “gmapsupp.img”
> dans un dossier temporaire. Allumez et connectez votre GPS à l'ordinateur, puis 
> créez un dossier "Garmin". Ensuite redémarrez le GPS, et l'extrait de carte OSM
> devrait être disponible.

-   Passez à la page Map (carte) pour voir la carte de l'endroit où vous êtes.
    Si vous avez ajouté la bonne carte OSM, vous devriez voir des routes et des
    noms de lieux, sinon la carte peut sembler assez vide. 
    Vous pouvez zoomer/dézoomer en appuyant sur les flèches haut/bas sur le côté
    gauche de l'appareil. 

## Traces et Waypoints

Votre GPS enregistre deux sortes d'informations qui sont utiles pour
créer des cartes ou conserver les coordonnées d'un lieu.
En premier lieu, il vous permet de conserver votre emplacement dans sa mémoire,
associé à un nom ou un numéro. Par exemple, votre premier point sera
numéroté 001, puis 002, etc.

> Si votre GPS ne démarre pas à 001, et que vous voulez effacer les points
> précédents, allez à l'icône "Find" du menu principal.
> Appuyez sur  “waypoints” puis sur le bouton submenu à droite de l'écran.
> Là, descendez jusqu'à  “Delete” (supprimer), cliquez sur “all symbols” 
> puis sur “Yes”.

Quand vous enregistrez un point, vous pouvez noter sur un papier à côté 
le numéro avec la description correspondante. Ces points enregistrés dans le 
GPS sont appelés des waypoints (points de route).

En second lieu, votre GPS peut enregistrer vos traces (tracks). Alors qu'un
waypoint n'enregistre qu'un emplacement isolé, une trace enregistre vos déplacements.
Par exemple, elle conserve un point toutes les secondes, ou tous les mètres,
et le résultat sera une série de points qui formera votre parcours complet.
Les traces sont utiles pour cartographier des objets représentés par des lignes
ou des surfaces, comme une route ou le contour d'un champ.

![Trace GPS](/images/google-earth.png)

## Enregistrer votre emplacement

-   Pour enregistrer votre emplacement courant dans un waypoint, cliquez sur le bouton
    “X” jusqu'à atteindre le menu principal. À l'aide du joystick, passez la surbrillance
    sur “Mark”, puis appuyez sur le joystick pour ouvrir la page “Save Waypoint”.

    ![save location 1](/images/save-location1.png)

    ![save location 2](/images/save-location2.png)

> Si vous utilisez plusieurs récepteurs GPS, assurez-vous qu'ils sont tous
> configurés dans le même format. Pour cela, allez dans le menu principal et
> ouvrez le “Set up Menu”.  Cliquez sur “Units” et choisissez les degrés décimaux
> (hddd.ddddd°), le Datum à WGS 84 (qui est une approximation standard de référence
> pour la forme de la Terre), et les autres éléments (distance, vitesse, altitude
> et profondeur) en mètres.

-   Sur cette page, vous pouvez examiner certaines informations sur le waypoint
    que vous enregistrez : d'abord son nom. Si c'est votre premier waypoint, 
    ce sera certainement “001”. Notez-le également sur votre bloc-notes, avec
    les informations supplémentaires que vous voulez. 
    En dessous, vous voyez la date et l'heure d'enregistrement, puis les coordonnées
    et l'altitude. 
-   Avec le joystick, allez sur le bouton  “OK” en bas de l'écran, et appuyez
    pour enregistrer ce point et n'oubliez pas de noter les informations
    correspondantes.
-   Appuyez sur le bouton “X” pour revenir à la carte. Vous devez maintenant
    voir votre waypoint à l'écran.


## Activer les traces

-   Maintenant, nous pouvons apprendre à activer et désactiver l'enregistrement 
    des traces. Quand il est activé, il mémorise votre déplacement.
    Prenez la bonne habitude d'activer l'enregistrement dès que vous commencez
    à cartographier, et de le désactiver à la fin : vous pourrez alors visualiser
    tout votre chemin sur l'ordinateur. Si vous voulez cartographier une route,
    pensez à enregistrer un waypoint aux deux extrémités, et à noter sur votre
    carnet les nom et type de route, et toutes ses autres caractéristiques notables.
-   Pour désactiver l'enregistrement des traces, cliquez sur le bouton “X” jusqu'à
    atteindre la page "Track log".

    ![turn on track](/images/turn-on-track.png)

-   Si vous voulez vider la mémoire des traces pour effacer les enregistrements précédents,
    sélectionnez “Clear” au joystick : la barre du haut doit retomber à 0%.
-   Pour activer l'enregistrement, sélectionnez “On”. Votre chemin est enregistré.
-   Sous l'option “Set up”, vous pouvez régler l'intervalle de temps ou de distance.
    Si vous avez une carte mémoire dans votre GPS, c'est une bonne habitude de
    régler l'intervalle à une seconde, ce qui donne la meilleure précision d'enregistrement,
    pour les cartographies de précision.
-   Appuyez sur le bouton “X” pour revenir à la carte. Vous pouvez maintenant visualiser
    votre déplacement en direct, sous la forme d'un tracé pointillé.

## Transférer les waypoints et les traces sur son ordinateur

### Connecter le GPS à l'ordinateur

-   Quand vous avez fini de cartographier au GPS, vous avez besoin de transférer
    les points et traces enregistrés dans votre ordinateur pour les ouvrir avec JOSM.
    Commencez par arrêter l'enregistrement des traces, si ce n'est pas déjà fait,
    en allant sur la page de traces et en sélectionnant “Off”. 
-   Reliez le GPS à l'ordinateur avec son câble. Une extrémité doit être reliée
    à un port USB de votre ordinateur, et l'autre à l'arrière du GPS, sous le 
    capuchon de caoutchouc en haut. Le GPS doit être allumé pour copier les points
    et les traces.

### Installer les pilotes du GPS

-   Vous devrez peut-être installer les pilotes GPS sur votre ordinateur.
    Si vous avez une copie de USBDrivers\_23.exe sur votre machine, double-cliquez
    dessus pour l'installer.
-   Si vous n'avez pas ce fichier, vous pouvez le télécharger. Ouvrez votre
    navigateur internet, et allez sur
    [http://www8.garmin.com/support/download\_details.jsp?id=591](http://www8.garmin.com/support/download_details.jsp?id=591)
-   Cliquez sur “Download” pour récupérer le fichier d'installation, puis 
    trouvez-le sur votre ordinateur et double-cliquez pour l'installer.

### Récupérer le programme de configuration GPSBabel
-   GPSBabel est un programme qui vous permet de copier des données depuis le GPS.
    Si vous en avez une copie sur CD ou clé usb, vous pouvez passer à la section suivante.
-   Si vous ne l'avez pas encore, ouvrez votre navigateur à la page 
    [www.gpsbabel.org](http://www.gpsbabel.org)
-   Cliquez sur “Downloads” en haut de page.
-   Parcourez la page. Si vous utilisez Windows, vous aurez besoin du fichier d'installation
    pour ce système. Cliquez sur “GPSBabel-1.4.2-Setup.exe” pour commencer le téléchargement.

### Install GPSBabel
-   Trouvez le fichier de GPSBabel sur votre machine, et double-cliquez pour l'installer.
-   Appuyez sur “Next”. 
-   Cliquez sur “I accept” puis sur “Next”. 
-   Continuez de cliquer sur “Next” jusqu'à la fin de l'installation.
-   Enfin, cliquez sur “Finish” pour démarrer GPSBabel.

    ![turn on track](/images/turn-on-track.png)


### Copier les traces et les waypoints

-   Cliquez sur le cercle à côté du mot “Device” en haut de la fenêtre.
-   Dans le menu déroulant “Format”, sélectionnez “Garmin serial/USB protocol”
-   Descendez au milieu de la fenêtre, sous Output. Dans le menu déroulant intitulé
    “Format”, sélectionnez “GPX XML”:

    ![Choose GPX XML](/images/xml.png)


-   Cliquez sur “File Name” et tapez un nom pour enregistrer votre fichier.
    Choisissez-le assez parlant, avec la date et le lieu concerné, par exemple
    _2011-07-07-Jakarta_
-   Assurez-vous que votre GPS est bien relié à l'ordinateur et allumé.
-   Cliquez sur “Apply” dans le coin bas-droite de la fenêtre.
-   Si tout va bien, vous devez voir une barre s'animer sur l'écran, indiquant
    que les données sont en cours de transfert depuis le GPS. À la fin, vos points
    et vos traces sont enregistrées dans le fichier que vous avez défini.

### Ouvrir les données dans JOSM

-   Maintenant, ouvrez JOSM. Dans le menu du haut, cliquez sur “Fichier” puis “Ouvrir…”
-   Sélectionnez le fichier que vous venez de créer avec GPSBabel, puis cliquez sur “Ouvrir”.
-   Vous devriez maintenat voir vos points et vos traces chargées dans une couche de JOSM.

    ![GPS Files Open in JOSM](/images/open-josm.png)

## Résumé

Félicitations ! Vous devriez maintenant avoir compris l'utilisation du GPS.
Si vous n'avez pas encore pratiqué, allez sur le terrain, enregistrer des points 
sur des lieux importants.
Dans ce chapitre, vous avez appris à ouvrir vos traces et vos points dans JOSM.
Dans le chapitre 6, nous allons utiliser cette information pour ajouter de
nouveaux lieux dans OpenStreetMap. Dans le chapitre suivant, nous allons étudier
les Walking Papers, qui est une autre façon de collecter des données sur le terrain.
Avec Walking Papers, vous n'avez besoin de rien d'autre qu'un papier et un crayon.

[Google Earth software, showing coordinates of Lombok, Indonesia]: {{site.baseurl}}/images/gps_lombok_map_en.png
[Garmin eTrex Vista HCx]: {{site.baseurl}}/images/gps_garmin_etrex_en.png
[GPS determined location]: {{site.baseurl}}/images/gps_aquiring_satellites_en.png
[GPS main menu]: {{site.baseurl}}/images/gps_main_en.png
[GPS all]: {{site.baseurl}}/images/gps_all_en.png
[GPS path]: {{site.baseurl}}/images/gps_google_earth_en.png
[save location 1]: {{site.baseurl}}/images/gps_save_location1_en.png
[save location 2]: {{site.baseurl}}/images/gps_save_location2_en.png
[turn on track]: {{site.baseurl}}/images/gps_turn_on_track_en.png
[GPSBabel Interface]: {{site.baseurl}}/images/gps_babel_en.png
[Choose GPX XML]: {{site.baseurl}}/images/gps_xml_en.png
[GPS Files Open in JOSM]: {{site.baseurl}}/images/gps_open_josm_en.png
