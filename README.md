<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# SoapboxFE for YunoHost

[![Integration level](https://dash.yunohost.org/integration/soapbox.svg)](https://dash.yunohost.org/appci/app/soapbox) ![Working status](https://ci-apps.yunohost.org/ci/badges/soapbox.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/soapbox.maintain.svg)  
[![Install SoapboxFE with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=soapbox)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install SoapboxFE quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

SoapboxFE is an alternative frontend for Pleroma.


**Shipped version:** 1.3.0~ynh1

## Screenshots

![Screenshot of SoapboxFE](./doc/screenshots/screenshot.jpg)

## Disclaimers / important information

### Important points to read before installing

- [Pleroma (Yunohost ver.)](https://github.com/YunoHost-Apps/pleroma_ynh) must be installed locally before you install SoapboxFE
- SoapboxFE must be installed under a Pleroma domain (i.e soapboxfe.your-pleroma-instance-domain.net)
- AdminFE under SoapboxFE returns 404

Using screen in case of disconnects

``` 
sudo apt-get install screen
screen
sudo yunohost app install https://github.com/YunoHost-Apps/soapbox_ynh.git
```
Recover after disconnect:
```
screen -d
screen -r
```

## Documentation and resources

* Official app website: <https://soapbox.pub/>
* Official admin documentation: <https://docs.soapbox.pub/>
* Upstream app code repository: <https://gitlab.com/soapbox-pub/soapbox-fe>
* YunoHost documentation for this app: <https://yunohost.org/app_soapbox>
* Report a bug: <https://github.com/YunoHost-Apps/soapbox_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing --debug
or
sudo yunohost app upgrade soapbox -u https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
