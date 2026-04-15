# openclaw-book-to-article Skill

把“一本书/读书笔记/长文材料”转化为**可发布的高质量中文文章**的写作 Skill（破/立/塑/润四阶段）。

## 内容

- `SKILL.md`：Skill 规范与执行流程

## 使用方式（Cursor Skills）

将本目录放到你的 Skills 路径下（例如 `~/.cursor/skills/`），或把 `SKILL.md` 的内容同步到你正在使用的 Skill 管理位置。

## 安装到 OpenClaw / Cursor 的推荐方式

下面以 macOS 为例（Linux 同理）。

### 方式 A：直接把仓库放进 Skills 目录（推荐）

1) 克隆仓库到本地：

```bash
git clone git@github.com:coolsujiekai/openclaw-book-to-article-skill.git
```

2) 把仓库移动（或软链接）到 Cursor Skills 目录：

```bash
mkdir -p ~/.cursor/skills
mv ./openclaw-book-to-article-skill ~/.cursor/skills/
```

完成后确保这个文件存在：

- `~/.cursor/skills/openclaw-book-to-article-skill/SKILL.md`

### 方式 B：只复制 `SKILL.md`（适合你已有技能管理结构）

把本仓库的 `SKILL.md` 内容复制到你的 Skill 管理位置，并保持 Skill 名称与头部元信息不被破坏。

## 如何在写作时使用（最小用法）

1) 准备输入：书名/章节要点/划线摘录/读后感任意一种即可（越碎也可以）。
2) 在 Cursor（或 OpenClaw）里调用该 Skill：`openclaw-book-to-article`。
3) 按 Skill 流程依次产出：刺点与靶心场景 → 推演链条闭环 → 二三稿质感 → Lead/标题/摘要/终稿。


