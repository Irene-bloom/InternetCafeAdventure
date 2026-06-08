# 不夜城网吧：通宵纪行 · CyberCafé: All-Night

> 凌晨的网吧，最后一盏屏幕还亮着。刷卡开机，在天亮之前破解核心、带着数据消失在黎明——别让防火墙抓到你。
>
> *A neon-noir, all-night heist platformer. Boot up, hack the cores, and vanish into the dawn before the firewall catches you.*

🎮 **在线试玩 / Play now:** https://irene-bloom.github.io/InternetCafeAdventure/

---

## 玩法 · How to Play

**目标**：在 **90 秒天亮倒计时**内解密 **5 个核心**，触发「数据已窃取」后全速逃离机房，带着核心数据消失在黎明。被防火墙拦截即任务失败。

| 操作 | 按键 |
| --- | --- |
| 左右移动 | `←` `→` 或 `A` `D` |
| 跳跃 | `↑` 或 `空格 Space` |
| 开始游戏 | 点击「刷卡开机」 |

- 🥤 **红牛补给（0 / 6）**：沿途收集，为通宵续航。
- 🔓 **解密核心（0 / 5）**：集齐即触发逃脱阶段。
- ⏱ **天亮倒计时（90s）**：时间归零，夜就结束了。
- ⚠️ **被防火墙拦截** → `SYSTEM ERROR`，入侵失败，点「重连内网」重来。
- ✅ **DATA SECURED** → 你带着核心数据消失在黎明，*通宵纪行 · 完*。

---

## 特色 · Features

- **赛博 noir 美学**：霓虹光感 + 噪点质感的不夜城网吧氛围。
- **两阶段玩法**：潜入解密 → 数据窃取后的全速逃脱，节奏有张力。
- **倒计时压迫感**：90 秒天亮限时，逼出操作与路线规划。
- **纯前端，零依赖**：打开浏览器即玩，无需安装。
- **移动端适配**：响应式 viewport，手机也能跑。

---

## 技术栈 · Tech Stack

- HTML5 Canvas
- 原生 JavaScript（无框架、无构建步骤）
- CSS
- 部署于 GitHub Pages

> 单页纯前端项目，所有逻辑在浏览器端运行。

---

## 本地运行 · Run Locally

```bash
# 克隆仓库
git clone https://github.com/Irene-bloom/InternetCafeAdventure.git
cd InternetCafeAdventure

# 方式一：直接用浏览器打开 index.html 即可

# 方式二：起一个本地服务器（推荐，避免部分浏览器的本地文件限制）
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

---

## 部署 · Deployment

项目通过 **GitHub Pages** 部署：仓库 `Settings → Pages → Source` 选择主分支，几分钟后即可通过
`https://irene-bloom.github.io/InternetCafeAdventure/` 访问。

---

## 关于 · About

由 **Vesper（[@Irene-bloom](https://github.com/Irene-bloom)）** 设计与开发。
一个关于通宵、霓虹与黎明的小实验。

*Bring ideas to life.* 🌙
