<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Isso for YunoHost

[![Integration level](https://dash.yunohost.org/integration/isso.svg)](https://dash.yunohost.org/appci/app/isso) ![Working status](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Install Isso with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Isso quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Isso – *Ich schrei sonst* – is a lightweight commenting server written in
Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- **Comments written in Markdown**  
  Users can edit or delete own comments (within 15 minutes by default).
  Comments in moderation queue are not publicly visible before activation.
- **SQLite backend**  
  *Because comments are not Big Data.*
- **Disqus & WordPress Import**  
  You can migrate your Disqus/WordPress comments without any hassle.
- **Configurable JS client**  
  Embed a single JS file, 65kB (20kB gzipped) and you are done.

**Shipped version:** 0.13.0~ynh2

**Demo:** https://isso-comments.de

## Screenshots

![Screenshot of Isso](./doc/screenshots/example.jpg)

## Disclaimers / important information

* Limitations
    * Requires a dedicated domain

* Extra information
    * The admin interface for the app is `https://yourdomain.tld/admin`
    * One app instance can only be installed for one domain
    * Please do not add a trailing `/` in the target_domain

## Documentation and resources

* Official app website: <https://isso-comments.de>
* Official user documentation: <https://isso-comments.de/docs/reference/client-config/>
* Official admin documentation: <https://isso-comments.de/docs/reference/server-config/>
* Upstream app code repository: <https://github.com/posativ/isso>
* YunoHost documentation for this app: <https://yunohost.org/app_isso>
* Report a bug: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
or
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
