# FluxBB pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/fluxbb.svg)](https://dash.yunohost.org/appci/app/fluxbb) ![](https://ci-apps.yunohost.org/ci/badges/fluxbb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/fluxbb.maintain.svg)  
[![Installer FluxBB avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fluxbb)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer FluxBB rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

FluxBB is designed as a lighter, faster alternative to some of the traditional feature heavy forum applications. It is easy to use and has a proven track record of stability and security making it an ideal choice of forum for your website.


**Version incluse :** 1.5.11~ynh3

**Démo :** https://fluxbb.org/forums/index.php

## Captures d'écran

![](./doc/screenshots/fluxbb_screenshot.png)

## Avertissements / informations importantes

### Limitations with YunoHost

HTTP and LDAP authentication are not supported.
## Documentations et ressources

* Site officiel de l'app : https://fluxbb.org/
* Documentation officielle utilisateur : https://yunohost.org/en/app_fluxbb
* Documentation officielle de l'admin : https://fluxbb.org/docs/
* Documentation YunoHost pour cette app : https://yunohost.org/app_fluxbb
* Signaler un bug : https://github.com/YunoHost-Apps/fluxbb_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade fluxbb -u https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps