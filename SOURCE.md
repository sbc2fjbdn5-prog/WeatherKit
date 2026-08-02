# 来源和修改记录

## 上游来源

- 项目：`NSRingo/WeatherKit`
- 原始版本：`v3.2.0-beta4`
- 标签提交：`9123a0422a900debf7f09c9c981f8c3129bbcc52`
- 原始 Release：<https://github.com/NSRingo/WeatherKit/releases/tag/v3.2.0-beta4>
- 上游附件更新时间：`2026-08-02T10:05:22Z`
- WeatherKit 图标来源提交：`9123a0422a900debf7f09c9c981f8c3129bbcc52`
- 城市网格项目：`NSRingo/QWeather-Location-Grid`
- 城市网格来源提交：`8a4f1aab8c887fad0fd2b837e773dd025b0d456b`
- 镜像建立日期：2026-08-02

## 原始 Release 文件校验值

```text
649d27c4ce1aa887695f97c56e79d6ddbff3f5d470ae98a1336888723e48945c  upstream-iRingo.WeatherKit.plugin
bbf3b320187d5d08d49fce72ca75ee4c97630157a18e9d887a5bc6ceef893bab  upstream-iRingo.WeatherKit.sgmodule
d973c31d78fa8cf91c8579944f129d1b2117dcf3c7224b7ef9418c7c1603aa92  upstream-iRingo.WeatherKit.snippet
3adc8dd802d6902338c784cc0339b5a6739de15ea34fd93088d2d0eb67771aa1  upstream-iRingo.WeatherKit.stoverride
9a796f0069e71e9d91bdc022b19faebab4eea713d158d5e68664181d8ea9ee4f  upstream-request.bundle.js
320934bd7993c3147f58a17208b245e11658ff0043bc64313061cbff13300663  upstream-response.bundle.js
```

## 修改内容

客户端配置文件：

- 将 `NSRingo/WeatherKit` Release 中的 `request.bundle.js`、`response.bundle.js` 地址替换为 `sbc2fjbdn5-prog/WeatherKit` 的同版本 Release 地址。
- 未修改重写表达式、参数、MITM 域名和功能逻辑。

`response.bundle.js`：

- 将 QWeather 城市网格地址改为本仓库 `v3.2.0-beta4` 标签下的镜像文件。
- 将 `ColorfulClouds`、`WAQI`、`WeatherOL` 图标地址改为本仓库同版本标签下的镜像文件。
- 在文件开头添加镜像说明注释。

`request.bundle.js`：

- 保持原始 Release 内容不变；本次上游更新将天气预警处理由响应阶段调整到请求阶段，因此客户端配置会调用该脚本。

所有原始 Release 文件均以 `upstream-` 前缀完整保留。除上述地址及注释外，不修改上游逻辑。
