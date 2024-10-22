# 用大型语言模型解读图神经网络：从反事实视角探索分子属性预测

发布时间：2024年10月19日

`LLM应用` `药物发现` `人工智能`

> Explaining Graph Neural Networks with Large Language Models: A Counterfactual Perspective for Molecular Property Prediction

# 摘要

> 近年来，图神经网络 (GNN) 在分子属性预测任务中表现出色，如毒性分析。然而，GNN 的黑箱特性使其在高风险决策场景（如药物发现）中的输出令人担忧。为此，图反事实解释 (GCE) 应运而生，旨在提升 GNN 的透明度。但现有 GCE 方法往往忽视领域特定知识，导致输出难以理解。为此，我们提出 LLM-GCE 方法，利用大型语言模型 (LLM) 解释 GNN 的分子属性预测。我们通过自编码器从反事实文本对 (CTP) 生成反事实图拓扑，并引入 CTP 动态反馈模块，减少 LLM 幻觉，提供更忠实的指导。实验证明 LLM-GCE 性能优越。代码已发布于 https://github.com/YinhanHe123/new_LLM4GNNExplanation。

> In recent years, Graph Neural Networks (GNNs) have become successful in molecular property prediction tasks such as toxicity analysis. However, due to the black-box nature of GNNs, their outputs can be concerning in high-stakes decision-making scenarios, e.g., drug discovery. Facing such an issue, Graph Counterfactual Explanation (GCE) has emerged as a promising approach to improve GNN transparency. However, current GCE methods usually fail to take domain-specific knowledge into consideration, which can result in outputs that are not easily comprehensible by humans. To address this challenge, we propose a novel GCE method, LLM-GCE, to unleash the power of large language models (LLMs) in explaining GNNs for molecular property prediction. Specifically, we utilize an autoencoder to generate the counterfactual graph topology from a set of counterfactual text pairs (CTPs) based on an input graph. Meanwhile, we also incorporate a CTP dynamic feedback module to mitigate LLM hallucination, which provides intermediate feedback derived from the generated counterfactuals as an attempt to give more faithful guidance. Extensive experiments demonstrate the superior performance of LLM-GCE. Our code is released on https://github.com/YinhanHe123/new\_LLM4GNNExplanation.

[Arxiv](https://arxiv.org/abs/2410.15165)