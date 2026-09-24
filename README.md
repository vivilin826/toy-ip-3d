# Toy IP 3D

一个用于 Codex 的 Skill：从角色原画建立可复用的 3D 潮玩图片母版与角色身份卡，再以母版制作换装、姿势和表情变体。

它生成的是 **3D 风格图片**，不是可旋转、可打印的三维模型。角色原画、母版和生成作品保存在使用者自己的项目中；本仓库只包含通用 Skill 与空白身份卡模板。

## 安装

把本仓库克隆到 Codex 的个人 Skills 目录：

```bash
git clone https://github.com/vivilin826/toy-ip-3d.git ~/.codex/skills/toy-ip-3d
```

重新打开 Codex 后，可在对话中提及 `$toy-ip-3d`，并提供角色原画或已有的 3D 母版。

## 使用方式

- 首次建立角色：提供原画，生成 3D 母版及角色身份卡。
- 制作系列变体：提供已确认的母版，再描述服饰、姿势、表情或场景；也可以附参考图并指定各图的用途。
- 母版固定角色身份与五官结构，表情可变。外部人物参考图只影响用户指定的部分。

具体工作规则见 [SKILL.md](SKILL.md)，空白身份卡见 [references/character-card-template.md](references/character-card-template.md)。
