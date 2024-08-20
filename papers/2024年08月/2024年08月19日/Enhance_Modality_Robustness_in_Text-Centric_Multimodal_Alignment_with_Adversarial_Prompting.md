# 通过对抗性提示，提升以文本为核心的多模态对齐中的模态鲁棒性

发布时间：2024年08月19日

`LLM应用` `人工智能` `多模态学习`

> Enhance Modality Robustness in Text-Centric Multimodal Alignment with Adversarial Prompting

# 摘要

> 将不同模态数据转换为通用文本，进而作为大型语言模型的输入，是多模态模型对齐的常用策略，尤其是在成对数据稀缺时。本研究聚焦于以文本为中心的对齐方法，该方法通过将多样输入统一为文本形式，助力下游模型更好地解读多模态信息。我们评估了在噪声、输入顺序变化及模态缺失等挑战下，多模态表示的稳定性和质量，发现现有方法可能削弱下游模型的鲁棒性。为此，我们创新性地提出了一种以文本为中心的对抗训练策略，显著提升了鲁棒性，超越了传统方法及预训练模型。这一发现不仅揭示了该方法在增强多模态表示适应性方面的潜力，也为应对复杂现实场景提供了有力工具。

> Converting different modalities into generalized text, which then serves as input prompts for large language models (LLMs), is a common approach for aligning multimodal models, particularly when pairwise data is limited. Text-centric alignment method leverages the unique properties of text as a modality space, transforming diverse inputs into a unified textual representation, thereby enabling downstream models to effectively interpret various modal inputs. This study evaluates the quality and robustness of multimodal representations in the face of noise imperfections, dynamic input order permutations, and missing modalities, revealing that current text-centric alignment methods can compromise downstream robustness. To address this issue, we propose a new text-centric adversarial training approach that significantly enhances robustness compared to traditional robust training methods and pre-trained multimodal foundation models. Our findings underscore the potential of this approach to improve the robustness and adaptability of multimodal representations, offering a promising solution for dynamic and real-world applications.

[Arxiv](https://arxiv.org/abs/2408.09798)