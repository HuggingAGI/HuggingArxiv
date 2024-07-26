# PEFT-U：高效参数微调，专为个性化用户体验设计

发布时间：2024年07月25日

`LLM应用` `人机交互`

> PEFT-U: Parameter-Efficient Fine-Tuning for User Personalization

# 摘要

> 大型语言模型 (LLMs) 的兴起开启了人机交互的新篇章。以 Chat-GPT 为代表的这些模型，在语言理解上表现出色。但随着 LLMs 的飞速发展，模型个性化的研究却相对滞后。例如 GPT-3 等模型，虽致力于打造通用型模型，却忽视了用户的个性化需求。这种通用方法虽适用于多数场景，却难以满足人类多样性和个体需求的复杂性。为此，我们推出了 PEFT-U 基准，这是一个专为评估和构建用户个性化 NLP 模型而设计的新数据集。\datasetname{} 包含一系列以用户为中心的任务，涵盖多样且个性化的表达，用户的偏好在此可能大相径庭。借助 PEFT-U，我们致力于解决在多样化用户任务中，如何高效个性化 LLMs 以满足特定用户偏好的难题。

> The recent emergence of Large Language Models (LLMs) has heralded a new era of human-AI interaction. These sophisticated models, exemplified by Chat-GPT and its successors, have exhibited remarkable capabilities in language understanding. However, as these LLMs have undergone exponential growth, a crucial dimension that remains understudied is the personalization of these models. Large foundation models such as GPT-3 etc. focus on creating a universal model that serves a broad range of tasks and users. This approach emphasizes the model's generalization capabilities, treating users as a collective rather than as distinct individuals. While practical for many common applications, this one-size-fits-all approach often fails to address the rich tapestry of human diversity and individual needs. To explore this issue we introduce the PEFT-U Benchmark: a new dataset for building and evaluating NLP models for user personalization. \datasetname{} consists of a series of user-centered tasks containing diverse and individualized expressions where the preferences of users can potentially differ for the same input. Using PEFT-U, we explore the challenge of efficiently personalizing LLMs to accommodate user-specific preferences in the context of diverse user-centered tasks.

[Arxiv](https://arxiv.org/abs/2407.18078)