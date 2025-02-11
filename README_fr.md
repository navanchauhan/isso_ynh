<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Isso pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/isso.svg)](https://ci-apps.yunohost.org/ci/apps/isso/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Installer Isso avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Isso rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Isso – *Ich schrei sonst* – est un serveur de commentaires léger écrit en Python et JavaScript. Il vise à être un remplacement direct pour [Disqus](http://disqus.com).

### Caractéristiques

- Commentaires rédigés en Markdown
- Back-end SQLite
- Importation Disqus & WordPress
- Client JS paramétrable

**Version incluse :** 0.13.0~ynh5

**Démo :** <https://isso-comments.de>

## Captures d’écran

![Capture d’écran de Isso](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://isso-comments.de>
- Documentation officielle utilisateur : <https://isso-comments.de/docs/reference/client-config/>
- Documentation officielle de l’admin : <https://isso-comments.de/docs/reference/server-config/>
- Dépôt de code officiel de l’app : <https://github.com/posativ/isso>
- YunoHost Store : <https://apps.yunohost.org/app/isso>
- Signaler un bug : <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
ou
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
