# OpenWrt SNAPSHOT

---

### Basic Information

- **LAN Address**: `10.0.0.1`
- **Target Platform**: `x86/64`
- **Firmware Version**: `OpenWrt SNAPSHOT`
- **Username**: `root`
- **Password**: `NONE`

### Package Repositories

- [infinityapps](https://infinityapps.pages.dev/)

- [infinitykmods](https://infinitykmods.pages.dev/)

- [infinitypackages](https://infinitypackages.pages.dev/)

### Firmware Download

- [Releases](https://github.com/apoiston/openwrt-builder/releases)

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
# upgrade nikki
apk add -U nikki
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

### Special Thanks

- [Joseph Mory](http://github.com/morytyann)

- [OpenWrt](https://github.com/openwrt/openwrt)

- [OpenWrt LuCI](https://github.com/openwrt/luci)

- [OpenWrt Packages](https://github.com/openwrt/packages)

- [GitHub](https://github.com)

- [GitHub Actions](https://github.com/features/actions)
