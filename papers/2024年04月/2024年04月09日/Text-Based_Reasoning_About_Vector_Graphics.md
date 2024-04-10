# 通过文本解读矢量图形的逻辑推理

发布时间：2024年04月09日

`LLM应用` `矢量图形` `多模态感知与推理`

> Text-Based Reasoning About Vector Graphics

# 摘要

> 大型多模态模型在视语言基准测试中表现优异，但在处理精确感知细节的任务时却常常力不从心，例如对比线条长度或走迷宫。尤其在矢量图形的问题回答任务中，这类图像仅由2D形状组成，难度更大。为此，我们设计了视觉描述性语言模型（VDLM），专攻矢量图形的文本推理。VDLM采用可扩展矢量图形（SVG）技术，提供精准的视觉描述，并通过现成的光栅到SVG算法进行编码。鉴于现有语言模型无法直接解读SVG，VDLM引入了一种新的中间符号表示——原始视觉描述（PVD），它包含基本属性及其预测值，实现了与预训练语言模型的衔接。PVD是一种通用的视觉原语描述，适用于所有矢量图形，可通过程序生成的（SVG，PVD）对进行学习，使大型语言模型（LLMs）能够泛化处理复杂推理任务。通过将图像转换为文本形式，我们借助语言模型的力量，实现从SVG到视觉原语的对齐学习，并能应对各种未知问题的回答任务。实验证明，VDLM在矢量图形的低层次多模态感知和推理任务中，展现出比GPT-4V等最先进模型更出色的零次射击性能。此外，我们对VDLM的性能进行了深入分析，证实了其解耦的感知与推理流程带来了更佳的可解释性。项目详情可访问：https://mikewangwzhl.github.io/VDLM/

> While large multimodal models excel in broad vision-language benchmarks, they often struggle with tasks requiring precise perception of low-level visual details, such as comparing line lengths or solving simple mazes. In particular, this failure mode persists in question-answering tasks about vector graphics -- images composed purely of 2D objects and shapes. To address this challenge, we propose the Visually Descriptive Language Model (VDLM), which performs text-based reasoning about vector graphics. VDLM leverages Scalable Vector Graphics (SVG) for a more precise visual description and first uses an off-the-shelf raster-to-SVG algorithm for encoding. Since existing language models cannot understand raw SVGs in a zero-shot setting, VDLM then bridges SVG with pretrained language models through a newly introduced intermediate symbolic representation, Primal Visual Description (PVD), comprising primitive attributes (e.g., shape, position, measurement) with their corresponding predicted values. PVD is task-agnostic and represents visual primitives that are universal across all vector graphics. It can be learned with procedurally generated (SVG, PVD) pairs and also enables the direct use of LLMs for generalization to complex reasoning tasks. By casting an image to a text-based representation, we can leverage the power of language models to learn alignment from SVG to visual primitives and generalize to unseen question-answering tasks. Empirical results show that VDLM achieves stronger zero-shot performance compared to state-of-the-art LMMs, such as GPT-4V, in various low-level multimodal perception and reasoning tasks on vector graphics. We additionally present extensive analyses on VDLM's performance, demonstrating that our framework offers better interpretability due to its disentangled perception and reasoning processes. Project page: https://mikewangwzhl.github.io/VDLM/

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x1.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x2.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/star_ori.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/star_rec.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x3.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x4.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x5.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x6.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x7.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x8.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x9.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x10.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x11.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x12.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x13.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x14.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x15.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x16.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x17.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x18.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x19.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x20.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x21.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x22.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x23.png)

![通过文本解读矢量图形的逻辑推理](../../../paper_images/2404.06479/x24.png)

[Arxiv](https://arxiv.org/abs/2404.06479)