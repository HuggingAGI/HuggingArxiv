# 视觉语言模型究竟能捕捉到多少图像细节？

发布时间：2024年08月07日

`LLM应用` `计算机视觉`

> How Well Can Vision Language Models See Image Details?

# 摘要

> 基于LLM的视觉-语言模型（VLMs）在多种视觉-语言任务中表现出色，但我们对其在细节层面的图像识别能力仍知之甚少。为此，我们设计了像素值预测任务（PVP），旨在探究VLMs的细节识别能力，并助其感知更丰富的图像细节。这些模型通常由冻结的CLIP视觉编码器、大型语言模型及连接模块构成。通过微调PVP任务，我们发现：仅调整连接模块和LLM，VLMs难以精确预测像素值；而当视觉编码器也参与适应时，预测精度大幅提升。研究还表明，将像素值预测纳入VLM预训练，并优化视觉编码器，能显著增强VLMs在需要精细图像理解的下游任务中的表现，如图像分割（cIoU平均提升10.19）和游戏决策（两游戏得分分别提升80.34和70.54）。

> Large Language Model-based Vision-Language Models (LLM-based VLMs) have demonstrated impressive results in various vision-language understanding tasks. However, how well these VLMs can see image detail beyond the semantic level remains unclear. In our study, we introduce a pixel value prediction task (PVP) to explore "How Well Can Vision Language Models See Image Details?" and to assist VLMs in perceiving more details. Typically, these models comprise a frozen CLIP visual encoder, a large language model, and a connecting module. After fine-tuning VLMs on the PVP task, we find: 1) existing VLMs struggle to predict precise pixel values by only fine-tuning the connection module and LLM; and 2) prediction precision is significantly improved when the vision encoder is also adapted. Additionally, our research reveals that incorporating pixel value prediction as one of the VLM pre-training tasks and vision encoder adaptation markedly boosts VLM performance on downstream image-language understanding tasks requiring detailed image perception, such as referring image segmentation (with an average +10.19 cIoU improvement) and video game decision making (with average score improvements of +80.34 and +70.54 on two games, respectively).

[Arxiv](https://arxiv.org/abs/2408.03940)