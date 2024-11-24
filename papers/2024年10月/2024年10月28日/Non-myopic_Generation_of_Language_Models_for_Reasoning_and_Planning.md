# 用于推理和规划的非短视语言模型生成

发布时间：2024年10月28日

`LLM应用`

> Non-myopic Generation of Language Models for Reasoning and Planning

# 摘要

> 大型语言模型能够将复杂问题拆解为一连串步骤，在推理和规划方面表现出色。尽管在数学解题、编码等众多领域大获成功，然而因其自回归解码固有的短视特性，大型语言模型在保障可靠且最优规划时遭遇难题。此文从最优控制视角重新审视大型语言模型的推理，提出一种全新方法——预测解码，借助模型预测控制提升规划精准度。基于前瞻性轨迹对大型语言模型的分布进行重新加权，预测解码意在减少早期错误，推动非短视规划。我们的实验显示，在数学、编码和代理等众多任务中均有显著提升。另外，预测解码展现出计算效率，在计算资源减少的情况下胜过搜索基线。本研究为优化大型语言模型的规划能力带来启示。

> Large Language Models have demonstrated remarkable abilities in reasoning and planning by breaking down complex problems into sequential steps. Despite their success in various domains like mathematical problem-solving and coding, LLMs face challenges in ensuring reliable and optimal planning due to their inherent myopic nature of autoregressive decoding. This paper revisits LLM reasoning from an optimal-control perspective, proposing a novel method, Predictive-Decoding, that leverages Model Predictive Control to enhance planning accuracy. By re-weighting LLM distributions based on foresight trajectories, Predictive-Decoding aims to mitigate early errors and promote non-myopic planning. Our experiments show significant improvements in a wide range of tasks for math, coding, and agents. Furthermore, Predictive-Decoding demonstrates computational efficiency, outperforming search baselines with reduced computational resources. This study provides insights into optimizing LLM planning capabilities.

[Arxiv](https://arxiv.org/abs/2410.17195)