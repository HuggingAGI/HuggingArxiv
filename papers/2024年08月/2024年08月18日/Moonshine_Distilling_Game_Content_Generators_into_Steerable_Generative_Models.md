# Moonshine：精炼游戏内容生成器，打造可控的生成模型

发布时间：2024年08月18日

`LLM应用` `人工智能`

> Moonshine: Distilling Game Content Generators into Steerable Generative Models

# 摘要

> PCGML虽提升了游戏内容创作，但可控性和训练数据有限的问题仍待解决。本研究通过提炼构建性PCG算法，打造出可控的PCGML模型。首先，我们用构建性算法生成大量内容，并借助大型语言模型（LLM）进行标注。随后，我们利用这些合成标签，驱动两个PCGML模型（扩散模型和五美元模型）进行特定内容生成。这一神经网络提炼过程，既确保生成内容与原始算法一致，又通过纯文本实现可控性。我们将这种文本条件化的PCGML视为文本到游戏地图（T2M）任务，为文本到图像多模态任务提供了新思路。通过对比提炼模型与基准算法，我们验证了提炼方法在生成内容多样性、准确性和质量方面的有效性。

> Procedural Content Generation via Machine Learning (PCGML) has enhanced game content creation, yet challenges in controllability and limited training data persist. This study addresses these issues by distilling a constructive PCG algorithm into a controllable PCGML model. We first generate a large amount of content with a constructive algorithm and label it using a Large Language Model (LLM). We use these synthetic labels to condition two PCGML models for content-specific generation, a diffusion model and the five-dollar model. This neural network distillation process ensures that the generation aligns with the original algorithm while introducing controllability through plain text. We define this text-conditioned PCGML as a Text-to-game-Map (T2M) task, offering an alternative to prevalent text-to-image multi-modal tasks. We compare our distilled models with the baseline constructive algorithm. Our analysis of the variety, accuracy, and quality of our generation demonstrates the efficacy of distilling constructive methods into controllable text-conditioned PCGML models.

[Arxiv](https://arxiv.org/abs/2408.09594)