# MLLM-FL：利用多模态大型语言模型，在异构且长尾的数据上进行辅助联邦学习。

发布时间：2024年09月09日

`LLM应用` `人工智能` `联邦学习`

> MLLM-FL: Multimodal Large Language Model Assisted Federated Learning on Heterogeneous and Long-tailed Data

# 摘要

> 在联邦学习 (FL) 中，数据异质性常导致性能下降。为此，我们基于 GPT-4v 和 LLaVA 等先进的多模态大型语言模型 (MLLMs)，提出了多模态大型语言模型辅助联邦学习 (MLLM-FL) 框架。该框架利用 MLLMs 的跨模态能力和开放词汇知识，有效整合开源数据和服务器端计算资源，不仅提升性能，还避免了本地设备的隐私和计算负担。框架分三步：首先进行全局视觉-文本预训练，然后分发模型至各客户端进行本地训练，最后在服务器端进行全局对齐。实验表明，MLLM-FL 在处理数据异质性和长尾分布方面表现优异。

> Previous studies on federated learning (FL) often encounter performance degradation due to data heterogeneity among different clients. In light of the recent advances in multimodal large language models (MLLMs), such as GPT-4v and LLaVA, which demonstrate their exceptional proficiency in multimodal tasks, such as image captioning and multimodal question answering. We introduce a novel federated learning framework, named Multimodal Large Language Model Assisted Federated Learning (MLLM-FL), which which employs powerful MLLMs at the server end to address the heterogeneous and long-tailed challenges. Owing to the advanced cross-modality representation capabilities and the extensive open-vocabulary prior knowledge of MLLMs, our framework is adept at harnessing the extensive, yet previously underexploited, open-source data accessible from websites and powerful server-side computational resources. Hence, the MLLM-FL not only enhances the performance but also avoids increasing the risk of privacy leakage and the computational burden on local devices, distinguishing it from prior methodologies. Our framework has three key stages. Initially, prior to local training on local datasets of clients, we conduct global visual-text pretraining of the model. This pretraining is facilitated by utilizing the extensive open-source data available online, with the assistance of multimodal large language models. Subsequently, the pretrained model is distributed among various clients for local training. Finally, once the locally trained models are transmitted back to the server, a global alignment is carried out under the supervision of MLLMs to further enhance the performance. Experimental evaluations on established benchmarks, show that our framework delivers promising performance in the typical scenarios with data heterogeneity and long-tail distribution across different clients in FL.

[Arxiv](https://arxiv.org/abs/2409.06067)