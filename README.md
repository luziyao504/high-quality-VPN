# 科学上网工具合集 — 高质量开源项目与实用站点

> 整理一圈圈子里口碑不错的代理工具、客户端和实用网站，全部以开源项目为主，不堆垃圾机场。

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📌 这些是干什么的

下面整理的不是"买哪个机场"，而是**科学上网这件事背后真正硬核的开源项目和工具站**。圈子里能用的东西其实就这几类：

**一类是代理协议核心**——跑在服务器上的那一端，负责把你的流量加密、伪装、加速。主流的有 Xray（V2Ray 的加强分支）、Hysteria2（基于 QUIC 的 UDP 加速，晚高峰最稳）、sing-box（新一代通用代理平台，协议全支持）。这些都是 GitHub 上几千上万星的开源项目，自己有服务器就能搭。

**一类是客户端**——装在自己电脑或手机上的那一端，负责把系统流量导进代理通道。Windows 上现在主流是 **Clash Verge Rev**（Mihomo 内核的图形化客户端，界面最现代）和 **v2rayN**（老牌、协议全）；Mac 上用 **ClashX Meta** 或 **Stash**；iOS 上是 **Shadowrocket（小火箭）** 和 **Loon**；安卓是 **Clash for Android** 和 **v2rayNG**。

**一类是配套实用网站**——搭好之后用来测速度、查 DNS 泄露、看自己出口 IP 的工具站。这些站本身不用翻墙也能访问，但在排查问题的时候天天会用到。

## 🎯 怎么选

- **追求稳、不在乎折腾**：直接用 Hysteria2 协议 + Clash Verge 客户端，晚高峰不卡
- **想自己搭、有服务器**：选 Xray 或 sing-box，协议随便切
- **iOS 用户**：Shadowrocket 是绕不开的，App Store 外区买
- **移动端临时用**：v2rayNG（安卓）和 Streisand（iOS 新出的免费客户端）都不错

---

## 📊 速览表

### 🔧 代理协议 / 核心项目（服务器端）

| 项目 | 地址 | 特点 |
|---|---|---|
| Xray-core | [github.com/XTLS/Xray-core](https://github.com/XTLS/Xray-core) | V2Ray 加强分支，XTLS 抗封锁最强，圈子主力 |
| sing-box | [github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box) | 新一代通用代理平台，全协议支持，跨平台 |
| Hysteria | [github.com/apernet/hysteria](https://github.com/apernet/hysteria) | 基于 QUIC 的 UDP 加速，丢包环境下最稳 |
| Shadowsocks-rust | [github.com/shadowsocks/shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) | 经典 SS 协议的 Rust 重写版，轻量 |
| Trojan | [github.com/trojan-gfw/trojan](https://github.com/trojan-gfw/trojan) | 伪装成普通 HTTPS 网站，低调试用 |
| naiveproxy | [github.com/klzgrad/naiveproxy](https://github.com/klzgrad/naiveproxy) | 完全模拟 Chrome 浏览器流量，最难识别 |

### 🖥 客户端（自己设备上装）

| 客户端 | 平台 | 地址 / 说明 |
|---|---|---|
| Clash Verge Rev | Win / Mac / Linux | [github.com/clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev) —— 现在最推荐的图形客户端 |
| v2rayN | Windows | [github.com/2dust/v2rayN](https://github.com/2dust/v2rayN) —— 老牌全能 |
| v2rayNG | Android | [github.com/2dust/v2rayNG](https://github.com/2dust/v2rayNG) —— 安卓主力 |
| Shadowrocket | iOS | App Store 外区购买，俗称"小火箭" |
| Streisand | iOS | [github.com/StreisandEffect/streisand](https://github.com/StreisandEffect/streisand) —— 新出的免费开源 iOS 客户端 |
| ClashX Meta | macOS | [github.com/MetaCubeX/ClashX.Meta](https://github.com/MetaCubeX/ClashX.Meta) |
| Mihomo Party | 全平台 | [github.com/mihomo-party-org/mihomo-party](https://github.com/mihomo-party-org/mihomo-party) —— Mihomo 内核新客户端 |

### 🌐 实用工具网站（排查问题用）

| 网站 | 地址 | 用途 |
|---|---|---|
| Fast.com | [fast.com](https://fast.com) | Netflix 测速，看真实出口带宽 |
| Speedtest | [speedtest.net](https://www.speedtest.net) | 经典测速，选节点测延迟 |
| DNS Leak Test | [dnsleaktest.com](https://dnsleaktest.com) | 查 DNS 是否泄露，代理是否生效 |
| ipleak.net | [ipleak.net](https://ipleak.net) | 看出口 IP、DNS、WebRTC 泄露 |
| whoer.net | [whoer.net](https://whoer.net) | 综合匿名度评分 |
| itdog.cn | [itdog.cn](https://www.itdog.cn) | 国内站长工具，全国节点 ping / 路由追踪 |
| boce.com | [boce.com](https://www.boce.com) | 国内多地区 ping 检测 |

### 🌐 高质量机场

| 网站 | 网址 | 备注 |
|---|---|---|
| CyberGuard | [cyberguard.top](https://cyberguard.top/#/register?code=PgVpysvG) | 需要外网访问 |

---

## ⚠️ 几点提醒

1. **别迷信"免费机场"**——免费的要么限速到没法用，要么记录你流量卖广告，长期用要么自己搭要么挑口碑稳的付费。
2. **自己搭 > 买现成**——有一台境外 VPS（搬瓦工、Vultr、RackNerd 这类），用 Xray 或 Hysteria2 一键脚本 5 分钟搞定，自由度最高。
3. **协议选新不选旧**——SS 老协议已经很容易被识别，优先选 VLESS+Reality 或 Hysteria2。
4. **定期换节点、换端口**——别一个节点用半年不动，封了才想起来换就晚了。

---

<p align="center">
工具是开源的，用法看自己需求。觉得有用去 GitHub 给这些项目点个 ⭐️
</p>
