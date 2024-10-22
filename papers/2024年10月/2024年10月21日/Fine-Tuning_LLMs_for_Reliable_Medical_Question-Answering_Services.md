# 优化大型语言模型，打造可靠的医疗问答服务

发布时间：2024年10月21日

`LLM应用` `人工智能`

> Fine-Tuning LLMs for Reliable Medical Question-Answering Services

# 摘要

> 我们提出了一种先进的医疗问答服务方法，利用微调的大型语言模型 (LLM) 提升医疗信息的准确性和可靠性。研究重点优化了 LLaMA-2 和 Mistral 等模型，这些模型在提供精确、可靠的医疗答案方面表现出色。通过综合数据集和微调技术，如 rsDoRA+ 和 ReRAG，我们显著提升了模型性能。rsDoRA+ 通过分解模型权重、优化低秩矩阵学习率和秩稳定性，提高了效率；ReRAG 则通过按需检索和问题重写，进一步提升了答案的准确性。这种方法使医疗提供者能够快速获取可靠信息，助力高效决策并增强患者信任。我们的研究展示了微调 LLM 在提升医疗信息服务质量和可访问性方面的巨大潜力，最终为所有人带来更优质的医疗结果。

> We present an advanced approach to medical question-answering (QA) services, using fine-tuned Large Language Models (LLMs) to improve the accuracy and reliability of healthcare information. Our study focuses on optimizing models like LLaMA-2 and Mistral, which have shown great promise in delivering precise, reliable medical answers. By leveraging comprehensive datasets, we applied fine-tuning techniques such as rsDoRA+ and ReRAG. rsDoRA+ enhances model performance through a combination of decomposed model weights, varied learning rates for low-rank matrices, and rank stabilization, leading to improved efficiency. ReRAG, which integrates retrieval on demand and question rewriting, further refines the accuracy of the responses. This approach enables healthcare providers to access fast, dependable information, aiding in more efficient decision-making and fostering greater patient trust. Our work highlights the potential of fine-tuned LLMs to significantly improve the quality and accessibility of medical information services, ultimately contributing to better healthcare outcomes for all.

[Arxiv](https://arxiv.org/abs/2410.16088)