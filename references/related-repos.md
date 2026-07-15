# 相关GitHub仓库

本项目整合了以下开源项目：

## 核心依赖项目

### 1. CEOskill
**描述**: CEO决策支持技能，提供结构化决策框架  
**仓库**: https://github.com/AIPMAndy/CEOskill  
**关系**: Andy Product Skill的CEO决策框架来源  
**核心功能**:
- 决策类型分类（Type 1/2/危机/战略赌注）
- 结构化决策流程
- 去偏见检查
- War Gaming（竞争模拟）
- Stakeholder Mapping（利益相关方分析）

### 2. teach-rd-product-handbook
**描述**: 让研发具备产品意识的开源训练体系  
**仓库**: https://github.com/AIPMAndy/teach-rd-product-handbook  
**关系**: 研发产品训练体系的来源  
**核心功能**:
- 用户价值公式训练
- 需求三要素拆解
- PRD Lite写法
- 技术方案产品化
- 团队产品意识培养

### 3. product-incubator
**描述**: AI驱动的产品孵化平台，快速验证产品假设  
**仓库**: https://github.com/AIPMAndy/product-incubator  
**关系**: 快速验证和MVP方法论来源  
**核心功能**:
- 产品构思助手
- 技术选型引擎
- 代码生成器
- 快速部署
- 数据看板

### 4. andy-mao-strategy
**描述**: Andy定制版毛泽东战略思维系统  
**仓库**: https://github.com/AIPMAndy/andy-mao-strategy  
**关系**: 毛泽东战略思维的来源  
**核心功能**:
- 主要矛盾识别
- 集中兵力打歼灭战
- 农村包围城市
- 持久战三阶段
- 非对称竞争

## 本地技能依赖

这些是本地Claude技能，Andy Product Skill整合了它们的方法论：

### 1. jobs-product
**位置**: `~/.claude/skills/jobs-product/`  
**内容**: 乔布斯产品哲学  
**核心**: 极致简洁、用户不知道自己要什么、细节决定成败

### 2. yujun-product
**位置**: `~/.claude/skills/yujun-product/`  
**内容**: 俞军产品方法论  
**核心**: 用户价值公式、需求三要素、优先级判断

### 3. bezos-strategy
**位置**: `~/.claude/skills/bezos-strategy/`  
**内容**: 贝佐斯战略思维  
**核心**: 客户至上、长期思维、Day 1心态、逆向工作法

### 4. musk-strategy
**位置**: `~/.claude/skills/musk-strategy/`  
**内容**: 马斯克五步法  
**核心**: 质疑需求、删除部分、简化优化、加速周期、自动化

### 5. elon-musk-skill
**位置**: `~/.claude/skills/elon-musk-skill/`  
**内容**: 马斯克思维操作系统（完整版）  
**核心**: 第一性原理、渐近极限法、白痴指数、垂直整合

### 6. ceo-skill
**位置**: `~/.claude/skills/ceo-skill/`  
**内容**: CEO决策框架（本地版）  
**核心**: 与CEOskill仓库对应的本地技能

### 7. dbs-decision
**位置**: `~/.claude/skills/dbs-decision/`  
**内容**: 个人决策系统  
**核心**: 四层结构、来源标签、决策立案、结果回填

## 相关但未直接整合的项目

### 增长类
- **zhangyiming-growth**: 张一鸣增长方法论（未来v2.0可能整合）
- 位置: 查找中...

### 投资类
- **duanyongping-invest**: 段永平投资方法论
- **changying-index-fund-skill**: 长赢指数投资
- 位置: `~/.claude/skills/`

### 思维类
- **munger-thinking**: 查理·芒格思维模型
- **feynman-skill**: 费曼学习法
- **ilya-sutskever-skill**: Ilya Sutskever AI视角
- 位置: `~/.claude/skills/`

### 内容创作类
- **andy-ip-skill**: IP内容创作工具箱
- **andy-whitepaper**: 白皮书写作
- **copywriting**: 文案写作
- 位置: `~/.claude/skills/`

## 整合关系图

```
andy-product-skill (元整合)
├── 产品决策层
│   ├── yujun-product (用户价值)
│   ├── jobs-product (极致体验)
│   └── bezos-strategy (长期主义)
├── 效率优化层
│   ├── musk-strategy (五步法)
│   └── elon-musk-skill (第一性原理)
├── 战略决策层
│   ├── ceo-skill (决策框架)
│   ├── CEOskill (GitHub版)
│   └── andy-mao-strategy (战略思维)
└── 执行落地层
    ├── teach-rd-product-handbook (团队训练)
    ├── product-incubator (快速验证)
    └── dbs-decision (决策跟踪)
```

## 使用建议

### 单独使用
如果你只需要某个特定框架，可以直接使用原项目：
- 只需CEO决策 → 用 CEOskill
- 只需战略分析 → 用 andy-mao-strategy
- 只需团队培训 → 用 teach-rd-product-handbook

### 组合使用
如果你需要多个框架协同，使用 andy-product-skill：
- 自动场景路由
- 多框架协同
- 统一的使用界面

## 贡献新的整合

如果你发现了好的产品/战略方法论，欢迎提交PR整合到andy-product-skill：

1. 在 `docs/frameworks/` 下添加新框架文档
2. 在 `SKILL.md` 中添加框架描述和使用场景
3. 更新智能路由系统，添加新的场景组合
4. 提供使用案例

详见 [CONTRIBUTING.md](../CONTRIBUTING.md)

---

**最后更新**: 2026-07-15
