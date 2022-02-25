# HACS 极速版 

[HACS](https://hacs.xyz)是一款优秀的 [Home Assistant](https://www.home-assistant.io) 集成商店，然而国人想要使用它下载插件或前端卡片却困难重重，主要原因就是国内的网络环境。
本项目使用了[ghproxy.com](https://ghproxy.com)和[fastgit.org](https://fastgit.org)提供的GitHub镜像服务，可以让大家更快的下载商店里的插件。

## 安装

> 本项目为HACS官方集成的修改版，安装本项目版本会覆盖官方的集成，但是无需重新配置集成(共用一套配置)，因此你可以放心安装。如果想切换到官方版本，使用官方的shell命令再安装即可。

### 使用命令行安装

```bash
wget -O - https://cdn.jsdelivr.net/gh/hasscc/get/get | DOMAIN=hacs REPO_PATH=hacs-china/integration ARCHIVE_TAG=china bash -
```

- 如果是hassos/hassio/supervisor版本的HA，可直接在宿主机或`Terminal & SSH`加载项中执行上面的命令
- 如果是core/docker版本的HA，需要ssh登陆宿主机后，进入到HA配置目录执行

### 手动安装

- [下载](https://github.com/hacs-china/integration/releases/latest/download/hacs.zip)安装包并解压
- 通过samba/ftp复制解压出来的`custom_components`文件夹到你的HA配置目录
- 重启HA
- [添加HACS集成](https://my.home-assistant.io/redirect/config_flow_start/?domain=hacs)(仅首次安装)


------


# HACS (Home Assistant Community Store)

[![Total alerts](https://img.shields.io/lgtm/alerts/g/hacs/integration.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/hacs/integration/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/hacs/integration.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/hacs/integration/context:python)
[![Downloads for latest release](https://img.shields.io/github/downloads/hacs/integration/latest/total.svg)](https://github.com/hacs/integration/releases/latest)

_Manage (Install, track, upgrade) and discover custom elements for Home Assistant directly from the UI._

![gif](https://raw.githubusercontent.com/hacs/documentation/master/static/img/demo.gif)

## What?

HACS is a integration that gives the user a powerful UI to handle downloads of custom needs.

**Highlights of what HACS can do:**

- Help you discover new custom elements.
- Help you download new custom elements.
- Help you keep track of your custom elements.
  - Manage(download/update/remove)
  - Shortcuts to repositories/issue tracker

## Useful links

- [General documentation](https://hacs.xyz/)
- [Configuration](https://hacs.xyz/docs/configuration/basic)
- [FAQ](https://hacs.xyz/docs/faq/what)
- [GitHub](https://github.com/hacs)
- [Discord](https://discord.gg/apgchf8)
- [Become a GitHub sponsor? ❤️](https://github.com/sponsors/ludeeus)
- [BuyMe~~Coffee~~Beer? 🍺🙈](https://buymeacoffee.com/ludeeus)


## Issues

~~If~~ When you experience issues/bugs with this the best way to report them is to open an issue in **this** repo.

[Issue link](https://hacs.xyz/docs/issues)
