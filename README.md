# RetroMusicLab — 成品发布页

RetroMusicLab 是一个把游戏芯片音源（SPC / GBS / HES / GYM / SAP / AY / KSS / WSR / S98 /
PSF / PSF2 / USF / SSF / GSF / QSF / VIO 等）浏览、下载、转成 WAV/MP3、并直接播放的桌面工具。

**本仓库只放可直接运行的成品，不含任何源代码** —— 源码仓库为私有。

## 下载

最新版本在 [Releases](../../releases/latest) 页面：

| 文件 | 说明 |
|---|---|
| `RetroMusicLab.exe` | 单文件绿色版，双击即用，无需安装 |
| `RetroMusicLab-vX.Y-win64.zip` | 解压即用，含用户手册 |
| `USER-GUIDE.zh-CN.md` | 用户手册（中文） |
| `CHANGELOG-vX.Y.zh-CN.md` | 本版更新说明 |
| `SHA256SUMS.txt` / `md5` | 下载后校验用 |

**系统要求**：Windows 10 / 11 64 位。首次启动如需转换 MP3，程序会自行准备编码器。

## 校验

```powershell
# PowerShell
Get-FileHash .\RetroMusicLab.exe -Algorithm SHA256
```

把结果和发布页里的 `SHA256SUMS.txt` 对一下即可。

## 反馈

发现 bug 或想要新功能，直接在本仓库开 Issue。附上程序版本号和复现步骤，
能大幅缩短定位时间。

## 说明

- 本仓库的 Release 由私有源码仓库构建后上传，二进制与源码版本一一对应。
- 芯片音源版权归各自权利人所有，本工具只做格式转换与播放，不提供任何音源下载源的所有权。
