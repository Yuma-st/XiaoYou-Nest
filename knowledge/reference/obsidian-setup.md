# obsidian setup

## 这份文档的目的

说明小幽准备如何使用 Obsidian，以及你打开 Obsidian 后，应该把它当成什么工具来用。

一句话：

**Obsidian 不是小幽的脑子，而是小幽知识层最顺手的书房。**

---

## Obsidian 在小幽体系里的定位

小幽当前已经开始形成这些层次：
- 本源层：`AGENTS.md` / `SOUL.md` / `USER.md` / `IDENTITY.md` / `MEMORY.md`
- 日记层：`memory/`
- 知识层：`knowledge/`
- 项目层：`knowledge/projects/`
- 角色层：`roles/`
- 临时层：`tmp/`

其中，Obsidian 主要服务的是：
- `knowledge/`
- `knowledge/projects/`
- `knowledge/lessons/`
- `knowledge/safety/`
- `knowledge/decisions/`
- `knowledge/reference/`

它不负责替代 Git、不负责替代 memory，也不应该成为插件游乐场。

---

## 推荐打开方式

### 推荐做法

**直接把整个 workspace 打开成一个 Obsidian vault。**

原因：
- 不需要复制文件
- Git 继续管理真实文件
- 本源、memory、knowledge 都能被统一看见
- 后续目录结构调整不需要额外同步

### 但使用重心要明确

虽然是整个 workspace 做 vault，实际重点关注的是：

- `knowledge/README.md`
- `knowledge/projects/README.md`
- `knowledge/safety/README.md`
- `knowledge/projects/小幽自身进化/`

也就是说：

**打开全局，使用时聚焦 knowledge。**

---

## 当前最适合用 Obsidian 做什么

### 1. 看知识层
最直接的用途是浏览 `knowledge/`，帮助你快速看到：
- 当前知识库结构
- 已有项目
- 已有决策
- 已有工具建议
- 后续安全文档

### 2. 看项目文档
尤其是：
- `knowledge/projects/小幽自身进化/`

后续它会成为小幽升级工作的固定项目空间。

### 3. 看决策与经验沉淀
随着文档增多，Obsidian 会很适合：
- 回看为什么做某个决定
- 找过去的经验教训
- 建立项目、规则和经验之间的链接

---

## 当前不建议拿 Obsidian 做什么

### 1. 不要一开始追求复杂插件体系
现在最重要的是内容结构，不是插件数量。

### 2. 不要把 `tmp/` 当知识区
`tmp/` 是临时层，不是知识层。

### 3. 不要把 daily memory 全都知识化
`memory/` 仍然主要是日志与短期上下文；真正沉淀后的内容，再进入 `knowledge/`。

---

## 一开始建议这样使用

### 第一步
打开 workspace，先熟悉这几个入口：
- `knowledge/README.md`
- `knowledge/projects/README.md`
- `knowledge/reference/tooling-overview.md`
- `knowledge/reference/obsidian-setup.md`
- `knowledge/projects/小幽自身进化/README.md`

### 第二步
重点浏览：
- `knowledge/projects/小幽自身进化/`
- `knowledge/safety/`
- `knowledge/decisions/`

### 第三步
开始接受一种习惯：
- daily memory 是流水
- knowledge 是沉淀
- project 是任务与设计的承接区

---

## 后续建议逐步补的入口文档

后面建议继续补：
- `knowledge/lessons/README.md`
- `knowledge/decisions/README.md`
- `knowledge/reference/README.md`

这样 Obsidian 中的知识层会更顺手。

---

## 关于插件的建议

### 当前建议
先只用基础能力：
- 文件树
- 搜索
- 双链（如果需要）
- 最近文档
- 基础 markdown 编辑

### 暂时不建议
- 装太多插件
- 一开始就折腾复杂仪表盘
- 过度依赖知识图谱视图

### 后续可考虑
如果知识层稳定增长，再考虑：
- Dataview（做项目/决策索引）
- Templates（做文档模板）

但这属于后续增强，不是现在必须做的。

---

## 和 Git 的关系

Obsidian 管的是“看和整理”，不是版本控制。

Git 仍然负责：
- 回滚
- 审计
- 提交历史
- 远端同步

最理想的组合是：

- Obsidian = 书房 / 书架 / 索引
- Git = 黑匣子 / 版本历史 / 回滚底座

---

## 当前结论

如果说 `knowledge/` 是小幽的知识层，
那么 Obsidian 的作用就是：

**把这个知识层从“文件夹”变成“能用、能看、能长”的工作空间。**
