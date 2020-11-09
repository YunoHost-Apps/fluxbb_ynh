# FluxBB for YunoHost

![fluxbb_logo](sources/images/fluxbb_logo.png)

[
![](https://dash.yunohost.org/integration/fluxbb.svg)
![](https://ci-apps.yunohost.org/ci/badges/fluxbb.status.svg)
![](https://ci-apps.yunohost.org/ci/badges/fluxbb.maintain.svg)
](https://dash.yunohost.org/appci/app/fluxbb)

[![Install FluxBB with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=fluxbb)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install FluxBB quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

FluxBB is fast, light, user-friendly forum software for your website.

**Shipped version:** 1.5.11

## Screenshots

![fluxbb_screenshot](sources/images/fluxbb_screenshot.png)

## Demo

* [Official demo](https://fluxbb.org/forums/index.php)

## Configuration

How to configure this app: by the admin panel.

## Documentation

 * Official documentation: https://fluxbb.org/docs/
 * YunoHost documentation: https://yunohost.org/#/app_fluxbb

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported? no  
Can the app be used by multiple users? yes

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/fluxbb%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/fluxbb/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/fluxbb%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/fluxbb/)

## Limitations

* Change-url : once you change the url, you should go to the admin panel and change the `Base URL`

## Additional information

* Other info you would like to add about this app.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/fluxbb_ynh/issues
 * App website: https://fluxbb.org/
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
or
sudo yunohost app upgrade fluxbb -u https://github.com/YunoHost-Apps/fluxbb_ynh/tree/testing --debug
```
