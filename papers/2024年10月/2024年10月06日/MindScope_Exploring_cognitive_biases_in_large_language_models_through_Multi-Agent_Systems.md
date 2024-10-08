# MindScope 项目通过多代理系统，深入研究大型语言模型中的认知偏差。

发布时间：2024年10月06日

`LLM应用` `心理学` `人工智能`

> MindScope: Exploring cognitive biases in large language models through Multi-Agent Systems

# 摘要

> 探究大型语言模型 (LLM) 中的认知偏差，是一项既有趣又具挑战的任务。现有方法在检测能力和偏差类型覆盖上存在局限。为此，我们推出了 'MindScope' 数据集，巧妙融合静态与动态元素。静态部分包含 5,170 个开放式问题，覆盖 72 种认知偏差；动态部分则通过多代理通信框架，生成多轮对话，灵活适应各类心理学实验。我们还提出了一种多代理检测方法，结合 RAG、竞争辩论和强化学习，显著提升检测准确率，比 GPT-4 高出 35.10%。详细代码和资料请访问 https://github.com/2279072142/MindScope。

> Detecting cognitive biases in large language models (LLMs) is a fascinating task that aims to probe the existing cognitive biases within these models. Current methods for detecting cognitive biases in language models generally suffer from incomplete detection capabilities and a restricted range of detectable bias types. To address this issue, we introduced the 'MindScope' dataset, which distinctively integrates static and dynamic elements. The static component comprises 5,170 open-ended questions spanning 72 cognitive bias categories. The dynamic component leverages a rule-based, multi-agent communication framework to facilitate the generation of multi-round dialogues. This framework is flexible and readily adaptable for various psychological experiments involving LLMs. In addition, we introduce a multi-agent detection method applicable to a wide range of detection tasks, which integrates Retrieval-Augmented Generation (RAG), competitive debate, and a reinforcement learning-based decision module. Demonstrating substantial effectiveness, this method has shown to improve detection accuracy by as much as 35.10% compared to GPT-4. Codes and appendix are available at https://github.com/2279072142/MindScope.

[Arxiv](https://arxiv.org/abs/2410.04452)