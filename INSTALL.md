# 带货 AI 员工 Skill Pack 安装说明

这个包用于把“带货 AI 员工团队”分享给其他 Codex App 用户。

## 包内容

```text
daihuo-ai-employees/
daihuo-product-selection/
daihuo-supply-channels/
daihuo-platform-playbooks/
daihuo-content-conversion/
daihuo-growth-review/
```

每个文件夹都是一个独立 skill，包含：

```text
SKILL.md
agents/openai.yaml
references/
```

## 安装方式一：全局安装

适合个人长期使用，任何 Codex 项目里都能触发。

Windows:

```text
C:\Users\<你的用户名>\.codex\skills\
```

macOS/Linux:

```text
~/.codex/skills/
```

把本仓库里的 6 个 `daihuo-*` 文件夹完整放进去，然后重启 Codex App。

## 安装方式二：项目安装

适合团队共享一个项目仓库。

把 6 个 `daihuo-*` 文件夹放到项目根目录：

```text
项目根目录/.agents/skills/
```

然后重新打开这个项目或重启 Codex App。

## 使用方式

完整方案：

```text
请使用带货 AI 员工总控，为下面商品做一套从选品、货源、平台、内容到复盘的落地方案。

商品名：
类目：
价格：
规格/套餐：
佣金或毛利：
库存：
发货地：
物流时效：
可选货源渠道：
目标平台：
目标人群：
核心卖点：
证明材料：
竞品或参考账号：
已有数据：
风险点：
售后政策：
今日目标：
```

单独使用：

- `请作为带货选品数据员工...`
- `请作为带货货源渠道员工...`
- `请作为平台带货路径员工...`
- `请作为带货内容转化员工...`
- `请作为带货复盘增长员工...`

## 触发关键词

以下说法都能触发对应岗位：

- 带货 AI 员工、完整带货方案、带货员工团队
- 选品、测品、爆品判断、数据依据、佣金分析、退货风险
- 从哪里上货、猿推推、巨量百应、精选联盟、快分销、蒲公英、达人带货小程序
- 抖音带货路径、快手带货路径、小红书带货路径、平台适配
- 短视频脚本、直播话术、评论回复、小红书种草、口播、分镜
- 播放量、完播率、点击率、GMV、退货率、复盘、下一轮优化

## 分发建议

最简单：直接发 GitHub 链接，让别人复制 6 个 `daihuo-*` 文件夹到自己的 `.codex/skills`。

团队使用：把 6 个 skill 文件夹作为项目的 `.agents/skills` 一起提交，让团队成员打开项目就能用同一套带货员工。
