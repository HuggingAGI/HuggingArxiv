# 大规模部署 LLM 驱动的医疗聊天机器人，专家实时参与，带来宝贵经验。

发布时间：2024年09月16日

`LLM应用` `人工智能`

> Learnings from a Large-Scale Deployment of an LLM-Powered Expert-in-the-Loop Healthcare Chatbot

# 摘要

> LLM 在医疗领域应用广泛，但幻觉、信息缺失和偏见等问题影响了其可靠性。为此，研究人员推出了 BYOeB 平台，让开发者能创建经专家验证的 LLM 聊天机器人。首个应用 CataractBot 为白内障手术问题提供专家认证的回答。试点评估虽显示潜力，但样本小且多为定性。我们进行了为期 24 周的大规模部署，涉及 318 名患者和陪同人员，发送了 1,992 条消息，91.71% 的回答经七位专家验证。分析显示，医疗问题远多于物流问题，幻觉极少，84.52% 的医疗答案被专家评为准确。随着知识库的扩展，系统性能提升了 19.02%，减轻了专家负担。这些发现为未来 LLM 聊天机器人的设计提供了宝贵指导。

> Large Language Models (LLMs) are widely used in healthcare, but limitations like hallucinations, incomplete information, and bias hinder their reliability. To address these, researchers released the Build Your Own expert Bot (BYOeB) platform, enabling developers to create LLM-powered chatbots with integrated expert verification. CataractBot, its first implementation, provides expert-verified responses to cataract surgery questions. A pilot evaluation showed its potential; however the study had a small sample size and was primarily qualitative. In this work, we conducted a large-scale 24-week deployment of CataractBot involving 318 patients and attendants who sent 1,992 messages, with 91.71\% of responses verified by seven experts. Analysis of interaction logs revealed that medical questions significantly outnumbered logistical ones, hallucinations were negligible, and experts rated 84.52\% of medical answers as accurate. As the knowledge base expanded with expert corrections, system performance improved by 19.02\%, reducing expert workload. These insights guide the design of future LLM-powered chatbots.

[Arxiv](https://arxiv.org/abs/2409.10354)