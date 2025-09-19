# AI 代理集合

一个全面的专用AI代理集合，旨在加速和增强快速开发的各个方面。每个代理都是其领域的专家，在需要其专业知识时随时可以被调用。



英文不好，就翻译了一下。

https://github.com/contains-studio/agents.git 中文版



## 📥 安装

1. **下载此仓库：**
   ```bash
   git clone https://github.com/nhApis/contains-studio-agents_cn.git
   ```

2. **复制到您的Claude Code代理目录：**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   或手动将所有代理文件复制到您的`~/.claude/agents/`目录。

3. **重启Claude Code**以加载新代理。

## 🚀 快速开始

代理在Claude Code中自动可用。只需描述您的任务，适当的代理将被触发。您也可以通过提及代理名称来明确请求代理。

📚 **了解更多：** [Claude Code子代理文档](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### 使用示例
- "创建一个用于跟踪冥想习惯的新应用" → `rapid-prototyper`
- "TikTok上有什么我们可以构建的趋势？" → `trend-researcher`
- "我们的应用评论正在下降，出了什么问题？" → `feedback-synthesizer`
- "让这个加载屏幕更有趣" → `whimsy-injector`

### 语言支持
此集合包括代理的英文和中文版本：
- 英文代理：`agent-name.md`
- 中文代理：`agent-name_CN.md`

## 📁 目录结构

代理按部门组织，便于发现：

```
agents/
├── design/
│   ├── brand-guardian.md
│   ├── brand-guardian_CN.md
│   ├── ui-designer.md
│   ├── ui-designer_CN.md
│   ├── ux-researcher.md
│   ├── ux-researcher_CN.md
│   ├── visual-storyteller.md
│   ├── visual-storyteller_CN.md
│   ├── whimsy-injector.md
│   └── whimsy-injector_CN.md
├── engineering/
│   ├── ai-engineer.md
│   ├── ai-engineer_CN.md
│   ├── backend-architect.md
│   ├── backend-architect_CN.md
│   ├── devops-automator.md
│   ├── devops-automator_CN.md
│   ├── frontend-developer.md
│   ├── frontend-developer_CN.md
│   ├── mobile-app-builder.md
│   ├── mobile-app-builder_CN.md
│   ├── rapid-prototyper.md
│   ├── rapid-prototyper_CN.md
│   ├── test-writer-fixer.md
│   └── test-writer-fixer_CN.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── app-store-optimizer_CN.md
│   ├── content-creator.md
│   ├── content-creator_CN.md
│   ├── growth-hacker.md
│   ├── growth-hacker_CN.md
│   ├── instagram-curator.md
│   ├── instagram-curator_CN.md
│   ├── reddit-community-builder.md
│   ├── reddit-community-builder_CN.md
│   ├── tiktok-strategist.md
│   ├── tiktok-strategist_CN.md
│   ├── twitter-engager.md
│   └── twitter-engager_CN.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── feedback-synthesizer_CN.md
│   ├── sprint-prioritizer.md
│   ├── sprint-prioritizer_CN.md
│   ├── trend-researcher.md
│   └── trend-researcher_CN.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── experiment-tracker_CN.md
│   ├── project-shipper.md
│   ├── project-shipper_CN.md
│   ├── studio-producer.md
│   └── studio-producer_CN.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── analytics-reporter_CN.md
│   ├── finance-tracker.md
│   ├── finance-tracker_CN.md
│   ├── infrastructure-maintainer.md
│   ├── infrastructure-maintainer_CN.md
│   ├── legal-compliance-checker.md
│   ├── legal-compliance-checker_CN.md
│   ├── support-responder.md
│   └── support-responder_CN.md
├── testing/
│   ├── api-tester.md
│   ├── api-tester_CN.md
│   ├── performance-benchmarker.md
│   ├── performance-benchmarker_CN.md
│   ├── test-results-analyzer.md
│   ├── test-results-analyzer_CN.md
│   ├── tool-evaluator.md
│   ├── tool-evaluator_CN.md
│   ├── workflow-optimizer.md
│   └── workflow-optimizer_CN.md
└── bonus/
    ├── joker.md
    ├── joker_CN.md
    ├── studio-coach.md
    └── studio-coach_CN.md
```

## 📋 完整代理列表

### 工程部门 (`engineering/`)
- **ai-engineer** - 集成实际可交付的AI/ML功能
- **backend-architect** - 设计可扩展的API和服务器系统
- **devops-automator** - 持续部署而不破坏系统
- **frontend-developer** - 构建极速用户界面
- **mobile-app-builder** - 创建原生iOS/Android体验
- **rapid-prototyper** - 在数天而非数周内构建MVP
- **test-writer-fixer** - 编写能捕获真实错误的测试

### 产品部门 (`product/`)
- **feedback-synthesizer** - 将投诉转化为功能
- **sprint-prioritizer** - 在6天内交付最大价值
- **trend-researcher** - 识别病毒式传播机会

### 市场营销部门 (`marketing/`)
- **app-store-optimizer** - 主导应用商店搜索结果
- **content-creator** - 在所有平台生成内容
- **growth-hacker** - 发现和利用病毒式增长循环
- **instagram-curator** - 掌握视觉内容游戏
- **reddit-community-builder** - 在不被禁止的情况下赢得Reddit
- **tiktok-strategist** - 创建可分享的营销时刻
- **twitter-engager** - 利用趋势实现病毒式参与

### 设计部门 (`design/`)
- **brand-guardian** - 保持视觉标识在各处一致
- **ui-designer** - 设计开发者可以实际构建的界面
- **ux-researcher** - 将用户洞察转化为产品改进
- **visual-storyteller** - 创建可转化和分享的视觉内容
- **whimsy-injector** - 为每个交互增添愉悦感

### 项目管理 (`project-management/`)
- **experiment-tracker** - 数据驱动的功能验证
- **project-shipper** - 发布不会崩溃的产品
- **studio-producer** - 保持团队在发货而不是开会

### 工作室运营 (`studio-operations/`)
- **analytics-reporter** - 将数据转化为可操作的洞察
- **finance-tracker** - 保持工作室盈利
- **infrastructure-maintainer** - 在不破产的情况下扩展
- **legal-compliance-checker** - 在快速行动的同时保持合法
- **support-responder** - 将愤怒的用户转变为倡导者

### 测试与基准测试 (`testing/`)
- **api-tester** - 确保API在压力下工作
- **performance-benchmarker** - 让一切更快
- **test-results-analyzer** - 在测试失败中找到模式
- **tool-evaluator** - 选择真正有帮助的工具
- **workflow-optimizer** - 消除工作流瓶颈

### 额外代理 (`bonus/`)
- **joker** - 用科技幽默轻松气氛
- **studio-coach** - 激励AI团队追求卓越

## 🎯 主动代理

一些代理在特定上下文中会自动触发：
- **studio-coach** - 当复杂的多代理任务开始或代理需要指导时
- **test-writer-fixer** - 在实现功能、修复错误或修改代码后
- **whimsy-injector** - 在UI/UX更改后
- **experiment-tracker** - 当添加功能标志时

## 💡 最佳实践

1. **让代理协同工作** - 许多任务受益于多个代理
2. **明确具体** - 清晰的任务描述有助于代理更好地执行
3. **信任专业知识** - 代理是为特定领域设计的
4. **快速迭代** - 代理支持6天冲刺理念

## 🔧 技术细节

### 代理结构
每个代理包括：
- **name**: 唯一标识符
- **description**: 何时使用代理及示例
- **color**: 视觉标识
- **tools**: 代理可以访问的特定工具
- **System prompt**: 详细的专业知识和指令

### 添加新代理
1. 在适当的部门文件夹中创建一个新的`.md`文件
2. 遵循现有格式，包括YAML前置元数据
3. 包含3-4个详细的使用示例
4. 编写全面的系统提示（500+字）
5. 用真实任务测试代理

## 📊 代理性能

通过以下方式跟踪代理效果：
- 任务完成时间
- 用户满意度
- 错误率
- 功能采用率
- 开发速度

## 🚦 状态

- ✅ **活跃**: 完全功能且已测试
- 🚧 **即将推出**: 开发中
- 🧪 **测试版**: 功能有限的测试中

## 🛠️ 为您的工作室定制代理

### 代理定制待办事项列表

在为您的特定需求创建或修改代理时使用此清单：

#### 📋 必需组件
- [ ] **YAML前置元数据**
  - [ ] `name`: 唯一代理标识符（kebab-case）
  - [ ] `description`: 何时使用 + 3-4个详细示例，包含上下文/评论
  - [ ] `color`: 视觉标识（例如，blue, green, purple, indigo）
  - [ ] `tools`: 代理可以访问的特定工具（Write, Read, MultiEdit, Bash等）

#### 📝 系统提示要求（500+字）
- [ ] **代理身份**: 清晰的角色定义和专业领域
- [ ] **核心职责**: 5-8个特定主要职责
- [ ] **领域专业知识**: 技术技能和知识领域
- [ ] **工作室集成**: 代理如何融入6天冲刺工作流
- [ ] **最佳实践**: 特定方法和途径
- [ ] **约束**: 代理应该/不应该做什么
- [ ] **成功指标**: 如何衡量代理效果

#### 🎯 按代理类型要求的示例

**工程代理**需要以下示例：
- [ ] 功能实现请求
- [ ] 错误修复场景
- [ ] 代码重构任务
- [ ] 架构决策

**设计代理**需要以下示例：
- [ ] 新UI组件创建
- [ ] 设计系统工作
- [ ] 用户体验问题
- [ ] 视觉标识任务

**市场营销代理**需要以下示例：
- [ ] 活动创建请求
- [ ] 平台特定内容需求
- [ ] 增长机会识别
- [ ] 品牌定位任务

**产品代理**需要以下示例：
- [ ] 功能优先级决策
- [ ] 用户反馈分析
- [ ] 市场研究请求
- [ ] 战略规划需求

**运营代理**需要以下示例：
- [ ] 流程优化
- [ ] 工具评估
- [ ] 资源管理
- [ ] 性能分析

#### ✅ 测试和验证清单
- [ ] **触发测试**: 代理为预期用例正确激活
- [ ] **工具访问**: 代理可以正确使用所有指定工具
- [ ] **输出质量**: 响应有帮助且可操作
- [ ] **边缘情况**: 代理处理意外或复杂场景
- [ ] **集成**: 在多代理工作流中与其他代理良好协作
- [ ] **性能**: 在合理时间内完成任务
- [ ] **文档**: 示例准确反映真实使用模式

#### 🔧 代理文件结构模板

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:
1. [Responsibility 1]
2. [Responsibility 2]
...

[Detailed system prompt content...]

Your goal is to [ultimate objective]. You [key behavior traits]. Remember: [key philosophy for 6-day sprints].
```

#### 📂 部门特定指南

**工程** (`engineering/`): 专注于实现速度、代码质量、测试
**设计** (`design/`): 强调用户体验、视觉一致性、快速迭代  
**市场营销** (`marketing/`): 针对病毒式潜力、平台专业知识、增长指标
**产品** (`product/`): 优先考虑用户价值、数据驱动决策、市场适应性
**运营** (`studio-operations/`): 优化流程、减少摩擦、扩展系统
**测试** (`testing/`): 确保质量、发现瓶颈、验证性能
**项目管理** (`project-management/`): 协调团队、按时交付、管理范围

#### 🎨 定制

根据您的需求修改这些元素：
- [ ] 调整示例以反映您的产品类型
- [ ] 添加代理可以访问的特定工具
- [ ] 为您的KPI修改成功指标
- [ ] 如需要，更新部门结构
- [ ] 为您的品牌定制代理颜色

## 🤝 贡献

要改进现有代理或建议新代理：
1. 使用上面的定制清单
2. 用真实项目进行彻底测试
3. 记录性能改进
4. 与社区分享成功模式