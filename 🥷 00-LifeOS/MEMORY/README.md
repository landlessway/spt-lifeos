# MEMORY/

## 职责

**记忆层** — AI 的长期记忆，弥补 AI 没有记忆的缺陷。

包含：
- `skills/` — 可复用的技能（如自定义 Skill）
- `learning/` — 学习进度记录
- `patterns/` — 发现的模式和规律
- `synapses/` — 跨领域连接
- `mentors/` — 思维导师调用记录

---

## 成员

| 文件夹 | 说明 |
|--------|------|
| `skills/` | 存放你的技能（如自定义 Skill），按需添加 |
| `learning/` | 学习记录（按需创建文件，如 `维特根斯坦.md`） |
| `patterns/` | AI 发现的思维模式、行为规律 |
| `synapses/` | 跨领域知识连接（跨领域知识连接） |
| `mentors/` | 费曼/Naval/塔勒布/x-mentor 的调用记录 |

---

## 与 00-LIBRARY 的关系

```
00-LIBRARY/reading/书籍.pdf
    ↓
你阅读、标记
    ↓
MEMORY/learning/书籍.md（学习进度、理解变化）
    ↓
内容够多 → 升级为 KNOWLEDGE/ Wiki
```

---

## 动态更新

- `learning/` 随阅读持续更新
- `patterns/` AI 发现新模式后自动添加
- `synapses/` AI 发现关联后自动创建
- `mentors/` 每次调用后更新使用记录
