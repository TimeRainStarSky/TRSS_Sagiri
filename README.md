# TRSS Sagiri 纱雾机器人管理脚本
[![Stars](https://img.shields.io/github/stars/TimeRainStarSky/TRSS_Sagiri?color=yellow&label=收藏)](https://github.com/TimeRainStarSky/TRSS_Sagiri/stargazers)
[![Downloads](https://img.shields.io/github/downloads/TimeRainStarSky/TRSS_Sagiri/total?color=blue&label=下载)](https://gitee.com/TimeRainStarSky/TRSS_Sagiri/raw/main/Install.sh)
[![Releases](https://img.shields.io/github/v/release/TimeRainStarSky/TRSS_Sagiri?color=green&label=发布版本)](https://github.com/TimeRainStarSky/TRSS_Sagiri/releases/latest)  
[![访问量](https://profile-counter.glitch.me/TimeRainStarSky-TRSS_Sagiri/count.svg)](https://timerainstarsky.github.io/TRSS_Sagiri)

## 使用教程
1. 准备：[Arch Linux](https://archlinux.org)
- [Windows](https://www.microsoft.com/windows) 推荐使用 [ArchWSL](https://github.com/yuk7/ArchWSL) [详细教程](https://bytem.io/posts/install-arch-wsl)
- [Termux](https://github.com/hanxinhao000/ZeroTermux) 或`其他 Linux 发行版`推荐使用 [TMOE](https://gitee.com/mo2/linux) 安装 [Arch Linux](https://archlinux.org) 容器：
```
bash -c "$(curl -L https://gitee.com/mo2/linux/raw/2/2)"
```
- 有`root 权限`使用`chroot 容器`，否则使用`proot 容器`
- 进入 proot/chroot 容器：`tmoe p/c a`

2. 安装：
```
curl -LO "https://gitee.com/TimeRainStarSky/TRSS_Sagiri/raw/main/Install.sh" && bash Install.sh
```

3. 启动：`tssi`

视频教程：<https://b23.tv/av983453309>

## 使用说明
- [Sagiri](https://sagiri-kawaii.github.io/sagiri-bot) <-WS连接-> [Mirai](https://docs.mirai.mamoe.net) <-网络连接-> [QQ服务器](https://im.qq.com)
- [Mirai](https://docs.mirai.mamoe.net)：提供QQ账号管理，收发消息等功能
- [Sagiri](https://sagiri-kawaii.github.io/sagiri-bot)：对消息进行处理，完成目标操作

## 常见问题
- 问：发消息错误：46
- 答：账号被风控

- 问：无法连接到反向 WebSocket Universal 服务器
- 答：请确认 Sagiri 正常运行并启动了 Uvicorn WebSocket 服务器

- 问：address already in use
- 答：WebSocket 端口被占用，请尝试停止占用进程、重启设备，或修改配置文件，更改 WebSocket 端口

- 问：open terminal failed: not a terminal
- 答：TMOE proot 容器首次启动会出现，退出容器重启就行了

- 问：我有其他问题
- 答：提供详细问题描述，通过下方 联系方式 反馈问题

## 联系方式
- QQ群组：[211414032](https://jq.qq.com/?k=QU1xGLEB)
### 时雨🌌星空
- GitHub：[TimeRainStarSky](https://github.com/TimeRainStarSky)
- 酷安：[时雨丶星空](http://www.coolapk.com/u/2650948)
- QQ：[2536554304](https://qm.qq.com/cgi-bin/qm/qr?k=x8LtlP8vwZs7qLwmsbCsyLoAHy7Et1Pj)
- Telegram：[TimeRainStarSky](https://t.me/TimeRainStarSky)

## 界面展示
[![主界面](https://cdn.jsdelivr.net/gh/TimeRainStarSky/TRSS_Sagiri@main/Picture/Main.png)](https://github.com/TimeRainStarSky/TRSS_Sagiri)
[![Mirai](https://cdn.jsdelivr.net/gh/TimeRainStarSky/TRSS_Sagiri@main/Picture/Mirai.png)](https://github.com/iTXTech/mirai-console-loader)
[![Sagiri](https://cdn.jsdelivr.net/gh/TimeRainStarSky/TRSS_Sagiri@main/Picture/Sagiri.png)](https://sagiri-kawaii.github.io/sagiri-bot)

## 赞助支持
- 爱发电：<https://afdian.net/@TimeRainStarSky>
- Partme：<https://partme.com/TimeRainStarSky>