# 将销售员的对话策略融入大型语言模型，并运用思维链推理，这一方法对于增强模型处理复杂对话任务的能力至关重要。

发布时间：2024年04月29日

`Agent` `对话系统`

> Injecting Salesperson's Dialogue Strategies in Large Language Models with Chain-of-Thought Reasoning

# 摘要

> 近期对话系统研究主要分为两大类：任务导向型（TOD）和开放领域（如闲聊）对话。TOD系统致力于协助用户完成特定任务，而开放领域系统则更注重营造引人入胜的对话体验。但在现实情境中，用户的真实意图往往是在交流过程中逐步显现。最近的一项研究推出了SalesBot，这是一个模拟从闲聊向任务导向场景过渡的对话系统，用以培养销售人才。然而，初始数据集在过渡自然度和长对话连贯性方面存在不足，影响了销售与客户之间的互动流畅性。为改善这些问题，本文提出了升级版的SalesBot 2.0数据集，它通过精心设计的提示，借助大型语言模型（LLMs）中的常识知识。同时，我们还引入了一个创新模型——SalesAgent，该模型基于销售人员的互动数据，采用思维链（CoT）推理方法进行训练。SalesAgent在话题转换、用户意图理解以及策略选择上表现出色。通过多样化用户模拟的实验，我们验证了该方法在LLMs中控制对话策略的有效性。SalesBot 2.0不仅提升了对话的连贯性，还减少了冲突性，有助于提高销售与客户互动的模型学习效果。

> Recent research in dialogue systems and corpora has focused on two main categories: task-oriented (TOD) and open-domain (chit-chat) dialogues. TOD systems help users accomplish specific tasks, while open-domain systems aim to create engaging conversations. However, in real-world scenarios, user intents are often revealed during interactions. A recent study introduced SalesBot, which simulates dialogues transitioning from chit-chat to task-oriented scenarios to train sales agents. Unfortunately, the initial data lacked smooth transitions and coherent long-turn dialogues, resulting in poor naturalness in sales-customer interactions. To address these issues, this paper presents SalesBot 2.0, an improved dataset. It leverages commonsense knowledge from large language models (LLMs) through strategic prompting. Additionally, we introduce a novel model called SalesAgent, trained on salesperson's interactions, using chain-of-thought (CoT) reasoning. This model excels in transitioning topics, understanding user intents, and selecting appropriate strategies. Experiments using diverse user simulations validate the effectiveness of our method in controlling dialogue strategies in LLMs. Furthermore, SalesBot 2.0 enhances coherence and reduces aggression, facilitating better model learning for sales-customer interactions.

[Arxiv](https://arxiv.org/abs/2404.18564)