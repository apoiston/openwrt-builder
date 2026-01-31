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

### Package Repositories

- [apps](https://infinityapps.pages.dev/)

- [kmods](https://infinitykmods.pages.dev/)

- [packages](https://infinitypackages.pages.dev/)

### Common Commands

```shell
# update index
apk update
```

```shell
# upgrade all
apk upgrade
```

```shell
# install packages
apk add --update luci-i18n-nikki-zh-cn luci-app-nikki nikki
```

```shell
# upgrade packages
apk add --update --upgrade nikki luci-app-nikki luci-i18n-nikki-zh-cn
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

### Credits

- [Joseph Mory](http://github.com/morytyann)

- [OpenWrt](https://github.com/openwrt/openwrt)

- [OpenWrt LuCI](https://github.com/openwrt/luci)

- [OpenWrt Packages](https://github.com/openwrt/packages)

- [GitHub](https://github.com)

- [GitHub Actions](https://github.com/features/actions)

- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo)

- [timsaya/bandix](https://github.com/timsaya/luci-app-bandix)
