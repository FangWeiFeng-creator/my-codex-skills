---
name: xiaodao-economics
description: |
  用《小岛经济学》的生产率、储蓄、贷款、货币、贸易与危机分析回答和规划问题；先识别本书模型与作者立场，再给出可检查的条件和边界。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.xiaodao-economics
  cangjie.capability-count: 9
  cangjie.entrypoint-count: 1
---
# 小岛经济学 — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 现实投资、信贷、税务、法律或医疗建议
- 其他书籍的融合蒸馏或跨书知识合并
- 把书中人物的政治评价当作已被独立统计证明的事实

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 真实产出、储蓄和资本回报是判断增长的基础，名义支出不等于产能提高。
2. 贷款要按用途、资金来源、未来产出和失败损失分类，不能只看借款意愿。
3. 货币与价格必须分层；作者的通胀定义、现实统计和待核事实要分开。
4. 贸易和外部储蓄要同时追踪商品流、资金流和未来偿付关系。
5. 危机后的援助、退出和重组各有成本；必须标明受益者和损失承担者。
6. 本书是寓言式论证，不能替代现代统计、制度分析或专业建议。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 解释经济增长的来源；评估储蓄、资本和生产率；判断投资是否扩大产出 | references/capabilities/productive-capital-growth.md | references/capabilities/loan-purpose-triage.md、references/capabilities/investment-cost-benefit.md、references/capabilities/money-price-diagnosis.md |
| 判断一笔贷款该不该借或贷；比较商业、消费、应急贷款；审查还款来源和担保 | references/capabilities/loan-purpose-triage.md | references/capabilities/productive-capital-growth.md、references/capabilities/savings-interest-investment.md、references/capabilities/credit-bubble-mechanism.md |
| 解释低利率或高利率；判断降息是否刺激投资；识别利率扭曲 | references/capabilities/savings-interest-investment.md | references/capabilities/loan-purpose-triage.md、references/capabilities/credit-bubble-mechanism.md、references/capabilities/money-price-diagnosis.md |
| 判断一个说法是不是通货膨胀；解释价格下降或购买力变化；区分CPI和货币供应 | references/capabilities/money-price-diagnosis.md | references/capabilities/savings-interest-investment.md、references/capabilities/trade-external-balance.md、references/capabilities/credit-bubble-mechanism.md |
| 分析贸易逆差或顺差；解释分工和比较优势；追踪外国储蓄和储备货币 | references/capabilities/trade-external-balance.md | references/capabilities/money-price-diagnosis.md、references/capabilities/credit-bubble-mechanism.md、references/capabilities/crisis-reallocation.md |
| 分析房价或资产价格上涨；判断政府担保贷款的风险；梳理再融资和杠杆 | references/capabilities/credit-bubble-mechanism.md | references/capabilities/loan-purpose-triage.md、references/capabilities/savings-interest-investment.md、references/capabilities/crisis-reallocation.md |
| 比较援助、刺激和退出；分析危机后的失业与资产价格；判断债务如何处理 | references/capabilities/crisis-reallocation.md | references/capabilities/credit-bubble-mechanism.md、references/capabilities/trade-external-balance.md、references/capabilities/money-price-diagnosis.md |
| 评估基础设施或设备项目；比较投资方案；判断就业创造能否证明项目 | references/capabilities/investment-cost-benefit.md | references/capabilities/productive-capital-growth.md、references/capabilities/loan-purpose-triage.md、references/capabilities/crisis-reallocation.md |
| 分析工资和技能价值；选择学徒、借款买设备或打工；制定收入提升实验 | references/capabilities/labor-value-wage.md | references/capabilities/loan-purpose-triage.md、references/capabilities/productive-capital-growth.md、references/capabilities/investment-cost-benefit.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 缺少产出、成本、现金流或时间等关键输入，无法进行有意义的判断时，先列出缺口，不猜值。
- 用户要求现实统计或多国宏观结论，而当前材料未提供可核验数据时，标明需要更新资料并停止外推。
- 用户要求具体买卖、贷款批准或政策执行决定时，只提供书内分析框架，交由有权限的专业角色处理。
