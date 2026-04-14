# Warren Buffett Investment Skill
巴菲特投资分析助手

> *"别人贪婪时恐惧，别人恐惧时贪婪。"* — 沃伦·巴菲特
> *"Be fearful when others are greedy, and greedy when others are fearful."* — Warren Buffett

---

## Overview | 概览

A Claude Code skill powered by Warren Buffett's value investment philosophy. Provides comprehensive analysis of stocks, businesses, and investment decisions.

基于沃伦·巴菲特价值投资理念打造的 Claude Code 技能助手。提供股票分析、企业评估、投资决策辅助。

---

## Features | 功能

| Feature | 功能 |
|---------|------|
| 🎯 Investment Philosophy & Framework | 投资哲学与框架 |
| 🏰 Business/Stock Analysis | 企业/股票分析辅助 |
| 📊 Financial Indicators | 财务指标解读 |
| 💹 Valuation Methodology | 估值方法论 |
| 🛡️ Risk Assessment | 风险评估 |
| 📋 Question Checklist | 提问清单 |

---

## Quick Start | 快速开始

```bash
# Trigger the skill by asking investment questions
/buffett 分析贵州茅台的投资价值
/buffett 分析苹果公司的护城河
/buffett 什么是安全边际

# Ask about specific concepts
/buffett 怎么判断管理层好不好
/buffett ROE多少算合格
```

---

## Core Principles | 核心理念

### 四大投资原则 | Four Investment Principles

1. **护城河 (Moat)** — Durable competitive advantage
2. **安全边际 (Margin of Safety)** — Buy below intrinsic value
3. **能力圈 (Circle of Competence)** — Only invest in what you understand
4. **优质管理层 (Quality Management)** — Honest, capable, shareholder-focused

### 三不原则 | Three-Never Principles

- ❌ **不投不懂的行业** — Never invest in what you don't understand
- ❌ **不投没有护城河的企业** — Never invest in businesses without moats
- ❌ **不投管理层不可靠的公司** — Never invest with unreliable management

---

## File Structure | 文件结构

```
real-Warren-Buffett-skill/
├── SKILL.md                    # Main skill file (巴菲特投资框架)
├── README.md                   # This file
├── README_EN.md                # English version
└── references/
    ├── questions.md            # Enterprise analysis checklist (企业分析清单)
    └── indicators.md            # Key financial indicators (关键财务指标)
```

---

## Investment Criteria | 选股标准

| Indicator | 指标 | Standard | 标准 |
|-----------|------|---------|------|
| ROE | 净资产收益率 | > 15% | 长期维持，越高越好 |
| ROA | 资产收益率 | > 10% | 企业资产利用效率 |
| Debt/Equity | 债务股权比 | < 50% | 债务水平可控 |
| Free Cash Flow | 自由现金流 | Positive & Stable | 正数且稳定 |
| Gross Margin | 毛利率 | > 40% | 定价权的体现 |
| Payout Ratio | 派息率 | < 70% | 兼顾回报与再投资 |

### Deal Breakers | 一票否决项

- ❌ 连续 5 年亏损
- ❌ 管理层有诚信问题
- ❌ 行业前景不明
- ❌ 依赖单一客户/产品 > 30%

---

## Question Screening | 问题审查

Before answering, the skill screens questions. **These will be refused:**

| Type | 类型 | Reason | 原因 |
|------|------|--------|------|
| Bitcoin/Crypto | 比特币/加密货币 | No cash flow, pure speculation | 不产生现金流 |
| Leverage/Derivatives | 杠杆/期权 | Risk of losing principal | 违背保本原则 |
| Tech Stocks (outside circle) | 能力圈外科技股 | Can't predict 10 years out | 无法预测10年后 |
| No-Moat Companies | 没有护城河的公司 | Value traps | 低价可能是陷阱 |
| Macro Prediction | 宏观预测 | Nobody knows | 没人知道 |
| Market Timing | 时机选择 | Can't predict markets | 没人能预测 |

---

## Quote Highlights | 经典语录

> *"投资最重要的三个词：护城河、安全边际、能力圈。"*
> *"The three most important words in investing: moat, margin of safety, circle of competence."*

> *"好公司买贵了也比烂公司买便宜强。"*
> *"It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price."*

> *"时间是烂生意的敌人，是好生意的朋友。"*
> *"Time is the enemy of bad businesses and the friend of wonderful businesses."*

> *"不要借钱投资。用不着杠杆也一样能做成大事。"*
> *"Never borrow money. You can do fine without leverage."*

---

## Wisdom from Duan Yongping | 段永平补充智慧

### 三句话 | Three Principles

- **胸无"大"志** — 脚踏实地做喜欢的事
- **有所不为** — 知道什么不能做
- **做个正直的人** — Be an honest person

### 本分 | Benfen

> "本分就是说话算数，承诺要兑现。"
> *"Benfen means keeping your word and honoring commitments."*

---

## Inspired By | 理念来源

- 护城河 (Moat)
- 安全边际 (Margin of Safety)
- 能力圈 (Circle of Competence)
- 长期持有 (Long-term Holding)
- 本分文化 (Benfen Culture)

---

## License | 许可证

MIT License - 麻省理工学院许可证

---

*"如果你不愿意持有一只股票十年，那就不要考虑持有十分钟。"*
*"If you aren't willing to own a stock for ten years, don't even think about owning it for ten minutes."*
