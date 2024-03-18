# [针对大型多模态模型中出现的排版攻击问题，研究表明提供更多信息量的提示能够有效缓解这一现象。](https://arxiv.org/abs/2402.19150)

发布时间：2024年02月29日

`LLM应用`

> Typographic Attacks in Large Multimodal Models Can be Alleviated by More Informative Prompts

> LMMs 结合预训练的 VLMs 和 LLMs，在视觉与语言的交叉领域中展现出卓越的多模态任务处理能力，但 Typographic Attack——这种对 VLMs 具有破坏性的手段也被确认为 LMMs 的安全隐患。本研究首先系统地探究了 LMMs 在面对排版变化时的注意力分散问题，特别构建了一个跨多种多模态子任务（如物体识别、视觉属性检测、计数、计算及常识推理等）的排版扰动数据集进行评测。为进一步分析排版样式如何影响模型表现，我们详细研究了改变字体大小、颜色、透明度以及错字位置等多个排版参数的影响。结果显示，尽管受到排版攻击，LMMs 竟然能在一定程度上区分图像中的视觉内容与错字，这意味着视觉编码器产生的嵌入确实蕴含着分辨二者差异的信息。基于这一发现，我们揭示了通过向 CLIP 提供更丰富文本描述，可有效提升其在充斥错字图像上的零样本分类准确率。同时，我们还验证了 LMMs 如何借助更有价值的提示信息，挖掘嵌入中的信息以区分视觉内容与错字。最终，我们创新性地提出了一个提示信息强化方法，能有效缓解排版样式带来的负面影响。

> Large Multimodal Models (LMMs) rely on pre-trained Vision Language Models (VLMs) and Large Language Models (LLMs) to perform amazing emergent abilities on various multimodal tasks in the joint space of vision and language. However, the Typographic Attack, which shows disruption to VLMs, has also been certified as a security vulnerability to LMMs. In this work, we first comprehensively investigate the distractibility of LMMs by typography. In particular, we introduce the Typographic Dataset designed to evaluate distractibility across various multi-modal subtasks, such as object recognition, visual attributes detection, enumeration, arithmetic computation, and commonsense reasoning. To further study the effect of typographic patterns on performance, we also scrutinize the effect of tuning various typographic factors, encompassing font size, color, opacity, and spatial positioning of typos. We discover that LMMs can partially distinguish visual contents and typos when confronting typographic attacks, which suggests that embeddings from vision encoders contain enough information to distinguish visual contents and typos in images. Inspired by such phenomena, we demonstrate that CLIP's performance of zero-shot classification on typo-ridden images can be significantly improved by providing more informative texts to match images. Furthermore, we also prove that LMMs can utilize more informative prompts to leverage information in embeddings to differentiate between visual content and typos. Finally, we propose a prompt information enhancement method that can effectively mitigate the effects of typography.

[Arxiv](https://arxiv.org/abs/2402.19150)