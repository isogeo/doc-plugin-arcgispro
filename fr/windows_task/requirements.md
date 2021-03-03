# Pré-requis

Afin de pouvoir mettre en place la mise à jour automatique sur les postes, les prérequis suivant sont à respecter : 

* Accès de chaque utilisateur à un dossier (oneDrive, dossier sur le serveur) a minima en lecture sans condition d'accès
* Accès à ce dossier en écriture pour un administrateur
* Serveur ou poste avec droit administrateur Windows supportant le planificateur de tâche est muni d'une version de PowerShell supérieure ou égale à Powershell 2

## Windows supportant le planificateur de tâches

Les versions suivantes supportent le planificateur de tâche :

* Windows 10
* Windows 7
* Windows Server 2008 R2
* Windows Vista
* Windows Server 2008
* Windows Server 2003
* Windows Server 2019
* Windows XP
* Windows 2000

## Vérifier sa version de Powershell

Il est notamment possible de retrouver la version de Powershell en ouvrant un terminal Powershell et taper la commande suivante : 

```shell
Get-Host | Select-Object Version
```