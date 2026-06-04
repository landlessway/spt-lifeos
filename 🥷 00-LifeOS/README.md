# 00-LifeOS/

## 职责

**操作系统层** — LifeOS 的内核，每次对话启动时自动加载。

包含：
- `IDENTITY/` — 你是谁、你的目标、你的偏好
- `MEMORY/` — 长期记忆、技能库、学习记录、思维导师调用
- `WORKING/` — 工作记忆、任务池、候选池、日常日记

---

## 成员

| 文件夹 | 职责 |
|--------|------|
| `IDENTITY/` | 身份层：TELOS（使命）、CONTEXT（当前状态）、PROFILE（偏好画像）、BLINDSPOTS（盲点） |
| `MEMORY/` | 记忆层：skills、learning、patterns、synapses、mentors |
| `WORKING/` | 工作记忆：tasks、candidates、daily、dialogues |

---

## 启动注入

每次对话开始时，AI 自动加载以下文件：
1. `IDENTITY/TELOS.md` — 你的使命和目标
2. `IDENTITY/CONTEXT.md` — 你当前在做什么
3. `IDENTITY/PROFILE.md` — 你的偏好和风格
4. `MEMORY/learning/` — 你的学习进度（如有）

确保 AI 始终在上下文中。

---

## 动态更新

- IDENTITY 随你的成长而进化
- MEMORY 随使用不断累积
- WORKING 持续滚动更新

---

## 与其他文件夹的关系

| 本文件夹 | 输出到 |
| --- | --- |
| IDENTITY | 所有 Agent 的风格基础 |
| MEMORY/skills | 被 🔵 04-内容创作 调用 |
| MEMORY/learning | 指导 🟡 02-阅读palace 的阅读建议 |
| MEMORY/mentors | 被 🔵 04-表达系统 调用 |
| WORKING/tasks | 每日任务管理 |
| WORKING/candidates | 偏好进化池 → 晋升到 IDENTITY/PROFILE |

## 跨Agent调用

- **🟡 02-阅读palace**：调用 MEMORY/mentors（导师框架）
- **🔵 04-表达系统**：调用 MEMORY/mentors（导师框架）
- **🔵 04-内容创作**：调用 MEMORY/skills（技能库）
- **🟡 02-ibooks-highlights**：全局调用，为所有Agent提供金句

---

**最后更新**：2026-04-10
