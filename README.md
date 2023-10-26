# OpenWrt Home Assistant Packages (python3) 
Join Telegram group: [![@sgw_openwrt](https://img.shields.io/badge/%F0%9F%92%AC%20Telegram-%40SmartGateway-blue.svg)](https://t.me/sgw_openwrt)

## Description

OpenWrt Home Assistant Packages : for Head (Development branch)
![HomeAssistant logo](https://raw.github.com/home-assistant/home-assistant/master/docs/screenshots.png)

## License

See [LICENSE](LICENSE) file.

## Usage

Add the following line to feeds.conf or feeds.conf.default.
```
src-git homeassistant https://github.com/kuncy7/SGW-Homeassistant.git
```

Run
```
./scripts/feeds update homeassistant
./scripts/feeds install -a -p homeassistant
make defconfig
```

## Request to add a package is welcome
If you want a new module (native module) that requires a precompiled binary, ***please open the issue.***
