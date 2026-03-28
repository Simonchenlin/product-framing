---
name: product-framing
description: Use when starting a new product or feature, before writing any code - helps systematically uncover requirements through guided questioning
---

# Product Framing Skill

## Overview

A systematic questioning framework to help discover and structure product requirements before implementation. Based on the principle that "what you don't ask, you don't get."

## When to Use

- Starting a new product or major feature
- Requirements are vague or incomplete
- Transitioning from idea to implementation
- Need to align stakeholders on scope

**Do NOT use when:**
- Requirements are already fully documented
- User explicitly wants implementation only
- Simple bug fix or minor feature

## Core Framework: Six Discovery Phases

### Phase 1: Business Context (业务理解)

**Key Questions:**
1. 这个产品/功能是**做什么用的**？解决什么问题？
2. 当前是什么**行业和领域**？
3. 有哪些需要这个产品管理的**核心业务**？
4. **目标用户**是谁？他们的痛点是什么？

**Output:** Product vision statement (1-2 sentences)

---

### Phase 2: User Roles & Permissions (角色与权限)

**Key Questions:**
1. 有哪些**角色**会使用这个系统？
2. 每个角色的**核心功能**是什么？
3. 角色之间的**权限关系**如何？
4. 是否有**特殊权限**或数据隔离需求？

**Output:** Role matrix table

---

### Phase 3: Core Modules & Flows (核心功能模块)

**Key Questions:**
1. 主要的**功能模块**有哪些？
2. 模块之间的**关系和依赖**是什么？
3. 核心**业务流程**是什么？
4. 有哪些**关键流程分支**？
5. 异常流程如何处理？

**Output:** Module breakdown + critical flows

---

### Phase 4: Data Model (数据与实体)

**Key Questions:**
1. 需要管理哪些**核心实体**？
2. 每个实体的**关键属性**有哪些？
3. 实体之间的**关系**是什么？
4. 是否有**附件或文件**需求？
5. 数据的**生命周期**是什么？

**Output:** Entity relationship overview

---

### Phase 5: Integration & Boundaries (边界与集成)

**Key Questions:**
1. 需要**对接哪些外部系统**？
2. **边界条件**是什么？（规模、性能、并发）
3. 是否有**特殊场景**需要处理？
4. **导入/导出**需求？
5. **通知/消息**机制？

**Output:** Integration points + constraints

---

### Phase 6: Acceptance Criteria (验收标准)

**Key Questions:**
1. 如何**验证**产品成功？
2. **上线标准**是什么？
3. 需要哪些**文档和培训材料**？
4. 如何**迭代优化**？

**Output:** Acceptance criteria document

---

## Quick Reference Checklist

```
□ 产品背景：解决什么问题？
□ 目标用户：谁会用？多少人会用？
□ 核心模块：模块列表和关系
□ 角色权限：至少3个核心角色
□ 业务流程：关键流程图
□ 数据实体：核心表结构
□ 集成需求：外部系统对接
□ 边界条件：规模/性能/并发
□ 验收标准：上线checklist
□ 风险点：已知风险和应对
```

## Common Mistakes

| Mistake | Why It Matters |
|---------|----------------|
| 跳过Phase 1直接进入功能列表 | 没有方向感，后续决策容易偏离核心价值 |
| 不问边界条件 | 上线后才发现性能/规模问题 |
| 不确认角色权限 | 开发一半发现权限设计冲突 |
| 不问验收标准 | 交付时双方认知不一致 |

## Output Templates

### Product Vision Template
```
[产品名称]是一个[产品类型]，帮助[目标用户]解决[核心问题]。
核心价值：[1-2句话描述差异化价值]
```

### Module Breakdown Template
```
模块名称：
- 职责：
- 依赖：
- 关键接口：
```

## Usage Example

**User:** "我想做一个库存管理系统"

**Assistant (using this skill):**
"好的，让我们一步步梳理清楚。先从Phase 1开始：

**Phase 1 - 业务理解：**
1. 这个库存管理系统是做什么用的？解决什么问题？
2. 是什么行业/领域的库存管理？
3. 有哪些核心业务需要管理？（采购？销售？生产？）
4. 目标用户是谁？仓库管理员？财务？采购员？"

[继续逐步引导，直到完成所有phase]
