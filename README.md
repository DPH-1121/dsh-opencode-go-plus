# dsh-opencode-go-plus

在 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 中使用 OpenCode Go 订阅模型：自动带上网关要求的会话请求头，实时拉取模型目录并为新模型适配协议，在设置页配置 API Key、查看套餐剩余额度。

本包是 [`dsh-opencode-go`](https://github.com/Duskriver/dsh-opencode-go) 的维护分支，修掉了「模型明明在网关目录里、却静默不出现在选择器」的几类问题。它与上游**不能同时安装**，升级时先卸载旧包。支持 dsh `0.1.6` / `0.1.7` / `0.2.x`（含桌面版）。

配置、迁移与排错细节见[使用说明](./docs/guide.md)。

## 安装

见 [**DSH 插件安装教程**](https://github.com/DPH-1121/dsh-plugins/blob/main/docs/install.md)。

## 其他 DSH 插件

- [dsh-provider-plus](https://github.com/DPH-1121/dsh-provider-plus) —— 自定义模型提供商工作台：图片输入、网关请求头、模型拉取、连通性测试、用量查询。
- [dsh-wallhaven-wallpaper](https://github.com/DPH-1121/dsh-wallhaven-wallpaper) —— 在设置里搜 wallhaven，把图片铺成 Web GUI 背景。
- [dsh-plugins](https://github.com/DPH-1121/dsh-plugins) —— DSH 插件搜集面板：搜仓库、复制安装地址。

## 许可

MIT。派生自 [`Duskriver/dsh-opencode-go`](https://github.com/Duskriver/dsh-opencode-go)，上游版权归各自作者所有。