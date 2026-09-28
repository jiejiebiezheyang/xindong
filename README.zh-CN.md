<div align="center">

# 🎁 心跳 · 盲盒模拟器

[English](README.md) | **简体中文**

一个单文件、零依赖的网页版盲盒抽奖模拟器，支持概率分析与蒙特卡洛估计 —— 打开
`index.html` 即可开始抽奖。

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

## ✨ 功能特性

### 📊 数据统计面板

- **累计抽奖** —— 累计抽取次数
- **累计支出** —— 每次抽奖消耗的货币累计
- **累计收入** —— 抽奖获得奖励的总价值
- **净盈亏** —— 收入减去支出，实时更新

### 🎰 抽奖系统

- **多套倍率方案** —— 基础、3 倍、4 倍、5 倍概率分布
- **清晰的概率表** —— 每个奖品的中奖概率与奖励金额一目了然
- **抽奖操作** —— 单次抽奖、十连抽、五十连抽（每次消耗 15 单位）

### 🔮 今日运势

- 根据日期与时段生成的每日「运势」评分
- 展示运势等级、影响因素与趣味建议
- _仅供娱乐，理性抽奖。_

### 🎮 蒙特卡洛模拟

- 估算抽到稀有奖品 **梦幻城堡** 所需的期望次数
- 输出样本均值、最优 / 最差样本、中位数与理论期望值
- 模拟过程中提供实时进度条

### 🎨 界面设计

- 基于 [shadcn/ui](https://ui.shadcn.com/) 设计令牌的简洁风格
- 响应式布局，适配手机到桌面各种尺寸
- 流畅的动画与舒适的交互反馈

## 🚀 快速开始

无需构建、无需安装，直接用浏览器打开即可：

```bash
git clone https://github.com/jiejiebiezheyang/xindong.git
cd xindong
# 用浏览器打开 index.html
```

> 提示：也可以用任意静态服务器本地预览，例如 `npx serve .`。

## 🎯 使用指南

1. **选择方案** —— 在侧边栏选择 1× / 3× / 4× / 5× 概率方案。
2. **查看概率** —— 在概率分布表中查看各奖品的中奖概率与奖励。
3. **开始抽奖** —— 使用单次 / 十连 / 五十连，每次抽奖消耗 15 单位。
4. **关注盈亏** —— 顶部指标实时统计抽奖次数、支出、收入与净盈亏。
5. **执行模拟** —— 通过蒙特卡洛估算抽到梦幻城堡的期望次数。
6. **重置数据** —— 随时清空当前会话的数据。

## 📈 概率模型

每套方案定义了七个奖品的概率分布。基础（1×）方案如下：

| 奖品        |   概率 | 奖励 |
| :---------- | -----: | ---: |
| 🏰 梦幻城堡 |  0.04% | 2233 |
| 🔮 神秘护符 |  0.08% |  200 |
| 💎 时空钻石 |  0.12% |  100 |
| 🪄 彩虹魔杖 |   3.7% |   40 |
| 🧸 甜心玩偶 | 45.56% |   16 |
| 🍬 彩虹糖   |  44.5% |    9 |
| 🎟️ 观影券   |     6% |    2 |

在基础倍率下，梦幻城堡的理论期望为 `1 / 0.0004 = 2500` 次抽奖。

## 📦 项目结构

```text
xindong/
├── index.html      # 单页应用（HTML + CSS + JS）
├── favicon.svg     # 网站图标
├── LICENSE         # MIT 许可证
├── README.md       # 文档（English）
└── README.zh-CN.md # 文档（简体中文）
```

## 🛠️ 技术栈

- 原生 **HTML5 / CSS3 / JavaScript** —— 无框架、无打包工具
- **无后端**、**无运行时依赖**
- 完全运行在浏览器中，状态保存在内存里

## 📄 许可证

本项目基于 [MIT 许可证](LICENSE) 发布 © 2026 jiejiebiezheyang。

---

<div align="center">

_祝你好运，抽卡愉快！🎉_

</div>
