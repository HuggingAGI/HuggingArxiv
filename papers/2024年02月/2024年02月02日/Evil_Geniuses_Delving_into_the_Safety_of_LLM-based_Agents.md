# 恶才探秘：剖析基于LLM的智能体安全之谜在

发布时间：2024年02月02日

`Agent

这篇论文主要探讨了基于大型语言模型（LLM）的代理（Agent）的安全性问题，特别是代理数量、角色定义和攻击级别对LLM代理安全性的影响。论文提出了新的攻击策略和方法，并通过实验评估了这些策略和方法在不同代理系统中的效果。因此，这篇论文更符合Agent分类，因为它专注于代理系统的安全性和攻击性评估，而不是LLM的理论研究或应用开发。` `人工智能安全` `社会工程学`

> Evil Geniuses: Delving into the Safety of LLM-based Agents

# 摘要

> 随着大型语言模型的飞速发展，基于LLM的代理展现出逼真的人类行为和协作能力，但同时也带来了源自交互环境复杂性和工具可用性的独特风险。本文从代理数量、角色定义和攻击级别三个维度深入探讨了LLM代理的安全性。我们首创性地采用基于模板的攻击策略，探究代理数量对LLM的影响。针对交互环境和角色特异性问题，我们提出了“邪恶天才”（EG）攻击方法，该方法能自动生成与原始角色相关的提示，以评估不同角色定义和攻击级别的影响。EG通过红蓝对抗演习，大幅提升了提示的攻击性和与原始角色的相似度。我们在GPT-3.5和GPT-4基础上的CAMEL、Metagpt和ChatDev的评估中，取得了高成功率。广泛的评估和讨论揭示了这些代理的脆弱性，它们更容易产生有害行为，并能生成比LLMs更隐蔽的内容，凸显了安全挑战，并为未来研究指明了方向。我们的代码已公开在https://github.com/T1aNS1R/Evil-Geniuses。

> Rapid advancements in large language models (LLMs) have revitalized in LLM-based agents, exhibiting impressive human-like behaviors and cooperative capabilities in various scenarios. However, these agents also bring some exclusive risks, stemming from the complexity of interaction environments and the usability of tools. This paper delves into the safety of LLM-based agents from three perspectives: agent quantity, role definition, and attack level. Specifically, we initially propose to employ a template-based attack strategy on LLM-based agents to find the influence of agent quantity. In addition, to address interaction environment and role specificity issues, we introduce Evil Geniuses (EG), an effective attack method that autonomously generates prompts related to the original role to examine the impact across various role definitions and attack levels. EG leverages Red-Blue exercises, significantly improving the generated prompt aggressiveness and similarity to original roles. Our evaluations on CAMEL, Metagpt and ChatDev based on GPT-3.5 and GPT-4, demonstrate high success rates. Extensive evaluation and discussion reveal that these agents are less robust, prone to more harmful behaviors, and capable of generating stealthier content than LLMs, highlighting significant safety challenges and guiding future research. Our code is available at https://github.com/T1aNS1R/Evil-Geniuses.

[Arxiv](https://arxiv.org/abs/2311.11855)