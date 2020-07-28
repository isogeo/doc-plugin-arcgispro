# Ajouter une donnée à la carte

Pour ajouter une donnée à la carte, la troisième colonne \(dite "Ajouter"\) liste les options possibles.

Il y a plusieurs cas de figure :

* La donnée peut être ajoutée d'une seule manière. Auquel cas, la colonne "Ajouter" ne comprend qu'un bouton. Au clic sur le bouton `+`, la donnée sera ajoutée à la carte.

![](../../assets/plugin_ArcMap_search_results_addOk_one_FR.png "Donn&eacute;e ajoutable d&apos;une seule mani&egrave;re")

* La donnée peut être ajoutée de plusieurs manières différentes. Auquel cas, la colonne "Ajouter" comprend une liste déroulante permettant à l'utilisateur de choisir entre les différentes options avant de cliquer sur `+` :

![](../../assets/plugin_ArcMap_search_results_addOk_multi_FR.png "Donn&eacute;e ajoutable de plusieurs mani&egrave;res")

---

## Critères

### Données fichier {#add-file}

Le chemin vers la donnée doit être rempli dans le champ `Emplacement de la donnée` sur [https://app.isogeo.com](https://app.isogeo.com). Ce chemin doit être accessible :

* par l'utilisateur ayant lancé ArcGIS \(droits en lecture\);
* depuis le poste sur lequel le plugin se trouve \(en local ou via le réseau local\).

Formats :

* Esri FileGDB
* Esri Shapefile

### Données SDE {#add-sde}

Une table SDE pourra être ajoutée par le plugin dans les conditions suivantes :

* L'utilisateur a renseigné le fichier de connexion SDE à utiliser dans l'onglet `Paramètres`. Un seul fichier de connexion SDE est configurable.
* La fiche documentant la table a été créée à partir du scan FME Isogeo. En créant une fiche manuellement dans [https://app.isogeo.com](https://app.isogeo.com), il est impossible de renseigner le champ _name_ nécessaire à l’ajout de la table.

![](../../assets/plugin_ArcMap_settings_SDE_FR.png "Pointer sur le fichier de connexion SDE")

### Services géographiques {#add-service}

Le plugin supporte les couches de services documentés automatiquement et associées aux métadonnées de données :

* Web Feature Service \(WFS\)
* Web Map Service \(WMS\)
* Web Map Tile Service \(WMTS\)
* Esri Feature Service \(EFS\)
* Esri Map Service \(EMS\)

Consulter [l'aide en ligne Isogeo au sujet du recensement automatisé des services et de l'association couche de service / donnée cataloguée](http://help.isogeo.com/fr/features/inventory/md_services/srv_intro.html).

#### Cas particuliers

##### Accès au serveur géographique {#srv-403}

A l'ajout d'un service, la fenêtre d'erreur suivante peut s'afficher :

![](../../assets/plugin_ArcMap_error_srv_403.jpg "Erreur d&apos;acc&egrave;s au serveur g&eacute;ographique")

Pour qu'ArcGIS puisse accéder aux données via un service géographique, il est nécessaire que l'URL racine du serveur géographique soit pleinement accessible en lecture.

Par exemple, si les services à ajouter sont sur une URL du type : https://sig.monorganisme.fr/arcgis/rest/services/ISOGEO, alors l'URL racine du serveur géographique doit également être accessible en lecture : https://sig.monorganisme.fr/arcgis/rest/services.
