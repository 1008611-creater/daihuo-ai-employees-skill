# 带货 AI 员工 Skill 安装说明

这个包用于把“带货 AI 员工”分享给其他 Codex App 用户。

## 包内容

```text
daihuo-ai-employees/
  SKILL.md
  agents/openai.yaml
  references/
    compliance.md
    role-playbooks.md
    templates.md
```

## 安装方式一：全局安装

适合个人长期使用，任何 Codex 项目里都能触发。

Windows:

```text
C:\Users\<你的用户名>\.codex\skills\daihuo-ai-employees
```

macOS/Linux:

```text
~/.codex/skills/daihuo-ai-employees
```

把压缩包里的 `daihuo-ai-employees` 文件夹完整放进去，然后重启 Codex App。

## 安装方式二：项目安装

适合团队共享一个项目仓库。

把 `daihuo-ai-employees` 文件夹放到项目根目录：

```text
项目根目录/.agents/skills/daihuo-ai-employees
```

然后重新打开这个项目或重启 Codex App。

## 使用方式

在 Codex 里输入：

```text
请使用带货 AI 员工，为下面商品生成今天可执行的带货运营包。

商品名：
类目：
价格：
规格/套餐：
佣金或毛利：
库存：
发货地：
物流时效：
目标平台：抖音/快手/小红书/直播/多平台
目标人群：
核心卖点：
证明材料：
风险点：
售后政策：
今日目标：测品/起号/直播成交/复购/清库存
```

## 触发关键词

以下说法都能触发：

- 带货 AI 员工
- 选品分析
- 短视频脚本
- 直播话术
- 评论回复
- 小红书种草文案
- 抖音/快手带货内容
- 商品卖点拆解
- 带货复盘

## 分发建议

最简单：直接发 ZIP。

更适合团队：放到 Git 仓库，让团队成员把 `daihuo-ai-employees` 文件夹复制到自己的 `.codex/skills`，或者把它作为项目的 `.agents/skills` 一起提交。
