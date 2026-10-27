# Afri Media Express

Exportez vos médias en plus léger.

Creative tools by Robin Kapka

Ce dépôt héberge les fichiers de distribution et les mises à jour Firefox. Les sources de travail sont conservées dans un dépôt privé. L’extension est distribuée en mode non répertorié sur Mozilla : elle n’apparaît pas dans la boutique.

## Installation Firefox

La première version signée est en préparation. Aucun ZIP non signé ne doit être utilisé pour une installation permanente.

Une fois la version disponible dans Releases, téléchargez `afri-media-express-firefox.xpi`. Dans Firefox, ouvrez `about:addons`, puis le menu roue dentée → Installer un module depuis un fichier. Sélectionnez le XPI signé et confirmez les autorisations. L’installation reste disponible après redémarrage, sans débogueur.

## Mises à jour

Firefox consulte automatiquement [le manifeste de mise à jour](https://raw.githubusercontent.com/afriction/afri-media-express-updates/main/firefox/updates.json). Les versions proposées doivent être signées par Mozilla ; chaque entrée comporte une empreinte SHA-256 du fichier signé. Le manifeste reste vide tant que la première signature n’est pas disponible.

Aucun jeton GitHub n’est intégré à l’extension. Les fichiers de ce dépôt sont publics et accessibles sans compte GitHub.

[Confidentialité](PRIVACY.md)
