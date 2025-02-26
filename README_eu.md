<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ownCloud YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/owncloud)](https://ci-apps.yunohost.org/ci/apps/owncloud/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/owncloud)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/owncloud)

[![Instalatu ownCloud YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=owncloud)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ownCloud YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

ownCloud Infinite Scale (oCIS) is the new file sync & share platform that will be the foundation of your data management platform.

**Paketatutako bertsioa:** 7.1.0~ynh1

**Demoa:** <https://ocis.owncloud.com/>

## Pantaila-argazkiak

![ownCloud(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://owncloud.com>
- Administratzaileen dokumentazio ofiziala: <https://doc.owncloud.com/ocis/next/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/owncloud/ocis>
- YunoHost Denda: <https://apps.yunohost.org/app/owncloud>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/owncloud_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/owncloud_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/owncloud_ynh/tree/testing --debug
edo
sudo yunohost app upgrade owncloud -u https://github.com/YunoHost-Apps/owncloud_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
