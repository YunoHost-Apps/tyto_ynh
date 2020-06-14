# Tyto for YunoHost ![alt tag](https://github.com/YunoHost-Apps/tyto_ynh/blob/master/68747470733a2f2f7261772e6769746875622e636f6d2f6a6833792f7479746f2f6d61737465722f7372632f696d672f7479746f2e706e67.png)

[![Integration level](https://dash.yunohost.org/integration/tyto.svg)](https://dash.yunohost.org/appci/app/tyto) ![](https://ci-apps.yunohost.org/ci/badges/tyto.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/tyto.maintain.svg)  
[![Install Tyto with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=tyto)

> *This package allows you to install Tyto quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Tyto arose from the want for an electronic post-it board without the need for accounts. Something simple and intuitive that could be easily shared.

**Shipped version:** 3.0.4

## Screenshots

![](https://github.com/YunoHost-Apps/tyto_ynh/blob/master/68747470733a2f2f7261772e6769746875622e636f6d2f6a6833792f706963732f6d61737465722f7479746f2f6164645f7461736b2e676966.gif.)

## Demo

* [Official demo](https://jh3y.github.io/tyto)


### Features
* minimal UI
* no accounts necessary
* intuitive
* extensible
* localStorage persistence
* time tracking
* sortable UI
* task linking
* Markdown support
* etc.

## YunoHost specific features

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/tyto%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/tyto/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/tyto%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/tyto/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/tyto_ynh/issues
 * Upstream app repository: https://github.com/jh3y/tyto
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/tyto_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/tyto_ynh/tree/testing --debug
or
sudo yunohost app upgrade tyto -u https://github.com/YunoHost-Apps/tyto_ynh/tree/testing --debug
```
