# 通过模拟未来对话轮次，教导大型语言模型如何提出澄清问题。

发布时间：2024年10月17日

`LLM应用` `人工智能`

> Modeling Future Conversation Turns to Teach LLMs to Ask Clarifying Questions

# 摘要

> 大型语言模型 (LLM) 在面对模糊的用户请求时，最佳策略往往是提出澄清问题以获取更多信息。然而，现有的 LLM 往往预设单一解释，导致用户意图被误解。我们认为，这源于当前仅基于先前上下文评估回应的偏好数据标注实践。为此，我们提出通过模拟未来对话的预期结果来分配偏好标签，使 LLM 学会在适当时候提出澄清问题。在开放域问答实验中，我们发现使用新方法训练的 LLM 在提出澄清问题方面表现更佳，F1 得分提高了 5%，能更准确地捕捉用户的真实意图。

> Large language models (LLMs) must often respond to highly ambiguous user requests. In such cases, the LLM's best response may be to ask a clarifying question to elicit more information. We observe existing LLMs often respond by presupposing a single interpretation of such ambiguous requests, frustrating users who intended a different interpretation. We speculate this is caused by current preference data labeling practice, where LLM responses are evaluated only on their prior contexts. To address this, we propose to assign preference labels by simulating their expected outcomes in the future turns. This allows LLMs to learn to ask clarifying questions when it can generate responses that are tailored to each user interpretation in future turns. In experiments on open-domain QA, we compare systems that trained using our proposed preference labeling methods against standard methods, which assign preferences based on only prior context. We evaluate systems based on their ability to ask clarifying questions that can recover each user's interpretation and expected answer, and find that our training with our proposed method trains LLMs to ask clarifying questions with a 5% improvement in F1 measured against the answer set from different interpretations of each query

[Arxiv](https://arxiv.org/abs/2410.13788)