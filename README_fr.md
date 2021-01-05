# Grocy pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/grocy.svg)](https://dash.yunohost.org/appci/app/grocy) ![](https://ci-apps.yunohost.org/ci/badges/grocy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/grocy.maintain.svg)  
[![Install Grocy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grocy)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Grocy rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Grocy is a web-based self-hosted groceries & household management solution for your home.

**Version incluse :** 3.0.1

## Captures d'écran

![](https://grocy.info/img/grocy-desktop-en.png)

## Démo

* [Démo officielle](https://en.demo.grocy.info/stockoverview)

## Configuration

 Default login
 	user:     **admin**  
 	password: **admin**
 	
## Documentation

 * Documentation officielle : Lien vers la documentation officielle de cette application.
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/grocy%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/grocy/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/grocy%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/grocy/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/grocy_ynh/issues
 * Site de l'application : https://grocy.info/
 * Dépôt de l'application principale : https://github.com/grocy/grocy
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/grocy_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/grocy_ynh/tree/testing --debug
or
sudo yunohost app upgrade grocy -u https://github.com/YunoHost-Apps/grocy_ynh/tree/testing --debug
```
