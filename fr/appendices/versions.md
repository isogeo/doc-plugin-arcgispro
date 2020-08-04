# Notes de versions

<!-- timeline -->

## 0.8.0

* Fix design Proxy & search settings
* Modification quick search to set extent map
* Add box inside quick search saved
* Fix Esri dependencies
* Fix Bug "unknown geometry" instead of "service" by moment
* Fix Isogeo Icon inside Add-In Manager
* Removed unused dependencies
* Change configuration system (JSON file instead of App.Config)
* Fix bug right arrow not refreshing the results
* Fix proxy Settings
* Fix translation
* Clean code

<!-- /timeline -->
<!-- timeline -->

## 0.7.3

* Fix translation errors
* Add geographical operator inside quick search feature
* Improvement last search feature
* clean code

<!-- /timeline -->
<!-- timeline -->

## 0.7.2

* Correction du bug de l'affichage de la fenêtre Metadata remplie de "NR" par moment
* Modification des éléments de design nécessitant une remise à niveau
* Corrections d'erreurs de disposition du visuel

<!-- /timeline -->
<!-- timeline -->

## 0.7.1

* Correction de la fonctionnalité opérateur géographique
* Correction d'une erreur sur le reset bouton l'opérateur géographique n'était pas réinitialisé
* Correction de l'initialisation de l'opérateur géographique la valeur par défaut sauvegardée n'était pas appliquée au démarrage

<!-- /timeline -->
<!-- timeline -->

## 0.7.0

* Ajout de l'opérateur géographique
* Clean de code
* Ajout de logs
* Restructuration de quelques éléments du projet
* Correction d'un bug de chargement du plugin au démarrage
* Support de windows Server

<!-- /timeline -->
<!-- timeline -->

## 0.6.0

* Développement du log Manager
* Ajout d'un bouton pour l'accès au fichier log
* Amélioration du support des formats EFS et EMS
* Ajout du support aux formats SDE et GDB
* Ajout du support SHP
* Restructuration du projet en sous projets (Addin, language, models, resources, utils, mvvmpatern)
* Clean du code

<!-- /timeline -->
<!-- timeline -->

## 0.5.0

* Ajout de la fonctionnalité "Log Manager"
* Ajout de logs
* Ajout d'un bouton d'accès des logs depuis le plugin
* Ajout du support des formats "ArcSDE, FileGDB, SHP" à la fonctionnalité "Ajouter une couche à la carte"
* Nettoyage de code
* Modifications légères d'éléments de design

<!-- /timeline -->
<!-- timeline -->

## 0.4.1

* Correction d'un bug apparu à la version 0.4 l'offset des recherches était toujours de valeur 0.
* Passage de proxy settings en MVVM, permettant aux champs utilisateur et url de proxy de rester affichés quand on passe sur recherche pour ensuite revenir sur settings (le mot de passe n'est pas conservé si non enregistré durant le processus par mesure de sécurité)
* Ajout de pop-Ups pour proxy settings pour savoir si les identifiants ont été sauvegardé

<!-- /timeline -->
<!-- timeline -->

## 0.4

* Ajout de la fonctionnalité "Recherche rapide"
* Ajout de la fonctionnalité "Recherche précédente"
* Ajout de la fonctionnalité "Paramètres de recherche"
* Ajout de la fonctionnalité "Recherche par défaut"
* Améliorations importantes du fonctionnement interne du plugin
* Corrections de failles internes du plugin
* Clean important du code du plugin
* Modifications légères d'éléments de design

<!-- /timeline -->
<!-- timeline -->

## 0.3

* Ajout des fonctionnalités de tri (asc/desc - relevance,métadonnée créée etc)
* Préparation du terrain dans le code pour l'ajout de la feature "options par défaut" (dans la section setting)
* Modification du bouton reset pour réinitialiser également les paramètres de tri par les valeurs par défaut
* Amélioration de la sélection de la metadata (click accepté partout sur l'item)
* Correction de l'affichage de l'ui de la fenêtre Metadata pour le thème light
* Correction d'éléments incorrects sur l'affichage des données dans la fenêtre Metadata
* Ajout de sécurités dans le code pour éviter de futures générations d'erreurs
* Modifications légères d'éléments de design

<!-- /timeline -->
<!-- timeline -->

## 0.2

* Rework de la Recherche avancée pour reproduire le comportement ArcMap et QGis
* Correctif du bouton Reset
* Ajout d'un fond transparent au bouton Reset

<!-- /timeline -->
<!-- timeline -->

## 0.1

* Rework de la partie réseau du plugin
* Corrections de bon nombre de bugs liées au portage de la partie réseau du plugin ArcMap
* Modifications mineurs

<!-- /timeline -->
<!-- timeline -->

## 0.0.1

* Première publication envoyée à l'équipe Isogeo, plugin ArcGis Pro en version light
* Documentation d'installation du plugin dans la publication

<!-- /timeline -->