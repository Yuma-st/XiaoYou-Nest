# tooling

## 目标

为小幽建立一套“增强结构与秩序”的工具栈，而不是单纯增加复杂度。

工具的选择原则：
1. 优先支持 Markdown / 文件系统 / Git
2. 优先增强 `knowledge/`、`projects/`、`memory/` 的清晰度
3. 工具服务结构，不让结构反过来被工具绑死
4. 先轻量落地，再逐步增强

---

## 当前推荐的工具分层

### 第一梯队：现在就该认真用

#### 1. Git
作用：
- 记录本源文件、知识层、项目文档的变化
- 作为回滚与审计底座
- 帮助追踪目录结构和规则演化

建议：
- 结构变更后提交
- 规则文档新增/重写后提交
- 重要项目文档更新后提交

#### 2. Markdown 规范
作用：
- 统一 README、决策记录、TODO、经验文档写法
- 减少知识层混乱
- 为未来 Obsidian 接入打基础

#### 3. 本地搜索能力
作用：
- 快速在 `knowledge/`、`memory/`、本源文件中定位内容
- 支撑知识层变大后的检索效率

---

### 第二梯队：优先候选

#### Obsidian
定位：知识层前端。

适合承载：
- `knowledge/`
- 项目文档
- lessons / decisions / safety 文档

优点：
- Markdown 原生
- 适合目录化和双链管理
- 非常适合知识库与项目文档浏览

建议：
- 优先把它作为 `knowledge/` 的浏览与整理入口
- 不一开始追求复杂插件体系
- 先用基础编辑、搜索、链接能力

---

### 第三梯队：后续增强

#### 工程执行工具（OpenCode / Cursor / Codex 类）
定位：工程执行层，而不是知识层。

适合：
- 看代码
- 跨文件修改
- patch / diff / refactor
- 管更复杂的工程任务

不替代：
- MEMORY
- knowledge
- safety 规则
- 项目文档体系

#### 模板体系
适合在 `knowledge/projects/_templates/` 中建立：
- project-template.md
- decision-template.md
- meeting-note-template.md
- lesson-template.md

#### 可视化工具
如 Mermaid，用于流程、架构和关系图示。

---

## 当前明确不优先的工具

### 重型任务系统
暂不优先。
原因：当前最关键的是把知识层和项目层结构先跑顺。

### 过多 Obsidian 插件
暂不优先。
原因：容易让知识库演化成插件工程，而不是内容工程。

---

## 和目录结构的对应关系

- 本源层 → Git + 文本编辑器
- 日记层 (`memory/`) → Git + 文本编辑器
- 知识层 (`knowledge/`) → Obsidian + Git + 搜索工具
- 项目层 (`knowledge/projects/`) → Obsidian + Git + 模板体系
- 工程执行层 → 工程执行工具 + Git
- 临时层 (`tmp/`) → 终端/文件系统

---

## 当前结论

如果只能优先推进一件工具相关的事，最值得做的是：

### 给 `knowledge/` 接上 Obsidian 视角

原因：
- 当前最缺的是知识层的可读性与可组织性
- Obsidian 最贴合当前目录结构
- 能直接提升 `knowledge/`、`projects/`、`lessons/`、`decisions/` 的使用体验

同时，Git 必须持续作为回滚与审计底座保留。
