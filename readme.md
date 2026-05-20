<div align="center">
  <h1>🀄 大马三人麻将 & Lami 记账器</h1>
  <p><i>The Ultimate MY Board Game Tracker. A dual-language, mobile-first Web App with casino-grade animations and advanced scoring logic.</i></p>
  
  <a href="https://winmjlm.pages.dev"><strong>🔥 LIVE VIEW: winmjlm.pages.dev 🔥</strong></a><br><br>

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/Zero--Build-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="Zero Build">
  
  <br>
  
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" alt="PWA Ready">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/License-Non--Commercial-red?style=for-the-badge" alt="License">

  <br><br>

  <img src="https://img.shields.io/github/last-commit/yikchun1234/mahjonglamitracker?style=for-the-badge" alt="Last Commit">
  <img src="https://img.shields.io/github/repo-size/yikchun1234/mahjonglamitracker?style=for-the-badge" alt="Repo Size">
</div>

---

### ✨ 核心功能 (Core Features)

* 🌐 **Bilingual Interface:** Instantly toggle between English (EN) and 中文 (ZH).
* 🌙 **Casino-Grade UI:** Beautiful Light/Dark mode with 3D tile-flip animations (`@keyframes tileFlip3D`), a V2 Audio Engine for satisfying sound effects, and a V2 Canvas Confetti celebration engine.
* 💾 **Smart Auto-Save & Resume:** State is perfectly saved in `LocalStorage`. If you accidentally close the app, the "Smart Resume" modal will prompt you to pick up exactly where you left off.
* 🛡️ **Advanced Security (Domain Lockdown):** Built-in Anti-Debugger, Inspect Element blockers, and Domain Validation to prevent unauthorized cloning or cheating.

#### 🀄 三人麻将 (3-Player Mahjong)
* **Automated Scoring:** Instantly calculates Zimo (自摸), Dian Pao (出冲), Bao Pai (包牌), and Zha Hu (诈胡). 
* **Smart Hu Wei (虎尾):** Automatically voids Fan (番) and calculates only Fei (飞) when necessary (e.g., Draws, Zha Hu, or when the winner hits Max 10-Fan).
* **Instant Payments (即时收钱):** Click-to-claim buttons for Ming Gang (明杠), An Gang (暗杠), and Jia Gang (加杠).
* **🎰 Custom Jackpot System:** Optional pool where players contribute a set amount each round. The winner sweeps the entire pool upon hitting a Max-Fan (10) or Bao Pai!

#### 🃏 Lami (拉米)
* **Standard & Kosong Mode:** Automatically calculates payouts for Da, Er, San, and Joker differences. Toggle "Kosong" (Direct Win) for a sweep.
* **No Straight Penalty (无顺子起手):** Built-in rule to penalize players with a "+RM 1" extra payout to the winner if they start with no straights.

#### 💸 Advanced Custom Transfer (高级自由转账)
* A bank-style UI (`Payer ➡️ Payee`) for custom transactions. 
* Supports 1-to-1 transfers, 1-to-All (e.g., Custom Zimo/Bao), and All-to-1 scenarios with intelligent conflict prevention.

---

### 🚀 Zero-Build Setup

This application is incredibly lightweight and requires no backend servers or build tools.

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser.

> [!WARNING]
> **Domain Security Lock:** For security purposes, this application is domain-locked. If you wish to host it yourself, you must add your domain to the `allowedDomains` array in the `index.html` file, otherwise it will trigger an Unauthorized Error.

---

### 📱 手机端“添加到主屏幕” (PWA Setup)

For the best borderless experience, install it directly to your phone:
* **iOS (Safari):** Tap the **Share** icon at the bottom of the screen and select **"Add to Home Screen"**.
* **Android (Chrome):** Tap the browser menu (⋮) at the top right and select **"Add to Home screen"**.

---

### 📄 License & Usage (版权与使用协议)

* **仅供个人使用 (Non-Commercial Use Only):** 本项目严格仅供个人娱乐、学习与非商业用途。严禁将此应用或其源代码用于商业盈利、赌场运营或任何形式的赌博业务。<br>*(This project is strictly for personal and non-commercial use. You may not use this application for casino operations or monetized gambling businesses.)*
* **分发与署名 (Forks & Attribution):** 欢迎 Fork 或修改代码用于您自己的个人项目！但如果您公开分享修改后的版本，**必须提供原作者署名** (Amos) 并附带指向本 GitHub 仓库的直接链接。<br>*(You are welcome to fork and modify this code! However, if you share your version publicly, **you must provide proper citation** to the original author (Amos) and include a direct link back to this repository.)*

---

<div align="center">
  <b>Designed and Developed by Amos © 2026</b><br>
  <i>告别纸笔，轻松打牌。</i>
</div>
