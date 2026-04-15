
# 本仓库代码已全部删除
# 基于Renren-Skill生成的代码与System Prompt均与本仓库作者无关
# 请之前下载文件与代码的用户于看到此README的24小时内删除源代码与相关衍生品
# 本仓库原Renren-Skill仅基于公开微博数据蒸馏，仅供个人学习代码使用
# 本仓库代码出于尊重原作者/蒸馏对象 的隐私和肖像权，现不再维护与提供下载服务









# 以下为原README

# 🩷  — 恋恋 Renren 角色扮演 Skill

恋恋来袭😋💕 这是一个让 AI 变成恋恋的 skill…！从 779 条微博和 6106 条评论中蒸馏出来的哦…！仿制面包超人精心制作的…😋💕

## ✨ 这是什么

让 OpenClaw / ChatGPT / Claude / SillyTavern 等 AI 扮演「恋恋 Renren」的角色扮演技能。

支持三种模式：
- 🎭 **角色扮演** — 直接以恋恋的口吻对话
- 📖 **知识问答** — 关于恋恋和 StarHoney 的问题
- ✍️ **风格迁移** — 用恋恋的风格写任何内容

## 📦 安装

### OpenClaw

```bash
# 从 .skill 文件安装
skill install renren.skill

# 或者把 idol-renren/ 文件夹放到 skills 目录
cp -r idol-renren/ ~/.openclaw/skills/
```

### 其他 AI 平台

把 `universal-system-prompt.md` 全文复制为 system prompt 即可，适用于：
- ChatGPT / Claude / Gemini
- SillyTavern / Character.AI
- 任何支持 system prompt 的 AI 平台



## 📁 文件结构

```
renren/
├── SKILL.md                    ← OpenClaw 核心指令
├── universal-system-prompt.md  ← 跨平台通用版 system prompt
└── references/
    ├── persona.md              ← 深度人格画像
    ├── examples.md             ← 11 场景 × 真实语料 few-shot 示例
    └── knowledge.md            ← 知识库
```

## 🧬 数据来源

- **语料来源**：微博全量数据
- **数据规模**：779 条原创/转发微博 + 6106 条本人评论
- **时间范围**：2024.09 ~ 2026.04
- **蒸馏方法**：LLM 辅助人格画像提取 + 多轮 prompt 迭代优化

## 💕 恋恋简介

| 项目 | 内容 |
|------|------|
| 艺名 | 恋恋 Renren |
| 所属 | StarHoney（中国地下偶像团体） |
| 担当色 | 桃色 🩷 |
| 生日 | 11/29 射手座 ♐️ |
| 昵称 | 面包超人 |
| 特技 | 对视三秒就能让人喜欢上恋恋的超能力 💕 |

## 🍞 语言特征

- 句尾用「…！😋💕」，不用波浪号
- 称呼对方「宝宝」
- 面包是信仰，讨厌白切鸡
- 偶尔「喵…？😋💕」，偶尔 wwww
- 否定用「才不是…呢😋💕」「不许…！😋🫵🏻💕」

## ⚠️ 注意

本 skill 基于公开微博数据蒸馏，仅供个人学习和角色扮演使用。
请尊重原作者的隐私和肖像权，勿用于商业用途或冒充本人。

## 📄 License

MIT

---

> 其实恋恋觉得自己最最最可爱的魅力点是对喜欢大家的决心比任何人都自信😋💕要注意到哦😋🫵🏻💕💕💕
