# VILA-M3：借助医学专家知识强化视觉语言模型

发布时间：2024年11月19日

`LLM应用` `计算机视觉`

> VILA-M3: Enhancing Vision-Language Models with Medical Expert Knowledge

# 摘要

> 通才型视觉语言模型（VLMs）在计算机视觉领域成果斐然，然而在医疗保健这类专业领域却表现欠佳，毕竟这里需要专业知识。在传统计算机视觉任务中，有创意或近似的答案或许能行，但在医疗保健领域，精度才是关键。当下像 Gemini 和 GPT-4o 这样的大型多模态模型，因依赖所记忆的互联网知识，而非医疗保健所需的精细专业知识，所以难以胜任医疗任务。VLMs 通常历经三个训练阶段：视觉预训练、视觉语言预训练以及指令微调（IFT）。IFT 通常会混合通用数据和医疗保健数据来应用。相较而言，我们认为对于医疗 VLMs，有必要增加专门的 IFT 第四阶段，此阶段聚焦于医疗数据，并涵盖来自领域专家模型的信息。为医疗用途开发的领域专家模型意义重大，因为它们是针对特定临床任务进行训练的，比如通过分割和分类来检测肿瘤和判别异常，它们能学习医疗数据的细粒度特征——这些特征往往过于复杂，VLM 尤其在放射学中难以有效捕捉。本文引入了一种新的框架 VILA-M3，用于医疗 VLMs，其借助专家模型来利用领域知识。通过我们的实验，展示出了更优的最先进（SOTA）性能，相比之前的 SOTA 模型 Med-Gemini 平均提升约 9％，较针对特定任务训练的模型平均提高约 6％。我们的方法凸显了领域专业知识在为医疗应用打造精准、可靠的 VLMs 中的重要性。

> Generalist vision language models (VLMs) have made significant strides in computer vision, but they fall short in specialized fields like healthcare, where expert knowledge is essential. In traditional computer vision tasks, creative or approximate answers may be acceptable, but in healthcare, precision is paramount.Current large multimodal models like Gemini and GPT-4o are insufficient for medical tasks due to their reliance on memorized internet knowledge rather than the nuanced expertise required in healthcare. VLMs are usually trained in three stages: vision pre-training, vision-language pre-training, and instruction fine-tuning (IFT). IFT has been typically applied using a mixture of generic and healthcare data. In contrast, we propose that for medical VLMs, a fourth stage of specialized IFT is necessary, which focuses on medical data and includes information from domain expert models. Domain expert models developed for medical use are crucial because they are specifically trained for certain clinical tasks, e.g. to detect tumors and classify abnormalities through segmentation and classification, which learn fine-grained features of medical data$-$features that are often too intricate for a VLM to capture effectively especially in radiology. This paper introduces a new framework, VILA-M3, for medical VLMs that utilizes domain knowledge via expert models. Through our experiments, we show an improved state-of-the-art (SOTA) performance with an average improvement of ~9% over the prior SOTA model Med-Gemini and ~6% over models trained on the specific tasks. Our approach emphasizes the importance of domain expertise in creating precise, reliable VLMs for medical applications.

[Arxiv](https://arxiv.org/abs/2411.12915)