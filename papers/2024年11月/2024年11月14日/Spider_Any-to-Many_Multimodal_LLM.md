# Spider：任意到多种的多模态大型语言模型

发布时间：2024年11月14日

`LLM应用` `多模态` `语言模型`

> Spider: Any-to-Many Multimodal LLM

# 摘要

> 多模态大型语言模型（MLLMs）作为大型语言模型（LLMs）的拓展应运而生，能够融合各类模态。但任意对任意的 MLLMs 在单个响应中仅能生成“文本 + X”这样的成对模态，比如“文本 + {图像或音频或视频}”。为突破这一局限，我们推出了 Spider，这一全新高效的任意对多模态生成（AMMG）框架，能够生成“文本 + Xs”的任意组合，比如“文本 + {图像和音频和视频}”。为达成高效的 AMMG，我们的 Spider 整合了三个核心部分：用于基础 X 到 X（即任意对任意）模态处理的基础模型、用于掌控多模态解码器以生成 Xs（多模态）内容的新型高效解码器控制器，以及专为生成 Xs 信号提示而设计的任意对多指令模板。为训练 Spider，我们构建了全新的文本格式多模态（TMM）数据集，有助于学习 AMMG 所需的 X 到 Xs（即任意对多）能力。最终，训练有素的 Spider 生成了首个 X 到 Xs 多模态数据集，为未来 AMMG 任务的研究增强了潜力。总之，此项工作不但拓展了多模态交互的边界，还为推动该领域发展提供了丰富的数据支持。

> Multimodal LLMs (MLLMs) have emerged as an extension of Large Language Models (LLMs), enabling the integration of various modalities. However, Any-to-Any MLLMs are limited to generating pairwise modalities 'Text + X' within a single response, such as Text + {Image or Audio or Video}. To address this limitation, we introduce Spider, a novel efficient Any-to-Many Modalities Generation (AMMG) framework, which can generate an arbitrary combination of modalities 'Text + Xs', such as Text + {Image and Audio and Video}. To achieve efficient AMMG, our Spider integrates three core components: a Base Model for basic X-to-X (i.e., Any-to-Any) modality processing, a novel Efficient Decoders-Controller for controlling multimodal Decoders to generate Xs (many-modal) contents, and an Any-to-Many Instruction Template designed for producing Xs signal prompts. To train Spider, we constructed a novel Text-formatted Many-Modal (TMM) dataset, which facilitates the learning of the X-to-Xs (i.e., Any-to-Many) capability necessary for AMMG. Ultimately, the well-trained Spider generates a pseudo X-to-Xs dataset, the first-ever X-to-Xs many-modal dataset, enhancing the potential for AMMG task in future research. Overall, this work not only pushes the boundary of multimodal interaction but also provides rich data support for advancing the field.

[Arxiv](https://arxiv.org/abs/2411.09439)