# Notes de versions

<!-- timeline -->

## 0.8.0

* Correction du design des sections “paramètres de proxy” et “paramètres de recherche”
* Modification de la fonctionnalité “recherche rapide” pour y ajouter le chargement de l’étendue de la carte
* Ajout du “Box” à l’intérieur des paramètres des recherches rapides sauvegardées, nécessaire pour définir l’étendue de la carte actuelle.
* Optimisation des dépendances Esri ArcGis Pro SDK du plugin
* Suppression des dépendances non utilisées
* Correction du bug "géométrie inconnue" affiché au lieu de "service" dans certains cas sur les résultats de recherche
* Correction de l'affichage de l’icône Isogeo dans la section Manager d’Add-Ins
* Refonte d’une partie du système de gestion de configuration (sauvegarde)
* Notamment utilisation d’un fichier fichier au format JSON pour sauvegarder les données utilisateurs
* Correction du bug flèche droite de navigation qui n’actualise pas les résultats dans certains cas
* Correction de la section “paramètres de proxy”
* Corrections de traductions Français/Anglais
* Nettoyage du code

<!-- /timeline -->
<!-- timeline -->

## 0.7.3

* Corrections d’erreurs de traduction Anglais / Français du plugin
* Ajout de l’opérateur géographique à l’intérieur de la fonctionnalité “recherche rapide”
* Amélioration de la fonctionnalité “recherche précédente”
* Nettoyage du code

<!-- /timeline -->
<!-- timeline -->

## 0.7.2

* Correction du bug de l'affichage de la fenêtre Metadata remplie de "NR" par moment
* Modification des éléments de design nécessitant une remise à niveau
* Corrections d'erreurs de disposition du visuel

<!-- /timeline -->
<!-- timeline -->

## 0.7.1

* Correction de la fonctionnalité "opérateur géographique"
* Correction d'une erreur sur le bouton "réinitialiser"
  * l'opérateur géographique n'était pas réinitialisé
* Correction de l'initialisation de l'opérateur géographique
  * la valeur par défaut sauvegardée n'était pas appliquée au démarrage

<!-- /timeline -->
<!-- timeline -->

## 0.7.0

* Ajout de la fonctionnalité "opérateur géographique"
* Nettoyage du code
* Ajout de logs
* Restructuration de quelques éléments du projet
* Correction d'un bug de chargement du plugin au démarrage

<!-- /timeline -->
<!-- timeline -->

## 0.6.0

* Finalisation du Manager de logs
* Ajout d'un bouton pour l'accès au fichier logs généré par le Manager de logs
* Amélioration du support des formats EFS et EMS
* Amélioration du support des formats SDE et GDB
* Amélioration du support du format SHP
* Restructuration du projet en sous-projets (Addin, language, models, resources, utils, mvvmpatern)
* Nettoyage du code

<!-- /timeline -->
<!-- timeline -->

## 0.5.0

* Préparation du module "Manager de logs"
* Ajout de logs
* Ajout d'un bouton d'accès aux logs depuis le plugin
* Ajout du support des formats "SDE, FileGDB, SHP" à la fonctionnalité "Ajouter une couche à la carte"
* Nettoyage de code
* Modifications légères d'éléments de design

<!-- /timeline -->
<!-- timeline -->

## 0.4.1

* Correction d'un bug apparu à la version 0.4
  * l'offset des recherches était toujours de valeur 0.
* Passage de la section “paramètres de proxy” en architecture MVVM, permettant aux champs utilisateurs de rester complétés quand on passe sur l’onglet “recherche” pour ensuite revenir sur l’onglet “paramètres”
* Ajout de l’apparition de pop-ups pour savoir si les identifiants ont été sauvegardés dans la section “paramètres de proxy”

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

* Ajout des fonctionnalités de tri (asc/desc - relevance,métadonnée créée etc.)
* Préparation du terrain dans le code pour l'ajout de la fonctionnalité "options par défaut" (dans la section paramètres du plugin)
* Modification du bouton "réinitialiser" pour réinitialiser également les paramètres de tri par les valeurs par défaut
* Amélioration de la sélection d’un résultat dans la liste des résultats (clic accepté partout sur l'élément)
* Correction de l'affichage de l'ui de la fenêtre Métadonnées pour le thème light (clair)
* Correction d'éléments incorrects sur l'affichage des données dans la fenêtre Métadonnée
* Ajout de sécurités dans le code pour éviter des générations d'erreurs suite à d’éventuelles futures modifications du code
* Modifications légères d'éléments de design

<!-- /timeline -->
<!-- timeline -->

## 0.2

* Refonte de la fonctionnalité “recherche avancée” pour reproduire le comportement des plugins Isogeo ArcMap et Isogeo QGis
* Correctif / amélioration du bouton “réinitialiser”

<!-- /timeline -->
<!-- timeline -->

## 0.1

* Refonte de la partie réseau du plugin
* Corrections de bon nombre de bugs liés au portage de la partie réseau du plugin Isogeo ArcMap vers Isogeo ArcGis Pro
* Modifications mineures apportées sur le plugin

<!-- /timeline -->
<!-- timeline -->

## 0.0.1

* Première livraison du plugin Isogeo ArcGis Pro de Vianney Doleans envoyée à l'équipe Isogeo
  * Plugin ArcGis Pro en version “light” (principales fonctionnalités)
* Plugin disponible en thème light (clair) et dark (foncé)
  * Développement / design : possibilité de changer le pack de couleurs
* Envoi de la documentation d'installation du plugin à l’équipe Isogeo

<!-- /timeline -->