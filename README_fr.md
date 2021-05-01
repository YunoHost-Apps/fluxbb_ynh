# FluxBB pour YunoHost

[![](https://dash.yunohost.org/integration/fluxbb.svg) ![](https://ci-apps.yunohost.org/ci/badges/fluxbb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/fluxbb.maintain.svg)
](https://dash.yunohost.org/appci/app/fluxbb)  
[![Install FluxBB with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fluxbb)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer FluxBB rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

FluxBB est un forum de discussions écrit en PHP rapide et léger.

**Version incluse :** 1.5.11

## Captures d'écran

![fluxbb_screenshot](sources/images/fluxbb_screenshot.png)

## Démo

* [Démo officielle](https://fluxbb.org/forums/index.php)

## Configuration

 * Comment configurer cette application : via le panneau d'administration.

## Documentation

 * Documentation officielle: https://fluxbb.org/docs/
 * Documentation YunoHost: https://yunohost.org/fr/app_fluxbb

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

 * L'authentification LDAP et HTTP est-elle prise en charge ? **Non** 
 * L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/fluxbb.svg)](https://ci-apps.yunohost.org/ci/apps/fluxbb/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/fluxbb.svg)](https://ci-apps-arm.yunohost.org/ci/apps/fluxbb/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Change-url : une fois l'URL modifiée, allez dans le panneau de configuration pour modifier le champ `Base URL`

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/fluxbb_ynh/issues
 * Site de l'application: https://fluxbb.org/
 * Site web YunoHost: https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade fluxbb -u https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
```
