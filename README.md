<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Uptime Kuma for YunoHost

[![Integration level](https://dash.yunohost.org/integration/uptime-kuma.svg)](https://dash.yunohost.org/appci/app/uptime-kuma) ![](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.maintain.svg)  
[![Install Uptime Kuma with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Uptime Kuma quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

It is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Fancy, Reactive, Fast UI/UX.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP), and 70+ notification services, click here for the full list.
- 20 second intervals.
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Shipped version:** 1.0~ynh1

**Demo:** https://demo.uptime.kuma.pet

## Screenshots

![](./doc/screenshots/example.jpg)

## Disclaimers / important information

- Not working yet
- Uses N to install specific nodejs version
<!-- * Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...


- Other infos that people should be aware of, such as:
  - any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
  - how to configure / administrate the application if it ain't obvious
  - upgrade process / specificities / things to be aware of ?
  - security considerations ? -->

## Documentation and resources

* Official app website: https://uptime.kuma.pet/
* Official user documentation: https://github.com/louislam/uptime-kuma/wiki
* Official admin documentation: https://github.com/louislam/uptime-kuma/wiki
* Upstream app code repository: https://github.com/louislam/uptime-kuma/
* YunoHost documentation for this app: https://yunohost.org/app_uptime-kuma
* Report a bug: https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
or
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps