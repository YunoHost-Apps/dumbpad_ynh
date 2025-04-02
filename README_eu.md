<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# DumbPad YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/dumbpad)](https://ci-apps.yunohost.org/ci/apps/dumbpad/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/dumbpad)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/dumbpad)

[![Instalatu DumbPad YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbpad)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek DumbPad YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A stupid simple, no auth (unless you want it!), modern notepad application with auto-save functionality and dark mode support.

### Features

- Simple, clean interface
- Auto-saving
- Dark mode support
- Responsive design
- Optional PIN protection (4-10 digits)
- File-based storage
- Data persistence across updates


**Paketatutako bertsioa:** 2025.03.26~ynh1

## Pantaila-argazkiak

![DumbPad(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.dumbware.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/DumbWareio/DumbPad>
- YunoHost Denda: <https://apps.yunohost.org/app/dumbpad>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/dumbpad_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing).

`testing` abarra probatzeko, honakoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
edo
sudo yunohost app upgrade dumbpad -u https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
