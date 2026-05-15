<div align="center">
  <h1>🀄 大马三人麻将 & Lami 记账器</h1>
  <p><i>A mobile-first Web App designed for Malaysian 3-Player Mahjong and Lami scoring. (MY Board Game Tracker)</i></p>
  
  <a href="https://winmjlm.pages.dev"><strong>🔥 LIVE VIEW: winmjlm.pages.dev 🔥</strong></a><br><br>

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" alt="PWA Ready">
</div>

---

一个专为马来西亚本地规则量身打造的手机端网页记账应用。告别传统的纸笔算账，只需点几下，系统自动为你计算所有复杂的“番飞”、“虎尾”、以及“Lami 大中小”的输赢差价！

### ✨ 核心功能 (Core Features)

* 📱 **Mobile-First 设计:** 完美的手机端适配，支持保存到桌面（PWA-like）全屏运行。
* 🌙 **沉浸式体验:** 内置深色/浅色（赌场金黑）主题，搭配 3D 翻转动画与结算音效。
* 🌐 **双语支持:** 一键切换中文 (ZH) 与英文 (EN)。

#### 🀄 三人麻将 (3-Player Mahjong)
* **精准的虎尾 (Hu Wei) 计算:** 自动计算输家之间的“番金”与“飞金”差价。
* **智能防呆机制:** 赢家满番 (10番)、包牌、诈胡、流局时，系统会自动将其他玩家的虎尾番数强制归零（只算飞金），并动态隐藏不需要的输入框，防止手滑填错。
* **独立的 Jackpot 系统:** 支持设置每局入池金额。赢家满番或包牌时，一键自动赢走奖池积累金额。
* **即时收钱 (明杠/暗杠):** 游戏进行中随时记录杠牌，自动计算双倍（出冲）或单倍（自己摸）。

#### 🃏 Lami (拉米)
* **常规结算:** 自动根据玩家剩余牌数名次（大哥、二哥、三哥）分配输赢。
* **Kosong (直接出完) 模式:** 支持赢家一牌未丢直接胡牌，全场按最高额赔付。
* **Joker 差价对咬:** 自动计算全场所有玩家之间的 Joker 数量差价并互相补水。
* **无顺子罚款:** 支持开局无顺子 (No Straight) 起手的额外罚款设定。

#### 💸 自由转账 (高级模式)
颠覆性的转账 UI 设计，采用类似银行 App 的 `[出钱方] ➡️ [收钱方]` 直观面板：
* **明确的方向:** 一目了然的转账流向，并自带 (自摸)、(包牌)、(出完-Kosong) 等智能后缀提示。
* **联动互斥防呆:** 选择“所有人”后，另一侧仅能选择具体玩家，彻底杜绝逻辑冲突。
* **强制重置:** 每次结算后重置为“- 请选择 -”，防止残留上一局的数据。

---

### 🛠️ 数据存储 (Data Storage)
所有对局记录和分数变动都会自动实时保存在浏览器的本地缓存 (**LocalStorage**) 中。
刷新网页、甚至关闭浏览器，下次打开时都会自动提示你是否要“继续未完成的游戏”。想要重新开始，只需点击底部的“⚠️ 结束游戏 (清空所有分数)”即可安全重置。

---

### 📱 手机端“添加到主屏幕” (PWA Setup)
在手机浏览器打开网页后，将其添加到主屏幕即可获得无边框的完美 App 体验：
* **iOS (Safari):** 点击底部中间的 `[分享]` 按钮，下滑选择 **添加到主屏幕** (Add to Home Screen)。
* **Android (Chrome):** 点击右上角的 `[⋮]` 菜单，选择 **添加到主屏幕** (Install App)。

---

### 📄 License & Usage (版权与使用协议)

* **仅供个人使用 (Non-Commercial Use Only):** 本项目严格仅供个人娱乐、学习与非商业用途。严禁将此应用或其源代码用于商业盈利、赌场运营或任何形式的赌博业务。
* **分发与署名 (Forks & Attribution):** 欢迎 Fork 或修改代码用于您自己的个人项目！但如果您公开分享修改后的版本，**必须提供原作者署名** (Amos) 并附带指向本 GitHub 仓库的直接链接。

---

<div align="center">
  <b>Designed and Developed by Amos</b><br>
  <i>告别纸笔，轻松打牌。</i>
</div>
