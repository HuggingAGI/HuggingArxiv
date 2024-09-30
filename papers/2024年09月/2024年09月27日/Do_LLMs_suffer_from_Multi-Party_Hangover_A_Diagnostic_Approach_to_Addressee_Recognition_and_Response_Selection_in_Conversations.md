# 大型语言模型是否在多方对话中“宿醉”？我们提出一种诊断方法，专门用于识别对话接收者并选择恰当的回应。

发布时间：2024年09月27日

`LLM应用` `对话系统` `社交媒体`

> Do LLMs suffer from Multi-Party Hangover? A Diagnostic Approach to Addressee Recognition and Response Selection in Conversations

# 摘要

> 评估多党对话分类系统的性能颇具挑战，因为对话的语言与结构特征紧密相连。传统评估方法常忽略模型在不同结构复杂度下的行为差异。为此，我们设计了一套方法论，专门研究模型在对话特定结构属性上的表现。作为概念验证，我们聚焦于响应选择与收件人识别任务，以揭示模型短板。我们从大型在线 MPC 语料库中精选出结构多样、用户固定的诊断子数据集。同时，我们强调数据最小化，避免使用原始用户名，并提出替代文本消息的方案。结果显示，响应选择更依赖文本内容，而收件人识别则需捕捉对话结构。在零-shot 环境下使用 LLM，我们发现提示变化对任务的敏感性因任务而异。

> Assessing the performance of systems to classify Multi-Party Conversations (MPC) is challenging due to the interconnection between linguistic and structural characteristics of conversations. Conventional evaluation methods often overlook variances in model behavior across different levels of structural complexity on interaction graphs. In this work, we propose a methodological pipeline to investigate model performance across specific structural attributes of conversations. As a proof of concept we focus on Response Selection and Addressee Recognition tasks, to diagnose model weaknesses. To this end, we extract representative diagnostic subdatasets with a fixed number of users and a good structural variety from a large and open corpus of online MPCs. We further frame our work in terms of data minimization, avoiding the use of original usernames to preserve privacy, and propose alternatives to using original text messages. Results show that response selection relies more on the textual content of conversations, while addressee recognition requires capturing their structural dimension. Using an LLM in a zero-shot setting, we further highlight how sensitivity to prompt variations is task-dependent.

[Arxiv](https://arxiv.org/abs/2409.18602)