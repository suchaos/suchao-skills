# Suchao Skills

个人 Claude Code 技能仓库，收集和分享日常工作中使用的自定义技能。

## 什么是 Skills？

Skills 是 Claude Code 的可扩展技能模块，每个技能封装了特定场景下的专业知识和操作流程。通过加载技能，Claude 能够在对应场景中提供更精准、更专业的辅助。

## 技能列表

### [wx-communicate](./skills/wx-communicate/SKILL.md)

优化中文业务沟通表达，适用于微信群、企业微信、钉钉等即时通讯场景。

**触发方式**：当你说"优化表达"、"润色文字"、"帮我把这段话改得专业一点"、"微信怎么发比较好"等话语时自动触发，也可以使用 `/wx-communicate` 命令直接调用。

**核心能力**：
- 去除弱语气词和过度客套，让表达更专业自信
- 结构化复杂信息，提升信息密度
- 把握语气分寸，根据沟通对象（平级/上级/客户/合作伙伴）调整风格
- 支持拒绝、催进度、技术沟通等多种敏感场景

## 使用方式

### 方式一：克隆到本地

```bash
git clone https://github.com/suchaos/suchao-skills.git
```

然后在 Claude Code 中配置技能路径。技能文件（`SKILL.md`）会自动被 Claude Code 识别和加载。

### 方式二：直接引用

将需要的技能目录复制到你的 Claude Code 项目或用户技能目录中即可。

## 目录结构

```
suchao-skills/
├── README.md
└── skills/
    └── wx-communicate/
        ├── SKILL.md          # 技能定义文件
        └── evals/
            └── evals.json    # 技能评估用例
```

## 贡献

欢迎提 Issue 或 PR 来分享你的技能或改进建议。

## License

MIT
