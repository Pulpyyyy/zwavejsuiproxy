![GitHub release (with filter)](https://img.shields.io/github/v/release/Pulpyyyy/zwavejsuiproxy) ![GitHub](https://img.shields.io/github/license/Pulpyyyy/zwavejsuiproxy)

# Home Assistant Add-on: Z-Wave JS UI Proxy

⚠️ This addon does not contain Z-wave JS UI ⚠️

This addon acts as a proxy to an external running Z-wave JS UI instance. 
The sole purpose of this addon is to add a Z-wave JS UI icon to the sidebar of Home Assistant which will open the frontend of an external running Z-wave JS UI instance.

## Installation


[![Addon Home Assistant](https://raw.githubusercontent.com/Pulpyyyy/zwavejsuiproxy/refs/heads/main/.github/img/addon-ha.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FPulpyyyy%2Fzwavejsuiproxy/)

## Options

- `server` (required): this should be the local URL on which the Z-wave JS UI frontend is running, e.g. `http://192.168.1.222:8091` or even `https://192.168.1.222:8091`. Make sure there is no trailing slash!

## Extra
Default credentials to use Z-Wave JS UI are "admin/zwave"

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

![image](https://github.com/Pulpyyyy/zwavejsuiproxy/blob/d7ab9ad0419e9bc5eab38b41e8c90e380d92d3c8/img/proxy.png)
