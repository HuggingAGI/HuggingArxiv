# LLM 加上 Persona-Plug，摇身一变成为个性化 LLM。

发布时间：2024年09月18日

`LLM应用` `个性化` `语言模型`

> LLMs + Persona-Plug = Personalized LLMs

# 摘要

> 个性化在语言任务中至关重要，因为用户即使需求相同，也可能因个人兴趣而偏好不同输出。为此，我们开发了多种个性化方法，旨在让大型语言模型 (LLM) 生成符合用户偏好的定制内容。然而，为每位用户微调一个独特的 LLM 成本过高，而基于检索的即插即用方法又可能破坏用户历史的连续性，无法全面捕捉用户风格，导致效果不佳。为此，我们提出了一种新型个性化 LLM 模型，\ours{}。该模型通过轻量级插件用户嵌入器模块，为每位用户构建特定嵌入，从而更好地理解和捕捉用户习惯与偏好，生成更个性化的输出，且无需调整模型参数。实验证明，该模型在语言模型个性化 (LaMP) 基准的各项任务中，表现显著优于现有方法。

> Personalization plays a critical role in numerous language tasks and applications, since users with the same requirements may prefer diverse outputs based on their individual interests. This has led to the development of various personalized approaches aimed at adapting large language models (LLMs) to generate customized outputs aligned with user preferences. Some of them involve fine-tuning a unique personalized LLM for each user, which is too expensive for widespread application. Alternative approaches introduce personalization information in a plug-and-play manner by retrieving the user's relevant historical texts as demonstrations. However, this retrieval-based strategy may break the continuity of the user history and fail to capture the user's overall styles and patterns, hence leading to sub-optimal performance. To address these challenges, we propose a novel personalized LLM model, \ours{}. It constructs a user-specific embedding for each individual by modeling all her historical contexts through a lightweight plug-in user embedder module. By attaching this embedding to the task input, LLMs can better understand and capture user habits and preferences, thereby producing more personalized outputs without tuning their own parameters. Extensive experiments on various tasks in the language model personalization (LaMP) benchmark demonstrate that the proposed model significantly outperforms existing personalized LLM approaches.

[Arxiv](https://arxiv.org/abs/2409.11901)