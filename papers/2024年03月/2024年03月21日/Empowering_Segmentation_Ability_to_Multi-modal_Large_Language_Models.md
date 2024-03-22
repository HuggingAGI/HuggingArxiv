# 赋予多模态大型语言模型强大的分割技能

发布时间：2024年03月21日

`LLM应用` `图像处理`

> Empowering Segmentation Ability to Multi-modal Large Language Models

> MLLMs能够理解和解析图像-语言信息，并展现出令人瞩目的推理实力。本研究将MLLMs的功能进一步延伸，使其具备图像区域分割能力，这样一来，不仅能够回应图像-语言提示，还能精准定位并划分出语言提示中的复杂问题所关注的图像区域。前期工作LISA虽成功提升分割效果，但发现这样做会较大程度牺牲MLLMs原本的对话理解能力。因此，我们创新性地提出了名为LLaVASeg的MLLMs新框架，该框架采用链式思维引导策略，让MLLMs能够在理解用户查询的基础上，逐步推理出目标区域的关键描述，进而依据对图像的理解提取目标区域的颜色、相对位置等视觉属性，并以此来有效驱动下游分割模型。实验证明，此方法既保留了MLLMs原生的对话功能，又为其赋予了强大的推理分割技能，相关代码已开源至https://github.com/YuqiYang213/LLaVASeg。

> Multi-modal large language models (MLLMs) can understand image-language prompts and demonstrate impressive reasoning ability. In this paper, we extend MLLMs' output by empowering MLLMs with the segmentation ability. The extended MLLMs can both output language responses to the image-language prompts and segment the regions that the complex question or query in the language prompts focuses on. To this end, the existing work, LISA, enlarges the original word embeddings with an additional segment token and fine-tunes dialogue generation and query-focused segmentation together, where the feature of the segment token is used to prompt the segment-anything model. Although they achieve superior segmentation performance, we observe that the dialogue ability decreases by a large margin compared to the original MLLMs. To maintain the original MLLMs' dialogue ability, we propose a novel MLLMs framework, coined as LLaVASeg, which leverages a chain-of-thought prompting strategy to instruct the MLLMs to segment the target region queried by the user. The MLLMs are first prompted to reason about the simple description of the target region from the complicated user query, then extract the visual attributes of the target region according to the understanding of MLLMs to the image. These visual attributes, such as color and relative locations, are utilized to prompt the downstream segmentation model. Experiments show that the proposed method keeps the original dialogue ability and equips the MLLMs' model with strong reasoning segmentation ability. The code is available at https://github.com/YuqiYang213/LLaVASeg.

[Arxiv](https://arxiv.org/abs/2403.14141)