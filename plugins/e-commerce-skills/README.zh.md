# e-commerce-skills｜电商详情页内容 Skill

在 Claude Code、Codex、WorkBuddy 等支持 skills 的工具中运行：

```text
/install-skill saibodafu/e-commerce-skill/ecommerce-content-wireframe
```

这是一个用于梳理电商商品详情页内容的 skill。

当前可用能力是：`ecommerce-content-wireframe`。它会先引导用户填写完整产品信息表，再按照固定步骤梳理详情页内容；内容确认后，生成一份可运行的手机长图 HTML 黑白线框稿，用于预览详情页内容结构、模块顺序和转化逻辑。

## 当前 Skill

### ecommerce-content-wireframe

电商详情页内容黑白线框稿。

当你想梳理一个商品的电商详情页内容时使用。skill 会先要求你补充产品名、产品定位、目标人群、核心场景和核心卖点，再一步步生成详情页内容。

第一阶段：先收集精准信息

用户先填写完整产品信息表。如果暂时不确定某一项，可以写“待定”，但产品名、目标人群、核心场景和核心卖点建议尽量具体。

第二阶段：再进入共创

产品信息确认后，skill 按固定顺序逐层推进：

1. 核心价值承诺层
2. 痛点锚定层
3. 卖点强化层
4. 使用场景层
5. 产品身份卡
6. 决策收口层

最终会先整理成完整的详情页内容文档，再生成可直接运行的 HTML 黑白线框稿。

## 示例输入

```text
使用 ecommerce-content-wireframe，帮我梳理一款儿童电解质水的详情页内容。

产品名：小K水
产品定位：儿童日常补水与电解质补充饮品
目标人群：3-12岁儿童家长
核心卖点：低糖、好喝、补充电解质、儿童友好
```

## 也可以这样说

```text
帮我梳理一个新品的电商详情页内容。
```

```text
用 ecommerce-content-wireframe，帮我基于完整产品信息生成详情页黑白线框稿。
```

```text
我有一个猫粮产品，帮我先整理详情页内容结构。
```

## 输出特点

- 先收集精准产品信息，再生成详情页内容
- 每一步都给多个选择，并指引用户选择、融合或补充信息
- 关键字段不足时先补齐，非关键细节不足时再做轻量假设并明确标注
- 不编造平台规则、销量、转化率、认证、竞品数据或客户案例
- 输出可以交给运营、内容、设计或商品团队继续执行

## 项目结构

```text
.
├── AGENTS.md
├── commands/
│   └── ecommerce.md
├── skills/
│   └── ecommerce-content-wireframe/
│       └── SKILL.md
├── .claude-plugin/
└── .codex-plugin/
```

## 赛博大福

欢迎关注公众号“赛博大福”。

用 AI 把营销重干一遍。
