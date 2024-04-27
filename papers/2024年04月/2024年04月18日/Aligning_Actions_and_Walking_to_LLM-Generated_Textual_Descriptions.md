# 将行动和行走与大型语言模型生成的文本描述相匹配。

发布时间：2024年04月18日

`LLM应用` `运动分析` `多模态学习`

> Aligning Actions and Walking to LLM-Generated Textual Descriptions

# 摘要

> 大型语言模型（LLMs）在多个领域展现了非凡的才能，尤其是在数据扩充和合成数据创造方面。本研究利用LLMs为运动序列生成详尽的文本描述，涉及动作和行走模式。我们借助LLMs的表达力，将运动信息与高级语言信号相结合，以应对两项特定任务：动作识别和基于外观特征的行走序列检索。在动作识别任务中，我们利用LLMs为BABEL-60数据集中的动作生成文本描述，以实现运动序列与语言描述的匹配。在步态分析方面，我们通过LLMs对DenseGait数据集中的行走序列进行文本描述，探究外观特征如衣着和鞋履对行走模式的影响。这些描述捕捉了行走风格中的微妙差异。我们的方法证明了LLMs在增强结构化运动特征和整合多模态表示方面的潜力。这些研究成果不仅推动了对运动理解的深入，也为未来在多模态同步和运动分析中应用LLMs提供了新的思路。相关代码已在 https://github.com/Radu1999/WalkAndText 上公开。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in various domains, including data augmentation and synthetic data generation. This work explores the use of LLMs to generate rich textual descriptions for motion sequences, encompassing both actions and walking patterns. We leverage the expressive power of LLMs to align motion representations with high-level linguistic cues, addressing two distinct tasks: action recognition and retrieval of walking sequences based on appearance attributes. For action recognition, we employ LLMs to generate textual descriptions of actions in the BABEL-60 dataset, facilitating the alignment of motion sequences with linguistic representations. In the domain of gait analysis, we investigate the impact of appearance attributes on walking patterns by generating textual descriptions of motion sequences from the DenseGait dataset using LLMs. These descriptions capture subtle variations in walking styles influenced by factors such as clothing choices and footwear. Our approach demonstrates the potential of LLMs in augmenting structured motion attributes and aligning multi-modal representations. The findings contribute to the advancement of comprehensive motion understanding and open up new avenues for leveraging LLMs in multi-modal alignment and data augmentation for motion analysis. We make the code publicly available at https://github.com/Radu1999/WalkAndText

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/gaitclip-diagram.drawio.png)

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/gaitclip-diagram2.drawio.png)

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/GaitCLIP-annotation.drawio.png)

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/features.png)

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/classif.png)

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/ndgc.png)

![将行动和行走与大型语言模型生成的文本描述相匹配。](../../../paper_images/2404.12192/per_feature.png)

[Arxiv](https://arxiv.org/abs/2404.12192)