# CtrlSynth：一种可控的图像文本合成工具，专为高效多模态学习设计。

发布时间：2024年10月15日

`LLM应用` `计算机视觉` `人工智能`

> CtrlSynth: Controllable Image Text Synthesis for Data-Efficient Multimodal Learning

# 摘要

> 预训练鲁棒的视觉或多模态基础模型（如CLIP）依赖于可能存在噪声、对齐问题和长尾分布的大规模数据集。尽管先前的工作通过生成合成样本展示了增强数据集的潜力，但这些方法仅限于特定领域的即席用例，且由于缺乏对合成过程的细粒度控制，数据多样性有限。本文设计了可控的图像-文本合成管道CtrlSynth，通过将图像视觉语义分解为基础元素，并应用用户指定的控制策略（如移除、添加或替换操作），重新组合以合成图像或文本。CtrlSynth允许用户通过定制控制策略以细粒度方式控制数据合成，并利用预训练基础模型（如大型语言模型或扩散模型）的能力，生成自然且多样化的合成样本。作为一个闭环、无需训练且模块化的框架，CtrlSynth易于支持不同预训练模型。实验表明，CtrlSynth显著提升了CLIP模型在零样本分类、图像-文本检索和组合推理任务中的性能。

> Pretraining robust vision or multimodal foundation models (e.g., CLIP) relies on large-scale datasets that may be noisy, potentially misaligned, and have long-tail distributions. Previous works have shown promising results in augmenting datasets by generating synthetic samples. However, they only support domain-specific ad hoc use cases (e.g., either image or text only, but not both), and are limited in data diversity due to a lack of fine-grained control over the synthesis process. In this paper, we design a \emph{controllable} image-text synthesis pipeline, CtrlSynth, for data-efficient and robust multimodal learning. The key idea is to decompose the visual semantics of an image into basic elements, apply user-specified control policies (e.g., remove, add, or replace operations), and recompose them to synthesize images or texts. The decompose and recompose feature in CtrlSynth allows users to control data synthesis in a fine-grained manner by defining customized control policies to manipulate the basic elements. CtrlSynth leverages the capabilities of pretrained foundation models such as large language models or diffusion models to reason and recompose basic elements such that synthetic samples are natural and composed in diverse ways. CtrlSynth is a closed-loop, training-free, and modular framework, making it easy to support different pretrained models. With extensive experiments on 31 datasets spanning different vision and vision-language tasks, we show that CtrlSynth substantially improves zero-shot classification, image-text retrieval, and compositional reasoning performance of CLIP models.

[Arxiv](https://arxiv.org/abs/2410.11963)