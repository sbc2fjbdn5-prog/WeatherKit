# WeatherKit v3.2.0-beta4 镜像

这是 [`NSRingo/WeatherKit`](https://github.com/NSRingo/WeatherKit) `v3.2.0-beta4` 的固定版本镜像。发布附件、运行脚本、图标和城市网格数据均保存在本仓库，运行时地址已改为 `sbc2fjbdn5-prog/WeatherKit`。

## Quantumult X

推荐使用固定 Release 地址：

```text
https://github.com/sbc2fjbdn5-prog/WeatherKit/releases/download/v3.2.0-beta4/iRingo.WeatherKit.snippet
```

主分支 Raw 地址：

```text
https://raw.githubusercontent.com/sbc2fjbdn5-prog/WeatherKit/refs/heads/main/iRingo.WeatherKit.snippet
```

在 Quantumult X 中进入“设置 → 重写 → 右上角＋”，将上述地址作为资源路径添加。

## 其他客户端

| 客户端 | 固定镜像文件 |
|---|---|
| Loon | [`iRingo.WeatherKit.plugin`](https://github.com/sbc2fjbdn5-prog/WeatherKit/releases/download/v3.2.0-beta4/iRingo.WeatherKit.plugin) |
| Surge | [`iRingo.WeatherKit.sgmodule`](https://github.com/sbc2fjbdn5-prog/WeatherKit/releases/download/v3.2.0-beta4/iRingo.WeatherKit.sgmodule) |
| Stash | [`iRingo.WeatherKit.stoverride`](https://github.com/sbc2fjbdn5-prog/WeatherKit/releases/download/v3.2.0-beta4/iRingo.WeatherKit.stoverride) |

## 镜像内容

- 四种客户端配置均将 `response.bundle.js` 改为本仓库固定 Release 地址。
- `request.bundle.js`、`response.bundle.js` 均保存在仓库和 Release 中。
- `response.bundle.js` 使用的 QWeather 城市网格及六个天气图标均改为本仓库固定标签地址。
- `upstream-*` 文件保存未经修改的原始 Release 附件。
- [`SOURCE.md`](SOURCE.md) 记录来源版本、提交和修改范围。
- [`SHA256SUMS`](SHA256SUMS) 提供文件完整性校验值。

## 说明

镜像不会自动跟随上游更新。上游作者、项目主页及 Apache License 2.0 许可证信息均予以保留；完整许可证见 [`LICENSE`](LICENSE)。
