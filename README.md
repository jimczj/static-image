# static-image

牌友迹小程序的宣传截图，供 V2EX 帖子外链使用。

| 文件 | 内容 |
|---|---|
| `images/paiyouji-multi-tall.webp` | 多人模式，1200×4283 竖屏版，每行 2 张共 3 行 |
| `images/paiyouji-single-tall.webp` | 单人模式，1200×3042 竖屏版，每行 2 张共 2 行 |
| `images/paiyouji-qrcode.webp` | 小程序码，900×900 无损 |
| `images/paiyouji-multi.webp` / `paiyouji-single.webp` | 旧版横排合图，保留以免旧链接失效 |

外链地址（jsDelivr 兼容镜像，国内可用）：

```
https://cdn.jsdmirror.com/gh/jimczj/static-image@8a0aa48/images/paiyouji-multi-tall.webp
https://cdn.jsdmirror.com/gh/jimczj/static-image@8a0aa48/images/paiyouji-single-tall.webp
https://cdn.jsdmirror.com/gh/jimczj/static-image@8a0aa48/images/paiyouji-qrcode.webp
```

别换成官方 `cdn.jsdelivr.net`：它对 `/gh/` 路径会 301 跳到 `raw.githubusercontent.com`，国内基本打不开。实测 `cdn.jsdmirror.com` 可正常访问。

当前外链锁在 commit `8a0aa48`（无投影版）。改图后要重新锁 hash 或换文件名，`@main` 有缓存。
