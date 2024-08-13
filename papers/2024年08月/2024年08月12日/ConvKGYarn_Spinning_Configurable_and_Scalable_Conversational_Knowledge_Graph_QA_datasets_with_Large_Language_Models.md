# ConvKGYarn：借助大型语言模型，打造灵活且可扩展的对话知识图谱问答数据集。

发布时间：2024年08月12日

`LLM应用` `对话系统` `知识图谱`

> ConvKGYarn: Spinning Configurable and Scalable Conversational Knowledge Graph QA datasets with Large Language Models

# 摘要

> 随着大型语言模型和对话助手的迅速发展，我们需要动态、可扩展且可配置的对话数据集来支持训练与评估。这些数据集需适应包括文本和语音在内的多样化用户交互模式，每种模式都有其独特的建模挑战。知识图谱以其结构化和动态演变的特性，为当前和准确的知识提供了理想基础。尽管已有基于人工策划的知识图谱的对话数据集，但它们难以跟上用户信息需求的快速变化。为此，我们提出了 ConvKGYarn，一种可扩展的方法，用于生成最新且可配置的对话 KGQA 数据集。通过定性心理测量分析，我们的方法被证实能生成高质量数据集，与现有流行数据集相媲美，并能大规模覆盖广泛的人类交互配置。我们通过在多样化的对话中测试 LLM，展示了其在基于相同 KG 事实集的不同配置的对话 KGQA 集上的模型行为。研究结果表明，ConvKGYarn 不仅能改进 KGQA 基础，还能有效评估 LLM 的参数知识，为不断演进的对话助手领域提供了一个强有力的解决方案。

> The rapid advancement of Large Language Models (LLMs) and conversational assistants necessitates dynamic, scalable, and configurable conversational datasets for training and evaluation. These datasets must accommodate diverse user interaction modes, including text and voice, each presenting unique modeling challenges. Knowledge Graphs (KGs), with their structured and evolving nature, offer an ideal foundation for current and precise knowledge. Although human-curated KG-based conversational datasets exist, they struggle to keep pace with the rapidly changing user information needs. We present ConvKGYarn, a scalable method for generating up-to-date and configurable conversational KGQA datasets. Qualitative psychometric analyses confirm our method can generate high-quality datasets rivaling a popular conversational KGQA dataset while offering it at scale and covering a wide range of human-interaction configurations. We showcase its utility by testing LLMs on diverse conversations - exploring model behavior on conversational KGQA sets with different configurations grounded in the same KG fact set. Our results highlight the ability of ConvKGYarn to improve KGQA foundations and evaluate parametric knowledge of LLMs, thus offering a robust solution to the constantly evolving landscape of conversational assistants.

[Arxiv](https://arxiv.org/abs/2408.05948)