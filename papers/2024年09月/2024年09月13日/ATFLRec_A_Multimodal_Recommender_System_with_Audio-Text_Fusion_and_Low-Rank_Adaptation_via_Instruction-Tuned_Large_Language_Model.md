# ATFLRec：一款多模态推荐系统，融合音频与文本，并通过指令调优的大型语言模型实现低秩适应。

发布时间：2024年09月13日

`LLM应用` `电子商务`

> ATFLRec: A Multimodal Recommender System with Audio-Text Fusion and Low-Rank Adaptation via Instruction-Tuned Large Language Model

# 摘要

> 推荐系统 (RS) 通过提供个性化产品建议，在提升用户满意度方面至关重要，尤其在电子商务和娱乐领域。本研究聚焦于将多模态数据（文本和音频）整合到大型语言模型 (LLM) 中，以提升推荐性能。传统推荐系统面临冷启动问题，而 LLM 虽有潜力，但计算成本高。为此，我们引入了低秩适应 (LoRA)，在不降低性能的前提下提高效率。我们提出的 ATFLRec 框架，通过整合音频和文本模态，结合多种 LoRA 配置和模态融合技术，显著提升了推荐效果。实验结果显示，ATFLRec 超越了传统和基于图神经网络的基线模型，AUC 分数更高。此外，分别微调音频和文本数据，并采用不同的池化方法和 Mel 滤波器组，进一步优化了性能。这项研究为多模态推荐系统的优化及 LLM 中多样化数据模态的整合提供了重要启示。

> Recommender Systems (RS) play a pivotal role in boosting user satisfaction by providing personalized product suggestions in domains such as e-commerce and entertainment. This study examines the integration of multimodal data text and audio into large language models (LLMs) with the aim of enhancing recommendation performance. Traditional text and audio recommenders encounter limitations such as the cold-start problem, and recent advancements in LLMs, while promising, are computationally expensive. To address these issues, Low-Rank Adaptation (LoRA) is introduced, which enhances efficiency without compromising performance. The ATFLRec framework is proposed to integrate audio and text modalities into a multimodal recommendation system, utilizing various LoRA configurations and modality fusion techniques. Results indicate that ATFLRec outperforms baseline models, including traditional and graph neural network-based approaches, achieving higher AUC scores. Furthermore, separate fine-tuning of audio and text data with distinct LoRA modules yields optimal performance, with different pooling methods and Mel filter bank numbers significantly impacting performance. This research offers valuable insights into optimizing multimodal recommender systems and advancing the integration of diverse data modalities in LLMs.

[Arxiv](https://arxiv.org/abs/2409.08543)