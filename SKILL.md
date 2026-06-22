---
name: paper-review-methodology
slug: paper-review-methodology
version: 1.1.0
displayName: 学术论文全面审查方法论
summary: 29类审查方法按7大体系组织，含脱敏筛查，覆盖论文全生命周期从宏观评估到逐段执行
description: |
  Comprehensive academic paper review methodology with 29 review categories across 7 systems.
  Covers: full-paper review, version comparison, figure/table citation audit, AI-language purification,
  data authenticity verification, reference cross-checking, illustration feasibility analysis,
  abstract symmetry check, module consistency audit, architecture conflict analysis,
  requirement fulfillment audit, P0-P3 severity grading, desensitization review, and scoring.
  
  学术论文全面审查方法论，29类审查方法按7大体系组织（含脱敏筛查）。
  触发词：审查论文、论文评审、方法论审查、版本对比、图文检查、AI检测、数据验证、P0/P1/P2/P3分级、论文评分、脱敏筛查。
  English triggers: paper review, thesis review, methodology review, version comparison, figure audit,
  AI detection, data verification, P0-P3 grading, paper scoring, desensitization review.
---

# 学术论文全面审查方法论（Paper Review Methodology）

29类独立审查方法论，覆盖学术论文从宏观评估到逐段执行的完整审查链条。

## 快速导航

本技能按7大体系组织，每体系对应一个reference文件：

| 体系 | 包含方法 | 参考文件 |
|------|---------|---------|
| 一、宏观评估 | #1 四维度评估 #2 评分追踪 #3 19项审视法 #4 三级专家审查 | `references/macro-assessment.md` |
| 二、问题分级 | #5 P0-P3分级 #6 硬伤/软伤分类 #7 数据涟漪效应 | `references/problem-grading.md` |
| 三、专项审查 | #8-15 插图/图文/图题/AI语言/模块/段落归属/涟漪扫描 | `references/specialized-review.md` |
| 四、结构对比 | #16 架构冲突 #17 版本交叉引用 #18 双版本对比 | `references/structural-comparison.md` |
| 五、数据合规 | #19 数据真实性 #20 双抱归因 #21 摘要对称 #22 参考文献 #23 脱敏筛查 | `references/data-compliance.md` |
| 六、需求审计 | #24 14项决策 #25 7条专家需求 #26 安全底本策略 | `references/requirement-audit.md` |
| 七、执行方法 | #27 修改清单 #28 逐段比对 #29 P0逐项修正 | `references/execution-methods.md` |

## 典型话术模式

### 开篇句式
- 「以xxx身份审查/审阅xxx」
- 「从xxx维度对xxx进行系统性审查」
- 「发现xxx项问题：P0级x项/P1级x项/P2级x项/P3级x项」

### 评判句式
- 「该问题的性质是xxx」「严重程度为P0级」
- 「推荐方案A（xxx），替代方案B（xxx）」
- 「这一发现与前文xxx形成交叉验证」
- 「三个维度均不合格 → 建议xxx」

### 收束句式
- 「审查完成。核心结论：xxx」
- 「修正硬伤后预计：xx-xx分」
- 「等待用户确认/下达修改指令后执行」
- 「综合评分：X维度的加权总分」

### 自纠机制
- 「撤销：1项（AI痕迹过度敏感，撤销判定）」
- 「降级：1项（长句→P3，不作为独立修改项）」
- 「此前的xxx判定有误，现更正为xxx」

## 审查流程建议

1. **首轮** → 四维度评估 + P0-P3分级 + AI语言审查框架 → 确定整体质量和优先级
2. **专项轮** → 插图引用审查 + 参考文献比对 + 中英文摘要对称 + 模块一致性
3. **数据轮** → 数据真实性验证 + 双抱归因分析 + 脱敏筛查 + 全文涟漪扫描
4. **对标轮** → 版本交叉引用审计 + 决策/需求满足度审计
5. **终审轮** → P0逐项修正审计 + 逐段比对 + 评分追踪

## 评分公式

加权评分：内容完整性×0.3 + 逻辑完整性×0.25 + 逻辑闭环×0.25 + AI检测评估×0.2

优质线：85分（具备送审条件）
