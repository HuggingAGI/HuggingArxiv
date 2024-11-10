# 用于开放词汇运动生成的文本分解然后子运动空间散射

发布时间：2024年11月06日

`LLM应用` `计算机视觉` `动作生成`

> Textual Decomposition Then Sub-motion-space Scattering for Open-Vocabulary Motion Generation

# 摘要

> 文本到动作生成是计算机视觉中的一项关键任务，它通过给定的文本生成目标 3D 动作。现有的标注数据集规模有限，导致大多数现有方法对小数据集过度拟合，无法推广到开放域的动作。一些方法试图通过与 CLIP 空间对齐或使用预训练然后微调的范式来解决开放词汇动作生成问题。然而，当前标注数据集的有限规模仅允许它们实现从子文本空间到子动作空间的映射，而不是全文本空间和全动作空间之间的映射（全映射），这是实现开放词汇动作生成的关键。为此，本文提出利用原子动作（短时间内的简单身体部位动作）作为中间表示，并利用两个有序耦合的步骤，即文本分解和子动作空间散射，来解决全映射问题。对于文本分解，我们设计了一种细粒度的描述转换算法，并将其与大型语言模型的泛化能力相结合，将任何给定的动作文本转换为原子文本。子动作空间散射学习从原子动作到目标动作的组合过程，使学习到的子动作空间分散形成全动作空间。对于开放域的给定动作，它将外推转换为内插，从而显著提高泛化能力。我们的网络，$DSO$-Net，结合了文本分解和子动作空间散射来解决开放词汇动作生成问题。大量实验表明，我们的 DSO-Net 在开放词汇动作生成方面比最先进的方法有显著的改进。代码可在 https://vankouf.github.io/DSONet/ 获得。

> Text-to-motion generation is a crucial task in computer vision, which generates the target 3D motion by the given text. The existing annotated datasets are limited in scale, resulting in most existing methods overfitting to the small datasets and unable to generalize to the motions of the open domain. Some methods attempt to solve the open-vocabulary motion generation problem by aligning to the CLIP space or using the Pretrain-then-Finetuning paradigm. However, the current annotated dataset's limited scale only allows them to achieve mapping from sub-text-space to sub-motion-space, instead of mapping between full-text-space and full-motion-space (full mapping), which is the key to attaining open-vocabulary motion generation. To this end, this paper proposes to leverage the atomic motion (simple body part motions over a short time period) as an intermediate representation, and leverage two orderly coupled steps, i.e., Textual Decomposition and Sub-motion-space Scattering, to address the full mapping problem. For Textual Decomposition, we design a fine-grained description conversion algorithm, and combine it with the generalization ability of a large language model to convert any given motion text into atomic texts. Sub-motion-space Scattering learns the compositional process from atomic motions to the target motions, to make the learned sub-motion-space scattered to form the full-motion-space. For a given motion of the open domain, it transforms the extrapolation into interpolation and thereby significantly improves generalization. Our network, $DSO$-Net, combines textual $d$ecomposition and sub-motion-space $s$cattering to solve the $o$pen-vocabulary motion generation. Extensive experiments demonstrate that our DSO-Net achieves significant improvements over the state-of-the-art methods on open-vocabulary motion generation. Code is available at https://vankouf.github.io/DSONet/.

[Arxiv](https://arxiv.org/abs/2411.04079)