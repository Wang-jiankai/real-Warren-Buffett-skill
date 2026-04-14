<!-- badges -->
<div align="center">

![Warren Buffett](https://img.shields.io/badge/Warren-Buffett-FF6B35?style=for-the-badge&logo=buffalo)
![Value Investing](https://img.shields.io/badge/Value-Investing-2E7D32?style=for-the-badge&logo=leaf)
![Claude Code](https://img.shields.io/badge/Claude-Code-7B68EE?style=for-the-badge&logo=robot)

*[English](README_EN.md)*

</div>

---

<div align="center">

# 💰 巴菲特投资分析助手

> *"别人贪婪时恐惧，别人恐惧时贪婪。"* — 沃伦·巴菲特

**基于价值投资理念的智能投资辅助工具**

</div>

---

## ✨ 概览

> ⚠️ **使用前请先配置 WebSearch 权限** — 如果未配置，将无法获取最新股价、财报、业绩等实时数据，分析结果会严重失真！
>
> 在 `settings.json` 中添加：
> ```json
> { "permissions": { "allow": ["WebSearch", "WebFetch"] } }
> ```

基于沃伦·巴菲特价值投资理念打造的 Claude Code 技能助手，提供股票分析、企业评估、投资决策辅助。

---

## 🎯 核心功能

| 功能 | 说明 |
|------|------|
| 🎯 投资哲学与框架 | 护城河、安全边际、能力圈等核心理念 |
| 🏰 企业/股票分析 | 从巴菲特视角审视投资标的 |
| 📊 财务指标解读 | ROE、现金流、债务结构全面分析 |
| 💹 估值方法论 | 内在价值与安全边际评估 |
| 🛡️ 风险评估 | 识别投资陷阱与风险信号 |
| 📋 提问清单 | 系统化分析框架 |

---

## 🚀 快速开始

```bash
# 触发 skill，询问投资问题
/buffett 分析贵州茅台的投资价值
/buffett 分析苹果公司的护城河
/buffett 什么是安全边际
/buffett 怎么判断管理层好不好
/buffett ROE多少算合格
```

---

## 📜 核心理念

### 🏆 四大投资原则

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   🏰 护城河（Moat）                                       │
│      企业抵御竞争对手的持久竞争优势                          │
│                                                         │
│   ⚖️ 安全边际（Margin of Safety）                          │
│      永远用低于内在价值的价格买入                           │
│                                                         │
│   🎯 能力圈（Circle of Competence）                        │
│      只投资你真正理解的行业                                │
│                                                         │
│   👔 优质管理层                                           │
│      诚信、有能力、为股东着想                              │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

### ❌ 三不原则

<div align="center">

| 原则 | 英文 |
|------|------|
| 不投不懂的行业 | Never invest in what you don't understand |
| 不投没有护城河的企业 | Never invest in businesses without moats |
| 不投管理层不可靠的公司 | Never invest with unreliable management |

</div>

---

## 📊 选股标准

### 合格指标

| 指标 | 标准 | 说明 |
|:----:|:----:|------|
| ROE | > 15% | 长期维持，越高越好 |
| ROA | > 10% | 企业资产利用效率 |
| 债务/股权 | < 50% | 债务水平可控 |
| 自由现金流 | 正数且稳定 | 利润的真实检验 |
| 毛利率 | > 40% | 定价权的体现 |
| 派息率 | < 70% | 兼顾股东回报与再投资 |

### 🚫 一票否决项

- ❌ 连续 5 年亏损
- ❌ 管理层有诚信问题
- ❌ 行业前景不明
- ❌ 依赖单一客户/产品 > 30%

---

## 🚦 问题审查机制

> 在回答任何问题前，先审查是否符合巴菲特投资理念

### 将被直接拒绝的问题

| 类型 | 原因 | 巴菲特怎么说 |
|:----:|------|-------------|
| 比特币/加密货币 | 不产生现金流，是投机不是投资 | "比特币不创造任何东西" |
| 杠杆/期权 | 违背保本原则 | "杠杆是把需要的钱去冒险" |
| 能力圈外科技股 | 变化太快，无法预测10年后 | "我不知道微软10年后怎样" |
| 没有护城河的公司 | 低价可能是价值陷阱 | "没有护城河的便宜是陷阱" |
| 宏观预测 | 没人知道，浪费时间 | "我不在乎他们的宏观预测" |
| 时机选择 | 没人能预测市场 | "我从没见过能连续把握时机的人" |

---

## 💬 经典语录

> *"好公司买贵了也比烂公司买便宜强。"*
> *"It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price."*

> *"时间是烂生意的敌人，是好生意的朋友。"*
> *"Time is the enemy of bad businesses and the friend of wonderful businesses."*

> *"不要借钱投资。用不着杠杆也一样能做成大事。"*
> *"Never borrow money. You can do fine without leverage."*

> *"如果你不愿意持有一只股票十年，那就不要考虑持有十分钟。"*
> *"If you aren't willing to own a stock for ten years, don't even think about owning it for ten minutes."*

---

## 📁 文件结构

```
real-Warren-Buffett-skill/
├── SKILL.md                    📖 主技能文件（完整分析框架）
├── README.md                   📝 中文主导版（本文）
├── README_EN.md                📝 English version
└── references/
    ├── questions.md            ❓ 企业分析提问清单
    └── indicators.md           📈 关键财务指标详解
```

---

## 🏛️ 理念来源

- 🏰 **护城河** — Economic Moat
- ⚖️ **安全边际** — Margin of Safety
- 🎯 **能力圈** — Circle of Competence
- ⏳ **长期持有** — Long-term Holding
- 💎 **本分文化** — 段永平

---

## 🔗 链接

<div align="center">

*[English](README_EN.md)*

</div>

---

<div align="center">

*License: MIT*

*"如果你不愿意持有一只股票十年，那就不要考虑持有十分钟。"*

</div>
