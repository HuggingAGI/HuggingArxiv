# X-Reflect：多模态推荐中的交叉反射提示技术

发布时间：2024年08月27日

`LLM应用` `电子商务`

> X-Reflect: Cross-Reflection Prompting for Multimodal Recommendation

# 摘要

> 大型语言模型和多模态模型通过丰富项目描述，显著提升了推荐系统的准确性。然而，现有方法多依赖单一文本提示或基础多模态策略，未能充分挖掘文本与视觉信息的互补潜力。为此，我们提出了创新的交叉反射提示框架（X-Reflect），该框架通过引导多模态模型识别并整合文本与图像间的支持与冲突信息，从而生成更全面、上下文更丰富的项目表示。实验结果显示，X-Reflect在推荐准确性上超越了传统方法。此外，我们还探讨了该框架的泛化性与鲁棒性，为多模态推荐系统的优化提供了新思路。这项研究强调了多模态信息整合的重要性，并提出了一种创新方案，以提升多模态推荐系统中的项目理解能力。

> Large Language Models (LLMs) and Large Multimodal Models (LMMs) have been shown to enhance the effectiveness of enriching item descriptions, thereby improving the accuracy of recommendation systems. However, most existing approaches either rely on text-only prompting or employ basic multimodal strategies that do not fully exploit the complementary information available from both textual and visual modalities. This paper introduces a novel framework, Cross-Reflection Prompting, termed X-Reflect, designed to address these limitations by prompting LMMs to explicitly identify and reconcile supportive and conflicting information between text and images. By capturing nuanced insights from both modalities, this approach generates more comprehensive and contextually richer item representations. Extensive experiments conducted on two widely used benchmarks demonstrate that our method outperforms existing prompting baselines in downstream recommendation accuracy. Additionally, we evaluate the generalizability of our framework across different LMM backbones and the robustness of the prompting strategies, offering insights for optimization. This work underscores the importance of integrating multimodal information and presents a novel solution for improving item understanding in multimodal recommendation systems.

[Arxiv](https://arxiv.org/abs/2408.15172)