# FluxBB for YunoHost

[![](https://dash.yunohost.org/integration/fluxbb.svg) ![](https://ci-apps.yunohost.org/ci/badges/fluxbb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/fluxbb.maintain.svg)
](https://dash.yunohost.org/appci/app/fluxbb)  
[![Install FluxBB with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fluxbb)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install FluxBB quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/install) to know how to install and enjoy it.*

## Overview

FluxBB is fast, light, user-friendly forum software for your website.

**Shipped version:** 1.5.11

## Screenshots

![fluxbb_screenshot](sources/images/fluxbb_screenshot.png)

## Demo

* [Official demo](https://fluxbb.org/forums/index.php)

## Configuration

 * How to configure this app: by the admin panel.

## Documentation

 * Official documentation: https://fluxbb.org/docs/
 * YunoHost documentation: https://yunohost.org/en/app_fluxbb

## YunoHost specific features

#### Multi-users support

 * Are LDAP and HTTP auth supported? **No**  
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/fluxbb.svg)](https://ci-apps.yunohost.org/ci/apps/fluxbb/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/fluxbb.svg)](https://ci-apps-arm.yunohost.org/ci/apps/fluxbb/)

## Limitations

* Change-URL: once you change the URL, you should go to the admin panel and change the `Base URL`

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/fluxbb_ynh/issues
 * App website: https://fluxbb.org/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
or
sudo yunohost app upgrade fluxbb -u https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
```
