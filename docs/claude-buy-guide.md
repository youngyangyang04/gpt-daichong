---
description: 更新Claude Fable 5.1、Opus 5.5、Sonnet 5.5和Haiku 5.5，讲清Pro、Max、API付款区别，纠正PayPal及Claude Code CLI计费误区。
keywords:
  - claude国内充值
  - claude付款
  - Claude国内付款
  - 苹果礼品卡充值购买claude
  - 怎么给Claude API充值
  - Claude Code代充
  - 如何充值Claude Code
  - Claude Code能支付人民币吗
  - Claude Code苹果手机购买
  - 国内购买Claude
  - Claude Pro订阅
  - Claude订阅费用
  - Claude充值方法
  - Claude Max充值
  - Claude API购买
  - 国内支付Claude
  - Claude代充
  - Claude Fable 5.1
  - Claude Opus 5.5
  - Anthropic充值
  - Claude订阅
  - 国内怎么买Claude
tags:
  - Claude充值
  - Claude付款
  - Claude Pro
  - Claude Code
  - AI工具充值
title: Claude国内充值全指南｜Pro、Max、API与Claude Code付款
---

# Claude国内充值全指南｜Pro、Max、API与Claude Code付款

> **2026年10月20日更新：已核对官方模型与套餐说明；支付方式、可用地区和实际额度以账号页面为准。**

给Claude付款前，先确认买的是聊天与Claude Code订阅，还是程序调用所需的API用量。它们不能按同一条充值流程处理。

## 2026年10月，Claude有哪些当前模型？

官方模型目录目前列出 **Claude Fable 5.1、Opus 5.5、Sonnet 5.5、Haiku 5.5**。它们分别面向复杂推理与长任务、编程及知识工作、速度与能力平衡、低延迟高频任务。

API 中存在某个模型，不代表每个 Claude 订阅都能无限使用它。聊天和 Claude Code 内能选哪些模型、还剩多少额度，要看自己的账号页面。

## Claude Pro、Max和API有什么区别？

| 产品 | 网页端价格 | 主要用途 |
| --- | --- | --- |
| Free | 免费 | 先试用，再判断是否需要付费 |
| Pro | 月付20美元；年付200美元 | 更多使用量，包含Claude Code |
| Max 5x | 100美元/月 | 比Pro更高的会话用量 |
| Max 20x | 200美元/月 | 个人重度使用，不是团队席位套餐 |
| Claude API | 按实际调用计费 | 在程序或服务中调用模型 |

上表为官方网页标价，税费和移动端价格可能不同。5x、20x 比较的是相对 Pro 的会话用量，仍有其他用量限制，不代表智能提升倍数或无限使用。

## Claude支持哪些付款方式？PayPal能用吗？

Claude 官方接受符合要求的信用卡和借记卡；**不接受 PayPal、Venmo 这类第三方支付处理服务**。发卡地区、账单地址、余额和 3DS 验证都可能影响付款，海外卡也不保证成功。

人民币付款给代充商、用人民币购买礼品卡，与直接在 Claude 官网使用人民币结账是不同的事情。官方或商店实际提供什么币种和付款工具，应看自己的结账页面。

## 苹果手机和安卓能怎么订阅？

在所在地区能下载的官方 App 内查看可用订阅；付款前核对商店价格、税费、续费周期和目标账号。礼品卡必须与商店地区匹配，余额是否可用于该订阅以商店结账结果为准。

商店地区应符合实际使用条件；礼品卡面值需覆盖结账显示的订阅费和税费。App Store、Google Play 与网页端价格和套餐可能不同。

已有网页订阅时，先检查原订阅状态，避免又在 App 内开一份。通过商店订阅的，应到对应商店管理续费和取消。

## 第三方卡密充值怎么操作？

没有适用的官方支付方式时，部分用户会考虑人民币卡密服务。文中保留的 [第三方充值入口](https://payai.plus/) 是独立服务，与 OpenAI、Anthropic 官方订阅入口不同。

1. 核对商品是个人订阅、共享账号还是其他服务，以及对应套餐和时长。
2. 确认当前人民币报价、付款方式、账号条件和失败退款规则后再下单。
3. 获取卡密后，先核对充值页面域名与授权要求，再按指引操作。
4. 完成后回到产品自己的订阅页面，检查套餐和有效期，保存订单记录。

**卡密是第三方交付凭证。** 购买前应了解授权方式，不向不可信页面提供密码、验证码、Cookie、Session Token 或 API Key。本次更新核对了公开资料，未重新完成第三方付款实测。

旧版充值页面仅作为历史示意，不代表当前套餐、价格或授权步骤：

![Claude第三方充值历史页面](../assets/images/2026-06-11_19-42-59.jpg?v=20261022)

![Claude第三方卡密历史订单](../assets/images/2026-06-11_19-47-48.jpg?v=20261022)

## Claude Code CLI一定要充值API吗？

**不一定。终端和支持的 IDE 都可以登录 Claude Pro/Max 账号使用订阅额度**，并非只有网页端能用订阅。选择 API/Console 认证时，才按对应 API 账单计费。

已经有 Pro/Max 时，先检查 Claude Code 当前登录的账号和计费方式。环境中的 `ANTHROPIC_API_KEY` 可能让请求走 API 计费；需要切换时，按官方说明使用 `/login` 重新选择认证方式。

## Claude API在哪里充值？

使用 Claude Console账单页，在具有 Admin 或 Billing 权限的组织中购买 credits，并检查用量和自动充值设置。App Store 礼品卡不能直接兑换成 Console 余额。

Pro 订阅额度不能当作 API 余额。当前 Max、Team 另有月度 API credits 权益，需要关联 Console 组织并按规则领取；这部分 credits 有到期和用途限制，不能拿来支付 Claude Code 或 Claude App 的额外用量。领取和使用规则请查看对应官方说明。

## 常见问题

**Claude Pro和ChatGPT Plus选哪个？**

用自己的真实任务比较写作、文件分析、代码修改和用量。Claude Code与Codex都应看任务结果、客户端和套餐限制，不宜直接宣称某一个永远是“最强Agent”。

**苹果手机开了Pro，电脑CLI能用吗？**

在CLI登录同一个有效Pro账号并选择订阅认证即可使用对应权益，无需仅因换成CLI就另充API。

**代充一定不会影响账号吗？**

不能保证。应核对支付来源、授权和订阅条件；“激活码”这个名称本身不能证明官方背书。

## 付款前后要检查什么？

- 不把密码、验证码、Cookie、Session Token 或 API Key 发给客服或不可信页面。
- 核对个人账号、工作区、套餐名称和有效期，避免充错账号。
- 不把“自助充值”理解成官方授权或零风险保证。
- 保存订单与实际到账记录；续费和退款要按原付款渠道处理。
