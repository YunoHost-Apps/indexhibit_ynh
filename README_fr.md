# Indexhibit pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/indexhibit.svg)](https://dash.yunohost.org/appci/app/indexhibit) ![](https://ci-apps.yunohost.org/ci/badges/indexhibit.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/indexhibit.maintain.svg)  
[![Installer Indexhibit avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=indexhibit)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Indexhibit rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Indexhibit is a pioneering, influential, web-based content management system (CMS), founded in 2006 by Jeffery Vaska and Daniel Eatock, which is used primarily to create online portfolios (image, text and video).

It is intended for independent-minded creators, academics, researchers, students, collectors, et al., who wish to learn how and manage the visual display of their works, on their own terms, according to their own abilities.

From its inception, the project wanted to grant users a simple and quick way to publish, without many design constraints, allowing them to show their work with clarity in a neutral display. An early decision was made to not utilize every new web technology and keep it simple. Guiding principles were honesty, earnestness and diy.

Over the years Indexhibit was featured in design magazines and was part of art school curriculums. Vaska has conducted Indexhibit workshops on three continents.

Indexhibit is not a 'platform' and there is no tracking or selling of your data. You do you.

**Version incluse :** 2.1.6~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/146_indexhibit.png)

## Avertissements / informations importantes

Post install: `http://yourdomain.com/ndxzstudio/install.php` to finish the install.

Database credentials are sent to the administrator's email address.

Admin area: `http://yourdomain.com/ndxz-studio` (where `yourdomain.com` is your domain)


## Documentations et ressources

* Site officiel de l'app : https://www.indexhibit.org
* Documentation officielle de l'admin : https://forum.indexhibit.org/tutorials/getting-started/installation/
* Dépôt de code officiel de l'app : https://github.com/Indexhibit/indexhibit
* Documentation YunoHost pour cette app : https://yunohost.org/app_indexhibit
* Signaler un bug : https://github.com/YunoHost-Apps/indexhibit_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/indexhibit_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/indexhibit_ynh/tree/testing --debug
ou
sudo yunohost app upgrade indexhibit -u https://github.com/YunoHost-Apps/indexhibit_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps