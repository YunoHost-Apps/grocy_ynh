# Grocy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/grocy.svg)](https://dash.yunohost.org/appci/app/grocy) ![](https://ci-apps.yunohost.org/ci/badges/grocy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/grocy.maintain.svg)  
[![Install Mantis with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=grocy)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Grocy quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Grocy is a web-based self-hosted groceries & household management solution for your home.

**Shipped version:** 2.7.1

## Screenshots

![](https://grocy.info/img/grocy-desktop-en.png)

## Demo

* [Official demo](https://en.demo.grocy.info/stockoverview)

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported?
* Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/grocy%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/grocy/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/grocy%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/grocy/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/grocy_ynh/issues
 * App website: https://grocy.info/
 * Upstream app repository: https://github.com/grocy/grocy
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/grocy_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/grocy_ynh/tree/testing --debug
or
sudo yunohost app upgrade grocy -u https://github.com/YunoHost-Apps/grocy_ynh/tree/testing --debug
```
