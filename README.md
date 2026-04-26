# AuraPOS-Releases
Logiciel de caisse pour la Belgique.


## Telechargement

La derniere version est disponible dans la section [Releases](../../releases/latest).

Telechargez l'installeur `AuraPOSSetup-X.Y.Z-beta.exe` puis lancez-le. L'installation
detecte automatiquement les prerequis (.NET 10 Desktop Runtime) et propose
l'installation de PostgreSQL Server pour le mode multi-poste.

## Mises a jour automatiques

AuraPOS verifie au demarrage si une nouvelle version est disponible sur ce repo
(via l'API GitHub Releases). Lorsqu'une mise a jour est trouvee, l'application
propose d'ouvrir la page de telechargement.

Tu peux aussi declencher la verification manuellement depuis :
**Parametres > Licence > Verifier les mises a jour**.

## A propos de ce repo

Ce repo contient uniquement les **binaires** (installeurs `.exe`) publies sous
forme de Releases GitHub. Le code source d'AuraPOS reste prive.

## Notes de version

Voir la description de chaque [Release](../../releases) ou le fichier
`CHANGELOG.txt` inclus avec l'application installee.
