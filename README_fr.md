<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# DumbPad pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dumbpad)](https://ci-apps.yunohost.org/ci/apps/dumbpad/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dumbpad)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dumbpad)

[![Installer DumbPad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbpad)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer DumbPad rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Une application de bloc-notes moderne, simple, sans authentification (sauf si vous le souhaitez !), avec fonctionnalité d'enregistrement automatique et prise en charge du mode sombre.

### Caractéristiques

- Interface simple et propre
- Sauvegarde automatique
- Support du mode sombre
- Design réactif
- Protection par code PIN en option (4 à 10 chiffres)
- Stockage sur fichier
- Persistance des données entre les mises à jour
    

**Version incluse :** 2025.03.14~ynh1

## Captures d’écran

![Capture d’écran de DumbPad](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.dumbware.io/>
- Dépôt de code officiel de l’app : <https://github.com/DumbWareio/DumbPad>
- YunoHost Store : <https://apps.yunohost.org/app/dumbpad>
- Signaler un bug : <https://github.com/YunoHost-Apps/dumbpad_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dumbpad -u https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
