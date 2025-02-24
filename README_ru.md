<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# DumbPad для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/dumbpad)](https://ci-apps.yunohost.org/ci/apps/dumbpad/)
![Состояние работы](https://apps.yunohost.org/badge/state/dumbpad)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/dumbpad)

[![Установите DumbPad с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbpad)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить DumbPad быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 1.0.0~ynh1

## Снимки экрана

![Снимок экрана DumbPad](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.dumbware.io/>
- Репозиторий кода главной ветки приложения: <https://github.com/DumbWareio/DumbPad>
- Магазин YunoHost: <https://apps.yunohost.org/app/dumbpad>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/dumbpad_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
или
sudo yunohost app upgrade dumbpad -u https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
