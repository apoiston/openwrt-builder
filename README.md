# OpenWrt SNAPSHOT

---

### Basic Information

- **LAN Address**: [10.0.0.1](http://10.0.0.1/)
- **Target Platform**: `x86/64`
- **Firmware Version**: `OpenWrt SNAPSHOT`
- **Username**: `root`
- **Password**: `NONE`

### Firmware Download

- [Releases](https://github.com/apoiston/openwrt-builder/releases)

### Package Download

- [extra](https://initextra.pages.dev/)

- [kmods](https://initkmods.pages.dev/)

- [packages](https://initpackages.pages.dev/)

### Common Commands

```shell
# update index
apk update
```

```shell
# upgrade mihomo core
apk add -U -u mihomo-alpha
```

```shell
# install packages
apk add --update luci-i18n-nikki-zh-cn luci-app-nikki nikki mihomo-alpha
```

```shell
# upgrade packages
apk add --update --upgrade mihomo-alpha nikki luci-app-nikki luci-i18n-nikki-zh-cn
```

```shell
# openwrt version
cat /etc/openwrt_version
```

```shell
# build details
cat /proc/version
```

```shell
# flash firmware
sysupgrade /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz
```

```shell
# flash firmware (clean install)
sysupgrade -n /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz
```

### Add Feed

```shell
# add key
wget -O /etc/apk/keys/initextra.pem https://initextra.pages.dev/public-key.pem
```

```shell
# add feed
echo https://initextra.pages.dev/snapshots/x86_64/extra/packages.adb >> /etc/apk/repositories.d/customfeeds.list
```

### Credits

- [Joseph Mory](https://github.com/nikkinikki-org/OpenWrt-nikki)

- [OpenWrt](https://github.com/openwrt/openwrt)

- [OpenWrt LuCI](https://github.com/openwrt/luci)

- [OpenWrt Packages](https://github.com/openwrt/packages)

- [GitHub](https://github.com)

- [GitHub Actions](https://github.com/features/actions)

- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo)
