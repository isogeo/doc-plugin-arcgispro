# Installation standard

Installation classique pour les utilisateurs non administrateurs de leur poste.

## Pas à pas {#install-steps}

La procédure se déroule en 2 grandes étapes : installer le plugin puis l'ajouter à l'interface.

### I. Installer le plugin {#installation}

1. Dézipper la nouvelle version dans un dossier dédié. Pour être cohérent avec le fonctionnement d'ArcGIS, nous recommandons d'utiliser le dossier des _AddIns_ dans `Mes Documents` : `C:\Users\$USER\Documents\ArcGIS\AddIns\Desktop10.X\Isogeo` \(noter le X à remplacer selon votre version\)

2. Double-cliquer sur **ArcMapAddinIsogeo.esriAddIn** :

   ![](../../assets/plugin_ArcMap_install_esriaddin.png "Fichier .esriAddIn")

3. La fenêtre suivante s'ouvre :

   ![](../../assets/plugin_ArcMap_install_confirm.png "Assistant d&apos;installation du plugin")

4. Valider en cliquant sur **Install Add-In**. Une petite boîte de dialogue confirme que l'installation a réussi : "_Installation succeeded_".

Le plugin est désormais référencé dans les compléments d'ArcMap. Il s'agit maintenant de l'ajouter à l'interface de travail d'ArcMap.

---

### II.Ajouter le plugin à l'interface {#add-to-ui}

1. Lancer ArcMap
2. Ouvrir le menu **Personnaliser / Gestionnaire de compléments**

   ![](../../assets/plugin_ArcMap_install_custom_addins_menu_FR.png "Gestionnaire de compléments - Menu")

3. Dans la section "Mes compléments", le plugin apparaît :

   ![](../../assets/plugin_ArcMap_install_custom_addins_windows_FR.png "Gestionnaire de compléments - Liste")

4. Cliquer sur **"Personnaliser..."** \(ou faire menu _Personnaliser / Mode personnalisation_\). Deux options d'ajout sont alors possibles, selon les habitudes de chacun :

   * Ajouter une barre d'outils dédiée au plugin Isogeo
   * Ajouter l'icône du plugin Isogeo à une barre d'outils existante

#### II.a Ajouter l'icône à une barre d'outils existante {#add-command-icon}

1. Aller dans l'onglet **Commandes**, attendre le chargement de la liste des catégories \(parfois long\) et sélectionner **Add-In Controls** :

   ![](../../assets/plugin_ArcMap_install_custom_commands_FR.png "Personnalisation - Onglet Commandes - Catégorie Add-In Controls")

2. Glisser-déposer l'icône Isogeo dans une barre d'outils :

   ![](../../assets/plugin_ArcMap_install_custom_commands_dragNdrop.gif "Glisser-déposer l&apos;icône du plugin Isogeo dans une barre d\&apos;outils existante")

#### II.b Ajouter une barre d'outils dédiée {#add-command-toolbar}

1. Dans l'onglet **Barre d'outils**, descendre dans la liste et cocher Isogeo
2. Glisser-déposer la barre d'outils apparue à sa convenance :

   ![](../../assets/plugin_ArcMap_install_custom_toolbar_dragNdrop.gif "Glisser-déposer la barre d&apos;òutils dédiée au plugin Isogeo")

> Astuce : il est également possible de faire un clic-droit, dans une barre d'outils existante, de cocher Isogeo, puis de placer la barre de la même manière :
>
> ![](../../assets/plugin_ArcMap_install_custom_toolbar_clic.png "Personnalisation - Barre d&apos;outils - Clic droit")



