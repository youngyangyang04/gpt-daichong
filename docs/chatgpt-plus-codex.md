---
title: ChatGPT Plus和Codex是什么关系？模型、额度与付费说明
description: 讲清ChatGPT Plus与Codex的关系，更新GPT-6 Astra、GPT-6.1 Sol、GPT-6.1 Terra、Luna、Free与Go可用条件、订阅额度和API计费区别。
keywords:
  - ChatGPT Plus和Codex的关系
  - Codex是什么
  - Codex要单独付费吗
  - Codex怎么用
  - ChatGPT Plus能用Codex吗
  - OpenAI Codex
  - Codex CLI
  - codex编程智能体
  - GPT-6.1 Sol
  - GPT-6 Astra Sol Luna
  - Codex IDE扩展
  - ChatGPT Plus充值
  - 国内开通ChatGPT Plus
  - 支付宝充值ChatGPT
  - ChatGPT代充
  - ChatGPT Plus订阅
tags:
  - ChatGPT Plus
  - Codex
  - OpenAI
  - AI编程工具
  - ChatGPT充值
---

# ChatGPT Plus和Codex是什么关系？模型、额度与付费说明

> **2026年11月16日更新：已核对官方模型与套餐说明；支付方式、可用地区和实际额度以账号页面为准。**

**Plus包含Codex使用权益，但“Codex必须先买Plus”和“使用Codex永远不额外收费”都不准确。** 免费入口、订阅额度、额外credits和API认证需要分开看。

## Codex是什么？

Codex是OpenAI的编程智能体，可以读取项目、修改文件、运行命令和测试。桌面端、CLI、IDE和云端的执行环境不同：本地任务使用本机环境，云任务使用配置好的云环境，并非所有任务都在云沙箱里运行。

## Plus包含什么？免费账号能用吗？

Plus包含相应的Codex权益；Free、Go也有受开放进度限制的桌面端Luna入口。不同套餐的模型、客户端和额度并不相同，免费账号不应被描述为“完全不能用”。

| 使用方式 | 费用关系 |
| --- | --- |
| ChatGPT账号登录 | 使用套餐对应的模型与用量 |
| 购买额外credits | 按账号支持的规则扩展用量，可能额外付费 |
| API Key认证 | 按API账单计费，不是扣订阅内的API余额 |

CLI和IDE支持ChatGPT登录或API Key认证；不能只凭“用了CLI”判断走哪条账单。

## Codex用哪些模型？

当前模型包括GPT-6 Astra、GPT-6.1 Sol、GPT-6.1 Terra、GPT-6 Sol与GPT-6 Luna。GPT-6.1 Sol可用于复杂编程和持续工作，Luna适合明确、重复的任务；可见选项以账号和客户端为准。

GPT-6.1 Sol、GPT-6.1 Terra、GPT-6 Sol、GPT-6 Luna在Work和Codex中提供，不在Chat中提供。

### Plus用户能用GPT-6.1 Terra吗？

根据[10月26日官方更新](https://learn.chatgpt.com/docs/changelog)，Terra面向Plus、Pro、Business、Enterprise和Edu的Work/Codex开放，侧重图像理解、电脑操作和专业工作。已有Plus用户先查看当前入口与模型列表，无需仅为Terra再买一份订阅。

在ChatGPT桌面端或网页版Work的Advanced模型列表查看GPT-6.1 Terra；Work移动端也支持。具体可见性受账号、开放进度与工作区设置影响。模型可用与是否已授权浏览器、桌面和应用操作是不同条件。

在CLI中可用`/model`查看当前可选模型。模型切换不会自动授予文件访问、网络或其他执行权限。

## GPT-5.5还能在Codex里选吗？

GPT-5.5已于2026年10月14日从ChatGPT登录的Codex中退役；API和API Key认证会话不受这次退役影响。旧配置中固定使用该模型的，需要改成账号当前可用的模型。

## Plus的额度怎么计算？

任务复杂度、上下文、所选模型与运行方式都会影响消耗。Work与Codex共享相应用量，不能把套餐理解为固定次数的所有任务通票。到用量页看余额和重置时间，再决定等待重置、加购或升级。

Pro也不只一个200美元档：当前有100、200、500美元月费档位，详见[Pro充值教程](./chatgpt-pro-recharge-guide.md)。最新Pro规则已取消Pro 200此前宣布的额度削减，Pro 100、Pro 500的Work/Codex额度也增加；Plus额度不变，见[官方说明](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)。

符合条件的Pro另有可激活的API credits福利，但它不增加ChatGPT或登录Codex的用量，也不覆盖通过API Key使用Codex的用量。不要把订阅额度、额外credits和API组织余额混为一谈，详见[福利规则](https://help.openai.com/en/articles/20001626-api-credits-benefit-for-eligible-chatgpt-subscriptions)。

## 怎样开始使用？

1. 选择账号可用的Codex客户端或官方入口。
2. 确认使用ChatGPT登录还是API Key认证。
3. 查看当前模型和剩余用量，先完成一个小任务。
4. 需要更高权益时，再到官方套餐页比较升级选项。

## 国内付款怎么处理？

已有Plus时通常先登录验证权益，无需再买一份“Codex会员”。需要订阅可看国内充值教程。文中的[第三方卡密入口](https://payai.plus/)为独立服务，购买前应核对授权与到账条件，卡密属于第三方交付凭证。

## 常见问题

**Plus能用Codex，为什么还出现付费提示？**

检查是否耗尽用量、误选API认证，或正在使用需要额外credits的能力。不要直接重复购买订阅。

**第三方充值会改变Codex模型能力吗？**

判断依据是账号最终到账的套餐和实际权限，不是商家宣传的模型名称。应在官方产品内核验。
