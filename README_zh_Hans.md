<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 DumbPad

[![集成程度](https://apps.yunohost.org/badge/integration/dumbpad)](https://ci-apps.yunohost.org/ci/apps/dumbpad/)
![工作状态](https://apps.yunohost.org/badge/state/dumbpad)
![维护状态](https://apps.yunohost.org/badge/maintained/dumbpad)

[![使用 YunoHost 安装 DumbPad](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbpad)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 DumbPad。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A stupid simple, no auth (unless you want it!), modern notepad application with auto-save functionality and dark mode support.

### Features

- Simple, clean interface
- Auto-saving
- Dark mode support
- Responsive design
- Optional PIN protection (4-10 digits)
- File-based storage
- Data persistence across updates


**分发版本：** 2025.03.14~ynh1

## 截图

![DumbPad 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.dumbware.io/>
- 上游应用代码库： <https://github.com/DumbWareio/DumbPad>
- YunoHost 商店： <https://apps.yunohost.org/app/dumbpad>
- 报告 bug： <https://github.com/YunoHost-Apps/dumbpad_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
或
sudo yunohost app upgrade dumbpad -u https://github.com/YunoHost-Apps/dumbpad_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
