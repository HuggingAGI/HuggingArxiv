# MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读

发布时间：2024年06月16日

`LLM理论

理由：这篇论文探讨了多模态大型语言模型（MLLMs）的内部运作机制，特别是关于视觉特征如何融入词嵌入空间的问题。论文通过研究领域特定神经元的分布和MLLMs处理多领域特征的方式，提出了一套三阶段框架，并通过实验验证了这一理论。这些内容涉及对MLLMs理论层面的理解和改进，因此属于LLM理论分类。` `多模态学习` `视觉问答`

> MMNeuron: Discovering Neuron-Level Domain-Specific Interpretation in Multimodal Large Language Model

# 摘要

> 将视觉特征融入词嵌入空间是多模态大型语言模型（MLLMs）的关键融合策略，但其内部运作机制仍是个谜。借鉴多语言研究，我们揭示了MLLMs中的领域特定神经元，并探究了它们的分布及MLLMs处理多领域特征的方式。我们进一步提出了一套三阶段框架，指导MLLMs在处理映射图像特征时的语言模型模块，并通过logit透镜验证了这一理论。实验结果显示，尽管MLLMs在视觉问答（VQA）上表现出色，但对领域特定信息的利用仍有提升空间。通过精准调控领域特定神经元，我们发现最多可提升10%的准确度，为未来打造跨领域、全能型的MLLMs指明了方向。我们的代码将在论文发表后公开。

> Projecting visual features into word embedding space has become a significant fusion strategy adopted by Multimodal Large Language Models (MLLMs). However, its internal mechanisms have yet to be explored. Inspired by multilingual research, we identify domain-specific neurons in multimodal large language models. Specifically, we investigate the distribution of domain-specific neurons and the mechanism of how MLLMs process features from diverse domains. Furthermore, we propose a three-stage framework for language model modules in MLLMs when handling projected image features, and verify this hypothesis using logit lens. Extensive experiments indicate that while current MLLMs exhibit Visual Question Answering (VQA) capability, they may not fully utilize domain-specific information. Manipulating domain-specific neurons properly will result in a 10\% change of accuracy at most, shedding light on the development of cross-domain, all-encompassing MLLMs in the future. Our code will be released upon paper notification.

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/framework.jpg)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x1.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/illustration.jpg)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/logit_frame.jpg)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x2.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x3.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x4.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x5.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x6.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x7.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x8.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x9.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x10.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x11.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x12.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x13.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x14.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x15.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x16.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x17.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x18.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x19.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x20.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x21.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/ad_sample.jpg)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x22.png)

![MMNeuron：揭示多模态大型语言模型中神经元级别的领域特异性解读](../../../paper_images/2406.11193/x23.png)

[Arxiv](https://arxiv.org/abs/2406.11193)