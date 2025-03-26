<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# OpenCloud pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/opencloud)](https://ci-apps.yunohost.org/ci/apps/opencloud/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/opencloud)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/opencloud)

[![Installer OpenCloud avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opencloud)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer OpenCloud rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

OpenCloud est la nouvelle plateforme de synchronisation et de partage de fichiers qui constituera la base de votre plateforme de gestion de données.

### Caractéristiques

- Interface utilisateur rapide, simple et propre
- Raccourcis clavier pour une sélection rapide des fichiers
- Prise en charge du glisser-déposer
- Recherche puissante par nom, texte intégral, OCR, type de fichier, date ou étiquette
- Synchronisation de fichiers fiable et tolérante aux pannes
- Options de partage flexibles
- Partage de fichiers avec des liens publics
- Espaces de travail : Dossiers de projet dédiés conçus pour simplifier la collaboration au sein de l'équipe
- Intégrations avec des outils tels que Markdown Editor (ToastUI) et Web Office (Collabora)
- Historique des fichiers pour suivre les modifications et restaurer les versions précédentes
- Synchronisation multi-appareils avec accès hors ligne sur tous vos appareils


**Version incluse :** 2.0.0~ynh2

## Captures d’écran

![Capture d’écran de OpenCloud](./doc/screenshots/screenshot.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://opencloud.eu/en>
- Dépôt de code officiel de l’app : <https://github.com/opencloud-eu/opencloud>
- YunoHost Store : <https://apps.yunohost.org/app/opencloud>
- Signaler un bug : <https://github.com/YunoHost-Apps/opencloud_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/opencloud_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opencloud_ynh/tree/testing --debug
ou
sudo yunohost app upgrade opencloud -u https://github.com/YunoHost-Apps/opencloud_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
