# 借助视觉模态，巧妙解锁大型语言模型的潜能

发布时间：2024年05月30日

`Agent

理由：这篇论文主要探讨了如何构建一个多模态大型语言模型（MLLM）来实施针对大型语言模型（LLMs）的越狱攻击。这种攻击涉及到创建一个特定的Agent（即MLLM），该Agent能够理解和响应有害的用户查询，并产生不当内容。因此，这个研究更侧重于Agent的设计和应用，而不是理论探讨或特定的LLM应用场景。此外，论文中提到的“越狱攻击”和“图像-文本语义匹配策略”都是为了增强Agent的能力和效率，这进一步支持了将其归类为Agent。` `网络安全` `人工智能安全`

> Efficient LLM-Jailbreaking by Introducing Visual Modality

# 摘要

> 本文探讨了如何通过构建多模态大型语言模型（MLLM）来实施针对大型语言模型（LLMs）的越狱攻击，使其在有害用户查询下产生不当内容。我们的方法首先整合视觉模块至目标LLM，形成MLLM，然后高效地进行MLLM越狱，生成越狱嵌入embJS，并将其转换至文本空间，以实现目标LLM的越狱。相较于直接越狱LLM，我们的方法因MLLM的脆弱性而更高效。为提升越狱成功率，我们设计了图像-文本语义匹配策略，精准选择初始输入。实验证明，我们的方法在效率与效果上均超越现有技术，并展现出强大的跨类别越狱能力。

> This paper focuses on jailbreaking attacks against large language models (LLMs), eliciting them to generate objectionable content in response to harmful user queries. Unlike previous LLM-jailbreaks that directly orient to LLMs, our approach begins by constructing a multimodal large language model (MLLM) through the incorporation of a visual module into the target LLM. Subsequently, we conduct an efficient MLLM-jailbreak to generate jailbreaking embeddings embJS. Finally, we convert the embJS into text space to facilitate the jailbreaking of the target LLM. Compared to direct LLM-jailbreaking, our approach is more efficient, as MLLMs are more vulnerable to jailbreaking than pure LLM. Additionally, to improve the attack success rate (ASR) of jailbreaking, we propose an image-text semantic matching scheme to identify a suitable initial input. Extensive experiments demonstrate that our approach surpasses current state-of-the-art methods in terms of both efficiency and effectiveness. Moreover, our approach exhibits superior cross-class jailbreaking capabilities.

![借助视觉模态，巧妙解锁大型语言模型的潜能](../../../paper_images/2405.20015/fig1.png)

![借助视觉模态，巧妙解锁大型语言模型的潜能](../../../paper_images/2405.20015/overview2.png)

![借助视觉模态，巧妙解锁大型语言模型的潜能](../../../paper_images/2405.20015/heatn.png)

[Arxiv](https://arxiv.org/abs/2405.20015)