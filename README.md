# static-image

牌友迹小程序的宣传截图，供 V2EX 帖子外链使用。

| 文件 | 内容 |
|---|---|
| `images/paiyouji-multi.webp` | 多人模式，5 张带壳截图 |
| `images/paiyouji-single.webp` | 单人模式，4 张带壳截图 |

外链地址（jsDelivr 兼容镜像，国内可用）：

```
https://cdn.jsdmirror.com/gh/jimczj/static-image@main/images/paiyouji-multi.webp
https://cdn.jsdmirror.com/gh/jimczj/static-image@main/images/paiyouji-single.webp
```

别换成官方 `cdn.jsdelivr.net`：它对 `/gh/` 路径会 301 跳到 `raw.githubusercontent.com`，国内基本打不开。实测 `cdn.jsdmirror.com` 两个文件都是 200。

改图别覆盖同名文件，`@main` 有缓存；换新文件名，或者锁 commit hash。
