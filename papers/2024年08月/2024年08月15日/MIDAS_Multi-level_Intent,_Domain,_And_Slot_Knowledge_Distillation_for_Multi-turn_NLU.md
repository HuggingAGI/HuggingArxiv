# MIDAS：多轮自然语言理解中的多级意图、领域与槽知识蒸馏

发布时间：2024年08月15日

`LLM应用` `人工智能`

> MIDAS: Multi-level Intent, Domain, And Slot Knowledge Distillation for Multi-turn NLU

# 摘要

> 尽管 LLM 能生成连贯文本，但常难以理解用户查询的深层意图。相比之下，NLU 模型通过解析用户输入的关键信息，实现更精准的交互。现有 NLU 模型多聚焦于单轮对话的语义解析，而真实对话多为多轮复杂交流。为此，我们提出 MIDAS 方法，通过多级知识蒸馏优化多轮对话理解。我们构建了针对不同对话层次的教师模型，并提出多教师损失策略，协同指导学生模型，显著提升多轮对话的解析能力。实验证明，MIDAS 有效提升了 NLU 模型在复杂对话场景中的表现，为 NLU 领域的发展开辟了新路径。

> Although Large Language Models(LLMs) can generate coherent and contextually relevant text, they often struggle to recognise the intent behind the human user's query. Natural Language Understanding (NLU) models, however, interpret the purpose and key information of user's input to enable responsive interactions. Existing NLU models generally map individual utterances to a dual-level semantic frame, involving sentence-level intent and word-level slot labels. However, real-life conversations primarily consist of multi-turn conversations, involving the interpretation of complex and extended dialogues. Researchers encounter challenges addressing all facets of multi-turn dialogue conversations using a unified single NLU model. This paper introduces a novel approach, MIDAS, leveraging a multi-level intent, domain, and slot knowledge distillation for multi-turn NLU. To achieve this, we construct distinct teachers for varying levels of conversation knowledge, namely, sentence-level intent detection, word-level slot filling, and conversation-level domain classification. These teachers are then fine-tuned to acquire specific knowledge of their designated levels. A multi-teacher loss is proposed to facilitate the combination of these multi-level teachers, guiding a student model in multi-turn dialogue tasks. The experimental results demonstrate the efficacy of our model in improving the overall multi-turn conversation understanding, showcasing the potential for advancements in NLU models through the incorporation of multi-level dialogue knowledge distillation techniques.

[Arxiv](https://arxiv.org/abs/2408.08144)