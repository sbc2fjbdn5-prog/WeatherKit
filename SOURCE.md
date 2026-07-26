# 来源和修改记录

## 上游来源

- 项目：`NSRingo/WeatherKit`
- 原始版本：`v3.2.0-beta1`
- 标签提交：`cf1343560dd9ef0c1226daa865ef0ca4c2497d95`
- 原始插件：
  `https://github.com/NSRingo/WeatherKit/releases/download/v3.2.0-beta1/iRingo.WeatherKit.plugin`
- 原始运行脚本：
  `https://github.com/NSRingo/WeatherKit/releases/download/v3.2.0-beta1/response.bundle.js`
- 图标来源提交：
  `NSRingo/WeatherKit@1a2f64883d866a6974a9a5369a82191c49413617`
- 城市网格项目：`NSRingo/QWeather-Location-Grid`
- 城市网格来源提交：
  `8a4f1aab8c887fad0fd2b837e773dd025b0d456b`
- 镜像建立日期：2026-07-26

## 原始 Release 文件校验值

```text
73f092fd7a8eddc9dc5aa52a0f0a2a38e79041d50fb089b8ed57ca14edfc3955  upstream-iRingo.WeatherKit.plugin
da6a705a072ea484ad718f414bbfd72f34fe24209cee3cb8e75cff73ac47e600  upstream-response.bundle.js
```

## 修改内容

`iRingo.WeatherKit.plugin`：

- 将两个 `script-path` 从上游 Release 地址改为
  `sbc2fjbdn5-prog/WeatherKit` 中的固定镜像地址。
- 添加醒目的镜像修改说明。

`response.bundle.js`：

- 将 QWeather 城市网格地址改为本仓库镜像地址。
- 将 `ColorfulClouds`、`WAQI`、`WeatherOL` 图标地址改为本仓库镜像地址。
- 在文件开头添加醒目的镜像修改说明。

除上述地址和说明外，不修改上游逻辑。
