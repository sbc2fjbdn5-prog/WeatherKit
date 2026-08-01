# 来源和修改记录

## 上游来源

- 项目：`NSRingo/WeatherKit`
- 原始版本：`v3.2.0-beta4`
- 标签提交：`518cef7e457618f9ea06d43eb85ba4a7b8e9afe2`
- 原始 Release：<https://github.com/NSRingo/WeatherKit/releases/tag/v3.2.0-beta4>
- WeatherKit 图标来源提交：`518cef7e457618f9ea06d43eb85ba4a7b8e9afe2`
- 城市网格项目：`NSRingo/QWeather-Location-Grid`
- 城市网格来源提交：`8a4f1aab8c887fad0fd2b837e773dd025b0d456b`
- 镜像建立日期：2026-08-02

## 原始 Release 文件校验值

```text
1be04bba8fe5b7bf32db4865a5aa5a0d1252e51ecc80ecbc9988489bfbf78111  upstream-iRingo.WeatherKit.plugin
6d842d5fa8f84ab098253cb90a8438a64d3a0b4247f9c3cfbcf3ad0443b9d11d  upstream-iRingo.WeatherKit.sgmodule
814cdd43bb2d608e2600a25c3bf18e46dc6b8ddf860c5e88b120dd36ba4a491a  upstream-iRingo.WeatherKit.snippet
acb031d30ec19b5f6eb8282f9122423fb3fe99c8d30a727ddcd657a59c7cac51  upstream-iRingo.WeatherKit.stoverride
36f14c3da130b29d993f0167ffb13909d89d828a398535e8fbb72e51560183dc  upstream-request.bundle.js
02aec4b0bf49210c4c560480ac64b50e74b3c825d1d4c8c93db944d4ea2359fb  upstream-response.bundle.js
```

## 修改内容

客户端配置文件：

- 将 `NSRingo/WeatherKit` Release 中的 `response.bundle.js` 地址替换为 `sbc2fjbdn5-prog/WeatherKit` 的同版本 Release 地址。
- 未修改重写表达式、参数、MITM 域名和功能逻辑。

`response.bundle.js`：

- 将 QWeather 城市网格地址改为本仓库 `v3.2.0-beta4` 标签下的镜像文件。
- 将 `ColorfulClouds`、`WAQI`、`WeatherOL` 图标地址改为本仓库同版本标签下的镜像文件。
- 在文件开头添加镜像说明注释。

`request.bundle.js`：

- 保持原始 Release 内容不变，仅作为完整版本快照保存。

所有原始 Release 文件均以 `upstream-` 前缀完整保留。除上述地址及注释外，不修改上游逻辑。
