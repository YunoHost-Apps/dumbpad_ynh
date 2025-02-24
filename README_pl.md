<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# DumbPad dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/dumbpad)](https://ci-apps.yunohost.org/ci/apps/dumbpad/)
![Status działania](https://apps.yunohost.org/badge/state/dumbpad)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/dumbpad)

[![Zainstaluj DumbPad z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbpad)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację DumbPad na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

A stupid simple, no auth (unless you want it!), modern notepad application with auto-save functionality and dark mode support.

### Features

    Simple, clean interface
    Auto-saving
    Dark mode support
    Responsive design
    Docker support
    Optional PIN protection (4-10 digits)
    File-based storage
    Data persistence across updates


**Dostarczona wersja:** 1.0.0~ynh1

## Zrzuty ekranu

![Zrzut ekranu z DumbPad](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.dumbware.io/>
- Repozytorium z kodem źródłowym: <https://github.com/DumbWareio/DumbPad>
- Sklep YunoHost: <https://apps.yunohost.org/app/dumbpad>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/dumbpad_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
lub
sudo yunohost app upgrade dumbpad -u https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
