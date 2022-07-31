# Créer l'intégration et le déploiement continue (CI/CD) avec Azure DevOps

## Tour d'horizon

Ce répertoire contient les sources pour les vidéos de la série: [Créer l'intégration et le déploiement continue (CI/CD) avec Azure DevOps](https://www.youtube.com/playlist?list=PL9d0U43jdN_7g0alwZ1wOEMYEvsTft3_7)

Le but de cette série est de montrer le fonctionnement d'Azure DevOps avec les pipelines YAML. Les principes exposés dans les vidéos sont applicables quelque soit la technologie utilisée.

## Code source

Le projet `Demo.Maui.DevOps` est un simple `Hello World`. Vous pouvez reproduire les même concepts avec d'autres technogies. Ce projet n'a pour but que de servir de support aux vidéos afin d'y montrer différents bonnes pratiques et mécanismes élémentaires.

Chaque vidéo peut être prise indépendamment. Il suffit de reprendre le code source du dossier `Demo.Maui.DevOps` et d'y ajouter les fichiers correspondants à la vidéo précédente du dossier `Pipelines`.

## Certificat Keystore

Le certificat sandbox_keystore.jks de **démonstration** est disponible dans les sources. Les mots de passes associés sont:

- `keystore.password` => P@ssWord1
- `key.alias` =>  sandbox_keystore_alias
- `key.password` => P@ssWord1

