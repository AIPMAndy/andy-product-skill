# Andy Product Skill - 产品方法论整合系统

<div align="center">

**整合 7 位大师的产品智慧，形成智能路由的产品决策操作系统**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-purple.svg)](https://claude.ai)

[English](#english) | [中文](#中文)

</div>

---

## 中文

### 这是什么？

Andy Product Skill 是一个为 Claude AI 设计的产品决策辅助系统，整合了：

1. **俞军产品方法论** - 用户价值、需求分析
2. **乔布斯产品哲学** - 极致体验、创新突破
3. **贝佐斯战略思维** - 长期主义、客户导向
4. **马斯克五步法** - 第一性原理、效率优化
5. **CEO 决策框架** - 结构化决策、去偏见
6. **毛泽东战略思维** - 弱者战略、竞争策略
7. **研发产品训练体系** - 团队协作、产品意识

### 为什么需要它？

**痛点 1：方法论太多，不知道用哪个**
- ❌ 看过很多产品书，用的时候想不起来
- ✅ 智能路由系统：根据场景自动推荐框架组合

**痛点 2：决策凭感觉，容易出错**
- ❌ "我觉得用户会喜欢"、"竞品都这么做"
- ✅ 结构化决策流程：分析 → 选项 → 去偏见 → 验证

**痛点 3：战略与执行脱节**
- ❌ 有宏大愿景，但不知道下一步做什么
- ✅ 多框架协同：长期战略 + 短期执行 + 持续验证

### 核心特性

#### 🎯 智能场景路由

根据你的问题类型，自动选择最合适的框架：

| 场景 | 推荐框架 | 输出 |
|------|---------|------|
| 新产品决策 | 俞军 + 贝佐斯 + CEO + 马斯克 | 做/不做建议 + MVP 范围 |
| 产品打磨 | 乔布斯 + 马斯克 + 俞军 | 删除清单 + 打磨重点 |
| 竞争策略 | 毛泽东 + CEO + 贝佐斯 + 俞军 | 突破点 + 非对称策略 |
| 长期规划 | 贝佐斯 + 毛泽东 + CEO + 马斯克 | 战略愿景 + 路线图 |
| 团队管理 | 毛泽东 + 马斯克 + 研发训练 | 问题诊断 + 改进计划 |
| 需求优先级 | 俞军 + 马斯克 + 乔布斯 + 毛泽东 | 优先级排序 + 路线图 |

#### 🧠 多框架协同

不是简单堆砌，而是有机组合：

```
例：新产品决策

俞军方法论 → 分析用户价值（用户、场景、问题）
    ↓
贝佐斯逆向工作法 → 写新闻稿，从终点倒推
    ↓
CEO 决策框架 → 评估风险、生成选项、去偏见
    ↓
马斯克五步法 → 质疑需求，能否简化或不做
    ↓
最终输出：做/不做的明确建议 + MVP 范围 + 验证指标
```

#### ✅ 去偏见检查

每个决策都要通过认知偏见检查：
- 锚定效应：是否被第一个方案/数字影响？
- 沉没成本：是否因为"已投入很多"而继续？
- 确认偏见：是否只找支持自己的证据？
- 可得性偏见：是否过度重视最近的事件？

#### 🎯 使命对齐

所有决策都要回答：如何推进 Andy 的使命？
- 多行星文明备份
- 全链可持续能源
- 人机共生平衡 AGI 风险
- AI 赋能 80 亿人

### 快速开始

#### 1. 安装 Skill

**方式一：直接复制**
```bash
# 复制到 Claude Skills 目录
cp -r andy-product-skill ~/.claude/skills/
```

**方式二：Git 克隆**
```bash
cd ~/.claude/skills/
git clone https://github.com/AIPMAndy/andy-product-skill.git
```

#### 2. 使用 Skill

在 Claude 对话中：

```
/andy-product-skill

或者直接说：
"用产品方法论帮我分析一下这个需求"
"用 Andy Product Skill 评估这个战略决策"
```

#### 3. 场景示例

**场景 1：新功能决策**
```
我在考虑给产品加一个 AI 聊天功能，该不该做？

→ Skill 会自动用俞军三要素分析
→ 评估用户价值（新体验 - 旧体验 - 替换成本）
→ 用马斯克五步法质疑必要性
→ 给出明确的做/不做建议
```

**场景 2：竞品对抗**
```
竞争对手是行业巨头，我们资源有限，怎么打？

→ Skill 会用毛泽东战略思维
→ 农村包围城市（找边缘突破点）
→ 集中兵力打歼灭战（资源聚焦）
→ 给出非对称竞争策略
```

**场景 3：需求太多不知道做哪个**
```
积压了 50 个需求，优先级怎么排？

→ Skill 会用俞军的优先级公式
→ 用户量 × 频次 × 价值
→ 用马斯克五步法质疑需求必要性
→ 给出 P0/P1/P2 分级和拒绝清单
```

### 文件结构

```
andy-product-skill/
├── README.md                 # 项目说明（本文件）
├── README_EN.md             # 英文说明
├── SKILL.md                 # 核心 Skill 文件（Claude 读取）
├── LICENSE                  # MIT 许可证
├── docs/                    # 详细文档
│   ├── frameworks/          # 各个框架的详细说明
│   │   ├── yujun.md        # 俞军方法论
│   │   ├── jobs.md         # 乔布斯哲学
│   │   ├── bezos.md        # 贝佐斯战略
│   │   ├── musk.md         # 马斯克五步法
│   │   ├── ceo.md          # CEO 决策框架
│   │   ├── mao.md          # 毛泽东战略
│   │   └── rd-training.md  # 研发产品训练
│   ├── scenarios/           # 场景使用指南
│   │   ├── new-product.md  # 新产品决策
│   │   ├── competition.md  # 竞争策略
│   │   ├── optimization.md # 产品打磨
│   │   └── priority.md     # 优先级排序
│   └── case-studies/        # 真实案例
│       ├── case-01-feature-decision.md
│       ├── case-02-market-entry.md
│       └── case-03-team-efficiency.md
├── examples/                # 示例模板
│   ├── decision-template.md     # 决策模板
│   ├── analysis-template.md    # 分析模板
│   └── retrospective-template.md # 复盘模板
└── references/              # 参考资料
    ├── books.md            # 推荐书籍
    ├── articles.md         # 推荐文章
    └── related-repos.md    # 相关仓库
```

### 使用场景

#### 产品经理
- ✅ 需求分析和优先级排序
- ✅ 产品规划和路线图制定
- ✅ 竞品分析和差异化策略
- ✅ 功能设计和体验优化

#### 创业者
- ✅ 产品方向选择和 MVP 定义
- ✅ 市场进入策略和竞争策略
- ✅ 资源有限情况下的聚焦决策
- ✅ 长期战略规划和阶段目标

#### 技术负责人
- ✅ 技术方案的产品价值评估
- ✅ 团队效率优化和流程改进
- ✅ 研发与产品的协作优化
- ✅ 技术债务的优先级判断

#### 投资人
- ✅ 项目价值评估和战略判断
- ✅ 创业团队的产品能力评估
- ✅ 市场时机和竞争格局分析
- ✅ 长期价值判断

### 与其他项目的关系

Andy Product Skill 整合了以下开源项目：

| 项目 | 关系 | 链接 |
|------|------|------|
| **CEOskill** | CEO 决策框架来源 | [GitHub](https://github.com/AIPMAndy/CEOskill) |
| **teach-rd-product-handbook** | 研发产品训练体系 | [GitHub](https://github.com/AIPMAndy/teach-rd-product-handbook) |
| **product-incubator** | 产品孵化方法论 | [GitHub](https://github.com/AIPMAndy/product-incubator) |
| **andy-mao-strategy** | 毛泽东战略思维 | [GitHub](https://github.com/AIPMAndy/andy-mao-strategy) |

本 Skill 是这些项目的"元整合"，提供统一的调用接口。

### 贡献指南

欢迎贡献！可以贡献的内容：

1. **新案例**：提交真实的使用案例（可匿名）
2. **新框架**：建议增加新的产品方法论
3. **改进建议**：优化现有框架的描述和使用方式
4. **文档完善**：补充文档、修正错误

**提交方式**：
1. Fork 本仓库
2. 创建分支：`git checkout -b feature/your-feature`
3. 提交改动：`git commit -m 'Add some feature'`
4. 推送分支：`git push origin feature/your-feature`
5. 提交 Pull Request

### 路线图

#### v1.0.0 (已完成)
- [x] 整合 7 个核心框架
- [x] 建立智能路由系统
- [x] 添加使命对齐检查
- [x] 提供 6 个场景组合

#### v1.1.0 (计划中)
- [ ] 增加交互式决策向导
- [ ] 添加更多真实案例
- [ ] 支持中英文双语
- [ ] 增加可视化决策树

#### v2.0.0 (未来)
- [ ] 整合更多方法论（张一鸣、张小龙等）
- [ ] AI 辅助决策建议（基于历史案例）
- [ ] 团队协作功能（多人决策）
- [ ] 与产品管理工具集成

### 常见问题

**Q: 这个 Skill 和单独使用各个方法论有什么区别？**

A: 
- **智能路由**：根据场景自动选择框架，不需要你记住每个方法论
- **多框架协同**：不同框架互补，交叉验证，减少盲点
- **去偏见检查**：自动识别认知偏见，提高决策质量
- **使命对齐**：确保所有决策服务于长期目标

**Q: 我需要学会所有 7 个方法论才能用吗？**

A: 不需要。Skill 会根据你的问题自动选择和应用框架，你只需要描述问题即可。

**Q: 适合个人使用还是团队使用？**

A: 都适合。个人可以用来提升决策质量，团队可以用作统一的决策语言和流程。

**Q: 和 GPT/Claude 的普通对话有什么区别？**

A: 
- **结构化**：有明确的分析框架和输出格式
- **专业性**：基于多位大师的实战经验
- **可验证**：每个建议都有明确的依据和验证指标
- **去偏见**：主动识别和纠正认知偏见

**Q: 可以用于商业项目吗？**

A: 可以。本项目采用 MIT 许可证，可自由使用、修改和商业化。

### 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

### 作者

**Andy** - AI 产品专家、持续创业者

- 前腾讯/百度 AI 产品负责人
- 大模型独角兽 VP
- 多个开源项目作者

**联系方式**：
- GitHub: [@AIPMAndy](https://github.com/AIPMAndy)
- 微信: `AIPMAndy`（课程咨询、商业合作）

### 致谢

感谢以下项目和方法论的启发：
- 俞军《俞军产品方法论》
- Walter Isaacson《乔布斯传》
- Jeff Bezos 的 Amazon Letters to Shareholders
- Elon Musk 的五步算法
- 毛泽东《矛盾论》《实践论》
- 以及所有为产品方法论做出贡献的前辈

---

## English

### What is this?

Andy Product Skill is a product decision-making system for Claude AI that integrates:

1. **Yu Jun's Product Methodology** - User value, requirement analysis
2. **Steve Jobs' Product Philosophy** - Ultimate experience, innovation
3. **Jeff Bezos' Strategic Thinking** - Long-term vision, customer obsession
4. **Elon Musk's 5-Step Algorithm** - First principles, efficiency
5. **CEO Decision Framework** - Structured decisions, debiasing
6. **Mao Zedong's Strategic Thinking** - Underdog strategy, competition
7. **RD Product Training System** - Team collaboration, product mindset

### Why do you need it?

**Pain Point 1: Too many methodologies, don't know which to use**
- ❌ Read many product books, can't recall when needed
- ✅ Smart routing: Auto-recommends framework combinations

**Pain Point 2: Decisions based on gut feeling**
- ❌ "I think users will like it", "Competitors do this"
- ✅ Structured process: Analysis → Options → Debiasing → Validation

**Pain Point 3: Strategy-execution gap**
- ❌ Have grand vision, don't know next steps
- ✅ Multi-framework synergy: Long-term + Short-term + Validation

### Quick Start

```bash
# Clone the repository
cd ~/.claude/skills/
git clone https://github.com/AIPMAndy/andy-product-skill.git

# Use in Claude
/andy-product-skill

# Or simply ask:
"Use product methodology to analyze this requirement"
```

### Core Features

- 🎯 **Smart Scenario Routing** - Auto-selects best frameworks
- 🧠 **Multi-Framework Synergy** - Organic combination, not simple stacking
- ✅ **Debiasing Check** - Identifies cognitive biases
- 🎯 **Mission Alignment** - Aligns with long-term goals

### License

MIT License - See [LICENSE](LICENSE) file

### Author

**Andy** - AI Product Expert, Serial Entrepreneur

- Ex-Tencent/Baidu AI Product Lead
- VP at LLM Unicorn
- Open Source Contributor

**Contact**:
- GitHub: [@AIPMAndy](https://github.com/AIPMAndy)
- WeChat: `AIPMAndy`

---

**Built with ❤️ by Andy | 2026-07-15**
