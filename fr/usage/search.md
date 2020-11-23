---
description: Utiliser le moteur de recherche de données Isogeo dans ArcGIS Pro
---

# Rechercher

Le moteur de recherche Isogeo dans ArcGIS Pro se base sur des filtres contextuels. L'utilisateur peut utiliser ces différents filtres pour resserrer le nombre de résultats qui s'affichant automatiquement sous la forme d'une liste.

![Interface de recherche du plugin - Recherche filtrée sur un mot-clé](../../assets/plugin_ArcGISPro_search_tab_filtered_FR.png)

De là il peut alors [consulter la métadonnée](/usage/metadata.md) ou [ajouter la donnée à sa carte](/usage/display.md).

## Recherche sémantique {#search-terms}

La recherche textuelle s'effectue dans la barre de saisie de texte en haut de la fenêtre du plugin.

Les termes saisis sont recherchés au sein :

* du titre de la fiche de métadonnées
* du nom du fichier
* de son résumé
* de ses mots-clés
* de ses thèmes INSPIRE

Pour en savoir plus sur le fonctionnement du moteur de recherche Isogeo, [consulter l'aide en ligne](https://help.isogeo.com/fr/features/inventory/search.html).

## Filtres contextuels {#filters}

### Filtre par mot-clé {#keywords}

Pour filtrer sur un mot-clé, sélectionner dans la liste déroulante dédiée.

![Filtre par mot-clé](../../assets/plugin_ArcGISPro_search_options_keywords_FR.png)

### Autres filtres

Tous les autres filtres sémantiques fonctionnent de la même manière \(sélection d'une modalité dans une liste déroulante\).

Tous les filtres sont inter-dépendants \(contextuels\). Ainsi l'application d'un filtre fait évoluer les modalités disponibles dans toutes les listes déroulantes et le nombre de résultats correspondant.

### Filtre géographique {#geometric}

Il est également possible de filtrer les résultats à partir de l'emprise de la carte.

![Filtre à partir de la carte](../../assets/plugin_ArcGISPro_search_options_geographic_FR.png)

Par défaut, le filtre géographique remonte toute les données qui **intersectent** l'emprise considérée. Pour changer ce comportement, aller dans l'onglet "Paramètres", choisir un opérateur différent, puis relancer la recherche.

![Paramétrer l&apos;opérateur géométrique pour le filtre géographique](../../assets/plugin_ArcGISPro_settings_geographic_FR.png)

---

## Afficher les résultats {#display}

Lors de la saisie de texte dans la barre de recherche et de l'action sur un filtre sémantique, le contenu des autres filtres se met à jour, et le nombre de résultats attendus s'affiche dans un bouton situé au dessus de la zone d'affichage des résultats.

> À l'ouverture du plugin, appuyer sur ce bouton permet d'afficher les résultats si aucun filre n'a encore été utilisé.

![Nombre de résultats sur le bouton pour les afficher](../../assets/plugin_ArcGISPro_search_results_show_FR.png)

À chaque recherche, les résultats de la recherche sont affichés dans le tableau, paginés de manière à n'afficher autant de résultats que la hauteur de la fenêtre le permet.

Pour chaque résultat, on trouve :

* le titre affecté à la fiche de métadonnée, au survol duquel s'affiche le résumé
* un label indiquant le type de donnée
* les modalités d'ajout disponibles pour cette donnée

Deux boutons et une liste déroulante sont consacrés à la navigation entre les différentes pages de résultats en bas du tableau :

![Pagination des résultats](../../assets/plugin_ArcGISPro_search_results_pagination_FR.png)

### Trier les résultats {#order}

Une fois affichés, les résultats peuvent être triés via les deux listes déroulantes situées au dessus de la zone d'affichage des résultats.

Le tri par défaut est **le score de pertinence** (voir [ici pour le détail du calcul du score](https://help.isogeo.com/fr/features/inventory/search.html#pertinence-)). Il s'agit du tri recommandé lors de recherches textuelles.

Lorsqu'aucun texte n'est saisi dans la barre de recherche, le score de pertinence étant nul pour tous les résultats c'est alors le tri décroissant par date de création de la fiche de métadonnée qui est appliqué par défaut.

Les autres tris disponibles sont :

* Ordre alphabétique
* Date de création de la métadonnée
* Date de dernière modification de la métadonnée
* Date de création de la donnée
* Date de dernière modification de la donnée

![Critères de tri](../../assets/plugin_ArcGISPro_sort_criteria_FR.png)

L'ordre du tri peut également être spécifié :

* Ascendant
* Descendant

![Ordre de tri](../../assets/plugin_ArcGISPro_sort_order_FR.png)

---

## Réinitialiser la recherche {#search-reset}

A tout moment, il est possible de réinitialiser le formulaire de recherche en cliquant sur l'icône à côté du bouton d'affichage des résultats.

![Bouton de réinitialisation de la recherche](../../assets/plugin_ArcGISPro_search_reset_button_FR.png)

---

## Cas particuliers

### Aucun résultat ne s'affiche {#no-results}

Si aucun résultat ne s'affiche, cela peut être provoqué par une erreur technique liée à la non prise en charge par ArcGIS Pro des emprises multiples dans un JSON (format de communication de l'API).

Exemple d'une emprise multiple provoquant cette erreur :

![Emprises multiples non prises en charge](../../assets/plugin_ArcMap_error_geojson_multipolygon.png)
