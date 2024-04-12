# 本文综述了视觉-语言模型的最新研究方法，并展望了未来的发展趋势。通过深入分析，我们旨在揭示这一领域的潜力与挑战，为未来的研究提供方向。

发布时间：2024年02月20日

`LLM理论` `视觉-语言模型` `多模态学习`

> Exploring the Frontier of Vision-Language Models: A Survey of Current Methodologies and Future Directions

# 摘要

> 大型语言模型（LLMs）引领了人工智能革命的新方向。尽管如此，LLMs主要处理文本信息，这限制了它们的应用范围。为了突破这一瓶颈，研究者们开始将视觉功能融入LLMs，催生了视觉-语言模型（VLMs）。VLMs在图像描述、视觉问答等复杂任务中大放异彩。本文通过深入调查，将VLMs分为三大类：专注于视觉-语言理解的模型、将多模态输入转换为单模态（文本）输出的模型，以及能够处理和生成多模态输入输出的模型。我们根据它们处理和生成不同数据模态的能力，对每个模型进行了详尽的剖析，包括其基础架构、训练数据来源、优势和局限，让读者对VLMs的核心组件有透彻的认识。我们还评估了VLMs在多个基准数据集上的表现，以期为读者呈现VLMs多样化领域的细致图景。同时，我们指出了未来研究的可能方向，期待在这一充满活力的领域中取得更多突破和发展。

> The advent of Large Language Models (LLMs) has significantly reshaped the trajectory of the AI revolution. Nevertheless, these LLMs exhibit a notable limitation, as they are primarily adept at processing textual information. To address this constraint, researchers have endeavored to integrate visual capabilities with LLMs, resulting in the emergence of Vision-Language Models (VLMs). These advanced models are instrumental in tackling more intricate tasks such as image captioning and visual question answering. In our comprehensive survey paper, we delve into the key advancements within the realm of VLMs. Our classification organizes VLMs into three distinct categories: models dedicated to vision-language understanding, models that process multimodal inputs to generate unimodal (textual) outputs and models that both accept and produce multimodal inputs and outputs.This classification is based on their respective capabilities and functionalities in processing and generating various modalities of data.We meticulously dissect each model, offering an extensive analysis of its foundational architecture, training data sources, as well as its strengths and limitations wherever possible, providing readers with a comprehensive understanding of its essential components. We also analyzed the performance of VLMs in various benchmark datasets. By doing so, we aim to offer a nuanced understanding of the diverse landscape of VLMs. Additionally, we underscore potential avenues for future research in this dynamic domain, anticipating further breakthroughs and advancements.

![本文综述了视觉-语言模型的最新研究方法，并展望了未来的发展趋势。通过深入分析，我们旨在揭示这一领域的潜力与挑战，为未来的研究提供方向。](../../../paper_images/2404.07214/VLM.png)

[Arxiv](https://arxiv.org/abs/2404.07214)