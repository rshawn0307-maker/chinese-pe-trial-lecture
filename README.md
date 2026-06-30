# chinese-pe-trial-lecture

中国教师编（教师资格证）体育学科面试试讲稿生成与审校 Skill。

## 功能

- 10 分钟无生上课，4 段式结构（开始-准备-基本-结束）
- 主情境串课，4 维绑定（情境大类⇄项类别⇄主情境⇄3 挑战模板）
- 强对齐到 5 大风格特征 + 15 项硬约束 + 28 条自检
- 24 条 pitfall 三段式 if-then 表（触发条件/一线修复/仍失败兜底）
- 支持生成流（新稿）和审校流（已有稿拆解）双模式
- 覆盖综合分析、组织计划、人际关系、应急应变、自我认知、言语表达六类题型

## 安装

将本仓库克隆到你的 agent skills 目录：

```bash
# 通用路径（auto-detect runtime）
git clone https://github.com/rshawn0307-maker/chinese-pe-trial-lecture.git

# 然后将整个目录复制到你的 skills 目录
# 例如：~/.claude/skills/ 或 ~/.trae-cn/skills/ 或 ~/.codex/skills/
```

## 使用

当用户说"试讲稿""试讲逐字稿""无生上课""体育面试稿"且指向体育学科时自动触发。

## 评分

Darwin-skill 优化评分：**84.6/100**（2026-06-30 优化）

## License

MIT
