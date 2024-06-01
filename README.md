# openwrt-packages

自用软件包源码合集，每天自动更新，建议使用 [immortalwrt](https://github.com/immortalwrt/immortalwrt) 源码。

## 食用方式（二选一）：

`还是建议按需取用，不然碰到依赖问题不太好解决`

1. 先 `cd` 进 `package` 目录，然后执行：
    ```bash
    git clone https://github.com/wukibaka/openwrt-packages
    ```

2. 或者添加下面代码到 `feeds.conf.default` 文件：
    ```bash
    src-git wukibaka_packages https://github.com/wukibaka/openwrt-packages
    ```

## 插件列表

- [immortalwrt-packages](https://github.com/immortalwrt/packages)
- [luci-app-adguardhome](https://github.com/kenzok78/luci-app-adguardhome)
- [luci-app-argon-config](https://github.com/jerrykuku/luci-app-argon-config)
- [luci-app-mosdns](https://github.com/sbwml/luci-app-mosdns)
- [luci-app-openclash](https://github.com/vernesong/OpenClash)
- [luci-app-smartdns](https://github.com/pymumu/luci-app-smartdns)
- [luci-app-ssr-plus](https://github.com/fw876/helloworld)
- [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)