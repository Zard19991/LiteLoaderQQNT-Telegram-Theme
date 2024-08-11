# LiteLoaderQQNT-Telegram-Theme

[LiteLoaderQQNT](https://github.com/LiteLoaderQQNT/LiteLoaderQQNT) 插件，高仿 Telegram 风格的 QQNT 主题

![light](screenshot/screenshot-light.png)

## 介绍

-   全方位高仿 Telegram
-   支持自定义壁纸
-   支持日间模式、夜间模式
-   Telegram 风格气泡
-   Telegram 风格输入框
-   支持连续消息合并
-   支持头像浮动
-   支持会话列表仅保留头像
-   支持自定义主题样式，提供大量设置项

## 版本适配

-   仅适配 **LiteLoaderQQNT 1.0.0** 及以上版本

## 使用方法

1.  从 [Release](https://github.com/festoney8/LiteLoaderQQNT-Telegram-Theme/releases) 下载 zip 压缩包（或直接 clone 项目）

2.  将主题文件解压到 [LiteLoaderQQNT 数据目录](https://liteloaderqqnt.github.io/guide/plugins.html) 的 `plugins` 文件夹下

3.  重启 QQ

> [!CAUTION]
>
> -   **注意：切换 日间/夜间模式 时，主题会自动适配，但设置页不会更新。需重新打开设置页，再修改主题设置**
> -   **本主题自带「头像置底、头像浮动、连续消息合并、右键菜单高亮显示回复和撤回、会话列表仅头像」，若同时使用 [轻量工具箱](https://github.com/xiyuesaves/LiteLoaderQQNT-lite_tools)，请关闭工具箱的相似功能**

## 兼容性

-   **请不要与其他 LiteLoader 主题同时使用**

-   本主题自带「自定义壁纸」功能，不必与其他插件的自定义壁纸同时启用。若功能失效，查看是否启用了官方的「超级调色盘」，是否使用了轻量工具箱的壁纸功能

-   本主题与 [背景插件](https://github.com/xh321/LiteLoaderQQNT-Background-Plugin) 存在样式冲突，会产生意料之外的融合效果

    -   正常情况下，本主题自带壁纸会覆盖掉背景插件的壁纸。若需同时启用，将 [这张全透明图片](https://upload.wikimedia.org/wikipedia/commons/8/89/HD_transparent_picture.png) 下载下来，设置成 Telegram 主题壁纸即可

-   本主题与 [Markdown 插件](https://github.com/d0j1a1701/LiteLoaderQQNT-Markdown/tree/v4) 共用时，会出现气泡圆角样式、图文混合消息样式问题，不影响正常功能

## 截图

### 日间模式

![light](screenshot/screenshot-light.png)

### 夜间模式

![dark](screenshot/screenshot-dark.png)

### 设置页

![setting](screenshot/screenshot-setting.png)

## 开发

-   本项目无需构建，package 管理仅用于代码 lint 和 format
-   css 文件由 scss 文件直接生成，可使用 [sass 命令](https://sass-lang.com/install/) 或 [Vscode 插件](https://code.visualstudio.com/docs/languages/css)

## 其他

-   本项目纯娱乐用途，仅供学习交流，请勿在微信、QQ、B 站之类的平台传播
-   没学过 Electron，代码菜，能跑就行，能跑的代码都是 GPT 写的，bug 都是我写的（
