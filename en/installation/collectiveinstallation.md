# Collective installation

## Requirements

The following requirements must be met : 

* Read access made available to each user on a specific folder (oneDrive, folder on the server) without any access conditions
* Write access for the admin on this folder

## Admin configuration

### Initialisation 

Place the plugin Addin `Isogeo.AddIn.esriAddinX` in the shared folder. 

### Update

When a update happens, simply replace the Addin file `Isogeo.AddIn.esriAddinX` with the new file. The plugin will be automatically updated on each Arcgis Pro with the correct configuration.  

## User config

To use the collective update, each user must :

* Open ArcgisPro
* Go to `Project` > `Add-in Manager` > `Options` et add a new folder (the path given by the admin) et check `Load all Add-INs without restrictions (Least Secure)`

!["Sélectionner dossier"](../../assets/ArcGisPro_set_plugin.PNG)

* Close ArcgisPro
* The addin will be added when Arcgis Pro is used again. 

