<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 OpenCloud

[![集成程度](https://apps.yunohost.org/badge/integration/opencloud)](https://ci-apps.yunohost.org/ci/apps/opencloud/)
![工作状态](https://apps.yunohost.org/badge/state/opencloud)
![维护状态](https://apps.yunohost.org/badge/maintained/opencloud)

[![使用 YunoHost 安装 OpenCloud](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opencloud)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 OpenCloud。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

OpenCloud is the new file sync & share platform that will be the foundation of your data management platform.    

### Features

- Fast, simple, and clean user interface
- Keyboard shortcuts for quick file selection
- Drag and drop support
- Powerful search by name, full text, OCR, file type, date, or tag
- Reliable, fault-tolerant file synchronization
- Flexible sharing options
- Share files with public links
- Workspaces: Dedicated project folders designed to simplify team collaboration
- Integrations with tools like Markdown Editor (ToastUI) and Web Office (Collabora)
- File history to track changes and restore previous versions
- Multi-device sync with offline access across all your devices


**分发版本：** 2.0.0~ynh2

## 截图

![OpenCloud 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://opencloud.eu/en>
- 上游应用代码库： <https://github.com/opencloud-eu/opencloud>
- YunoHost 商店： <https://apps.yunohost.org/app/opencloud>
- 报告 bug： <https://github.com/YunoHost-Apps/opencloud_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/opencloud_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opencloud_ynh/tree/testing --debug
或
sudo yunohost app upgrade opencloud -u https://github.com/YunoHost-Apps/opencloud_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
