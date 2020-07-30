---
description: Désinstaller le plugin Isogeo pour ArcGIS Pro
---

# Désinstallation

Voici les étapes à suivre pour désinstaller correctement le plugin.

1. Ouvrir ArcGIS Pro
2. Aller dans "Projet"
3. Sélectionner "Compléments"
4. Sélectionner "Isogeo Add-In"
5. Cliquer sur le bouton en bas à droite "Supprimer ce complément"
6. Le message "Ce complément a été supprimé" s'affiche en rouge
7. La suppression sera prise en compte après redémarrage d'ArcGIS Pro

!["Supprimer le plugin ArcGIS Pro"](/assets/delete_plugin_arcgis_pro.png)

Pour supprimer toutes les données utilisateurs enregistrées par le plugin, il faut supprimer le fichier *AddInConfiguration.json* dans le répertoire `C:\Users\%USERPROFILE%\Documents\Isogeo\ArcGisPro\`