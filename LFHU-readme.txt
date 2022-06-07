La scène de l'altiport de l'Alpe d'Huez (LFHU)

Cette scène est construite par ajout d'un patch sur l'aérodrome générique de Fg.
Elle est adaptée sur la scène France Améliorée d'Elmaxo, "custom-scenery-france-v1" 
Un lien vers ce fichier : 
http://fr.flightgear.tuxfamily.org/forum/viewtopic.php?id=901

Elle est utilisable sur la scène par défaut de fg  mais avec quelques raccords inésthetiques du paysage. 

Pour en profiter pleinement une adaptation du fichier "apt.dat" est nécessaire:

1- Décompressez le fichier $FG_DATA/Airports/apt.dat.gz avec un logiciel tel que 7Zip ou Winrar
2- Ouvrez le fichier décompressé nommé apt.dat avec un éditeur de texte tel que Notepad++
3- Recherchez et remplacez les lignes concernant LFHU par les lignes suivantes :

1  6289 1 0 LFHU  L Alpe d Huez
10  45.089993  006.088231 24x 238.01  1582 0000.0000 0000.0000  131 121121  2 0 2 0.25 0 0300.0300
14  45.089776  006.086760 7.3 0 LFHU Tower
51 12060 ALPE DHUEZ MULT

4- Enregistrez puis fermez le fichier apt.dat
5- Recompressez le fichier apt.dat au format "gz"

Pour installer la scène :

 Copiez les dossiers Airports, Models et Objects dans votre dossier Scenery

Les fichiers concernant la scène amélioré de LFHU sont :
- Airports/L/F/H/LFHU.groundnet.xml
  contient les positions de parking disponibles	
- Models/LFHU/...
  modèles 3d et textures
- Objects/e000n40/e006n45/3056064.stg
  positionnement des objets