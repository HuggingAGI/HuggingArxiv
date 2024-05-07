# WorldQA：通过长链推理，探索视频内容中的多模态世界知识

发布时间：2024年05月06日

`Agent` `视频理解` `人工智能`

> WorldQA: Multimodal World Knowledge in Videos through Long-Chain Reasoning

# 摘要

> 多模态信息与我们的知识相结合，助我们洞悉这个复杂多变的世界。但大型语言模型（LLM）和大型多模态模型（LMM）在模拟这一能力上仍有挑战。本文提出了WorldQA，这是一个旨在拓展多模态世界模型极限的视频理解数据集，具备三大特点：（1）多模态输入：包含1007个问答对和303个视频，要求分析视听数据以实现准确理解。（2）世界知识：我们辨识出五种关键的世界知识类型，用于构建问题。这要求模型不仅要感知，还要深入理解。（3）长链推理：数据集平均推理步骤达到4.45，超越了其他视频问答数据集。我们还推出了WorldRetriever，这是一个将专家知识整合成连贯推理链的代理，以提高对WorldQA查询的准确回答。对13种主流LLM和LMM的广泛评估显示，尽管WorldRetriever是最有效的模型，但在多项选择题中仅达到了70%的人类水平。这一发现强调了模型在推理和理解能力上需要进一步进步。实验还揭示了关键见解，例如，人类在增加帧数时表现更佳，而当前的LMM，包括WorldRetriever，在类似条件下性能下降。我们期望WorldQA、我们的方法和这些见解能为多模态世界模型的未来发展提供助力。

> Multimodal information, together with our knowledge, help us to understand the complex and dynamic world. Large language models (LLM) and large multimodal models (LMM), however, still struggle to emulate this capability. In this paper, we present WorldQA, a video understanding dataset designed to push the boundaries of multimodal world models with three appealing properties: (1) Multimodal Inputs: The dataset comprises 1007 question-answer pairs and 303 videos, necessitating the analysis of both auditory and visual data for successful interpretation. (2) World Knowledge: We identify five essential types of world knowledge for question formulation. This approach challenges models to extend their capabilities beyond mere perception. (3) Long-Chain Reasoning: Our dataset introduces an average reasoning step of 4.45, notably surpassing other videoQA datasets. Furthermore, we introduce WorldRetriever, an agent designed to synthesize expert knowledge into a coherent reasoning chain, thereby facilitating accurate responses to WorldQA queries. Extensive evaluations of 13 prominent LLMs and LMMs reveal that WorldRetriever, although being the most effective model, achieved only 70% of humanlevel performance in multiple-choice questions. This finding highlights the necessity for further advancement in the reasoning and comprehension abilities of models. Our experiments also yield several key insights. For instance, while humans tend to perform better with increased frames, current LMMs, including WorldRetriever, show diminished performance under similar conditions. We hope that WorldQA,our methodology, and these insights could contribute to the future development of multimodal world models.

[Arxiv](https://arxiv.org/abs/2405.03272)