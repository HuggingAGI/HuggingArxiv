# 针对多模态大型语言模型的统一生成式和判别式训练

发布时间：2024年10月31日

`LLM应用` `视觉语言模型` `多模态`

> Unified Generative and Discriminative Training for Multi-modal Large Language Models

# 摘要

> 近些年来，视觉语言模型（VLMs）主要在两种范式下进行训练。生成式训练让多模态大型语言模型（MLLMs）能够应对各类复杂任务，然而诸如幻觉和对象辨别能力弱等问题依然存在。判别式训练，以 CLIP 这类模型为代表，在零样本图像 - 文本分类和检索方面表现出众，但在需要细粒度语义区分的复杂场景中却力不从心。本文提出一种统一的方法来应对这些挑战，融合了两种范式的长处。将交错的图像 - 文本序列视为输入样本的通用格式，引入一种结构诱导的训练策略，在输入样本与 MLLM 的隐藏状态间建立语义关系。此策略增强了 MLLM 捕捉全局语义和区分细粒度语义的能力。借助动态时间规整框架内的动态序列对齐，并整合用于细粒度语义区分的新内核，我们的方法有效地平衡了生成式和判别式任务。大量实验表明我们的方法行之有效，在多个生成任务中达到了前沿水平，特别是那些需要认知和辨别能力的任务。此外，在交错和细粒度检索任务中，我们的方法超越了判别式基准。通过采用检索增强生成策略，我们的方法在一个模型内的某些生成任务中进一步提升了性能，为视觉语言建模的未来研究指明了颇具前景的方向。

> In recent times, Vision-Language Models (VLMs) have been trained under two predominant paradigms. Generative training has enabled Multimodal Large Language Models (MLLMs) to tackle various complex tasks, yet issues such as hallucinations and weak object discrimination persist. Discriminative training, exemplified by models like CLIP, excels in zero-shot image-text classification and retrieval, yet struggles with complex scenarios requiring fine-grained semantic differentiation. This paper addresses these challenges by proposing a unified approach that integrates the strengths of both paradigms. Considering interleaved image-text sequences as the general format of input samples, we introduce a structure-induced training strategy that imposes semantic relationships between input samples and the MLLM's hidden state. This approach enhances the MLLM's ability to capture global semantics and distinguish fine-grained semantics. By leveraging dynamic sequence alignment within the Dynamic Time Warping framework and integrating a novel kernel for fine-grained semantic differentiation, our method effectively balances generative and discriminative tasks. Extensive experiments demonstrate the effectiveness of our approach, achieving state-of-the-art results in multiple generative tasks, especially those requiring cognitive and discrimination abilities. Additionally, our method surpasses discriminative benchmarks in interleaved and fine-grained retrieval tasks. By employing a retrieval-augmented generation strategy, our approach further enhances performance in some generative tasks within one model, offering a promising direction for future research in vision-language modeling.

[Arxiv](https://arxiv.org/abs/2411.00304)