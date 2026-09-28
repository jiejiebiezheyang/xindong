<div align="center">

# 🎁 Xindong · Blind Box Simulator

**English** | [简体中文](README.zh-CN.md)

A single-file, dependency-free web app for blind-box draw simulation, probability
analysis and Monte Carlo estimation — open `index.html` and start pulling.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)](.)
[![Single File](https://img.shields.io/badge/build-none-blueviolet)](.)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![GitHub stars](https://img.shields.io/github/stars/jiejiebiezheyang/xindong?style=flat&logo=github)](https://github.com/jiejiebiezheyang/xindong/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/jiejiebiezheyang/xindong?style=flat&logo=github)](https://github.com/jiejiebiezheyang/xindong/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/jiejiebiezheyang/xindong)](https://github.com/jiejiebiezheyang/xindong/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/jiejiebiezheyang/xindong)](https://github.com/jiejiebiezheyang/xindong)

</div>

---

## ✨ Features

### 📊 Stats Dashboard

- **Total Draws** — cumulative number of pulls
- **Total Spent** — currency consumed by every draw
- **Total Income** — total rewards earned from pulls
- **Net Profit / Loss** — income minus spending, updated in real time

### 🎰 Draw System

- **Multiple Schemes** — basic, 3×, 4× and 5× probability distributions
- **Clear Odds Table** — each prize's probability and reward value at a glance
- **Draw Buttons** — single draw, 10-pull and 50-pull (15 units per draw)

### 🔮 Daily Fortune

- A deterministic daily "luck" score derived from the date and time
- Shows the fortune level, contributing factors and a playful suggestion
- _For entertainment only — please pull responsibly._

### 🎮 Monte Carlo Simulation

- Estimates how many draws are needed to obtain the rare **Fantasy Castle**
- Reports sample mean, best / worst case, median and theoretical expectation
- Live progress bar while the simulation runs

### 🎨 Interface

- Clean [shadcn/ui](https://ui.shadcn.com/)-inspired design tokens
- Responsive layout that adapts from mobile to desktop
- Smooth animations for comfortable interaction

## 🚀 Quick Start

No build step, no install. Just open the file in your browser:

```bash
git clone https://github.com/jiejiebiezheyang/xindong.git
cd xindong
# Open index.html in your browser
```

> Tip: you can also serve it locally with any static server, e.g. `npx serve .`.

## 🎯 Usage

1. **Pick a scheme** — choose the 1× / 3× / 4× / 5× probability plan from the sidebar.
2. **Check the odds** — review each prize's probability and reward in the distribution table.
3. **Draw** — use single / 10-pull / 50-pull; every draw costs 15 units.
4. **Watch your balance** — the top metrics track draws, spending, income and net profit.
5. **Run a simulation** — estimate the expected draws for the Fantasy Castle via Monte Carlo.
6. **Reset** — clear the current session's data at any time.

## � Probability Model

Each scheme defines a distribution over seven prizes. The basic (1×) scheme:

| Prize                 | Probability | Reward |
| :-------------------- | ----------: | -----: |
| 🏰 Fantasy Castle     |       0.04% |   2233 |
| 🔮 Mystic Charm       |       0.08% |    200 |
| 💎 Time-Space Diamond |       0.12% |    100 |
| 🪄 Rainbow Wand       |        3.7% |     40 |
| � Sweetheart Doll     |      45.56% |     16 |
| 🍬 Rainbow Candy      |       44.5% |      9 |
| 🎟️ Movie Ticket       |          6% |      2 |

At the basic rate, the theoretical expectation for the Fantasy Castle is
`1 / 0.0004 = 2500` draws.

## 📦 Project Structure

```text
xindong/
├── index.html      # Single-page app (HTML + CSS + JS)
├── favicon.svg     # Site icon
├── LICENSE         # MIT License
├── README.md       # Documentation (English)
└── README.zh-CN.md # Documentation (简体中文)
```

## �️ Tech Stack

- Native **HTML5 / CSS3 / JavaScript** — no framework, no bundler
- **No backend** and **no runtime dependencies**
- Runs entirely in the browser with all state kept in memory

## 📄 License

Released under the [MIT License](LICENSE) © 2026 jiejiebiezheyang.

---

<div align="center">

_Happy pulling! 🎉_

</div>
