<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# DumbPad untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/dumbpad)](https://ci-apps.yunohost.org/ci/apps/dumbpad/)
![Status kerja](https://apps.yunohost.org/badge/state/dumbpad)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/dumbpad)

[![Pasang DumbPad dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbpad)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang DumbPad secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A stupid simple, no auth (unless you want it!), modern notepad application with auto-save functionality and dark mode support.

### Features

- Simple, clean interface
- Auto-saving
- Dark mode support
- Responsive design
- Optional PIN protection (4-10 digits)
- File-based storage
- Data persistence across updates


**Versi terkirim:** 2025.03.14~ynh1

## Tangkapan Layar

![Tangkapan Layar pada DumbPad](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.dumbware.io/>
- Depot kode aplikasi hulu: <https://github.com/DumbWareio/DumbPad>
- Gudang YunoHost: <https://apps.yunohost.org/app/dumbpad>
- Laporkan bug: <https://github.com/YunoHost-Apps/dumbpad_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
atau
sudo yunohost app upgrade dumbpad -u https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
