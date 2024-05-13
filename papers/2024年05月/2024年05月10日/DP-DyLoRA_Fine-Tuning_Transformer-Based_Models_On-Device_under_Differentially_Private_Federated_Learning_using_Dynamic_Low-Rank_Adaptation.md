# DP-DyLoRA：在隐私保护联邦学习框架下，采用动态低秩适应技术，对基于变换器的模型进行设备端精细调整，以实现数据隐私与模型性能的平衡。

发布时间：2024年05月10日

`LLM应用

这篇论文探讨了在联邦学习框架下使用差分隐私技术来微调大型变压器模型的问题，特别是在保护隐私的同时保持模型性能的挑战。它涉及了多个应用领域，包括语音识别、计算机视觉和自然语言理解，并提出了一种新的方法DP-DyLoRA来减少性能损失。虽然它涉及了大型语言模型（LLM）的应用，但主要关注的是联邦学习和差分隐私技术，而不是LLM的理论或Agent的设计。因此，它更适合归类为LLM应用。` `联邦学习` `隐私保护`

> DP-DyLoRA: Fine-Tuning Transformer-Based Models On-Device under Differentially Private Federated Learning using Dynamic Low-Rank Adaptation

# 摘要

> 联邦学习让物联网设备在保护本地数据的同时，共同训练一个全局模型。但客户端的贡献仍可能泄露隐私。差分隐私通过添加随机性来保护隐私，但这也使得训练大型变压器模型变得困难。我们实证研究了在联邦学习中使用差分隐私微调大型变压器模型的可行性，并在语音识别、计算机视觉和自然语言理解等多个领域进行了实验。我们发现，完全微调在差分隐私联邦学习下会导致显著的性能下降，但通过参数高效微调可以缓解这一问题。我们的研究表明，DP-LoRA方法在DP-PEFT方法中表现最佳。我们还提出了DP-DyLoRA方法，它结合了差分隐私和动态低秩适应，有效减少了隐私保护下的性能损失，使得在拥有100万客户端和严格隐私预算ε=2的情况下，准确性下降和WER增加分别控制在2%和7%以内。

> Federated learning (FL) allows clients in an Internet of Things (IoT) system to collaboratively train a global model without sharing their local data with a server. However, clients' contributions to the server can still leak sensitive information. Differential privacy (DP) addresses such leakage by providing formal privacy guarantees, with mechanisms that add randomness to the clients' contributions. The randomness makes it infeasible to train large transformer-based models, common in modern IoT systems. In this work, we empirically evaluate the practicality of fine-tuning large scale on-device transformer-based models with differential privacy in a federated learning system. We conduct comprehensive experiments on various system properties for tasks spanning a multitude of domains: speech recognition, computer vision (CV) and natural language understanding (NLU). Our results show that full fine-tuning under differentially private federated learning (DP-FL) generally leads to huge performance degradation which can be alleviated by reducing the dimensionality of contributions through parameter-efficient fine-tuning (PEFT). Our benchmarks of existing DP-PEFT methods show that DP-Low-Rank Adaptation (DP-LoRA) consistently outperforms other methods. An even more promising approach, DyLoRA, which makes the low rank variable, when naively combined with FL would straightforwardly break differential privacy. We therefore propose an adaptation method that can be combined with differential privacy and call it DP-DyLoRA. Finally, we are able to reduce the accuracy degradation and word error rate (WER) increase due to DP to less than 2% and 7% respectively with 1 million clients and a stringent privacy budget of ε=2.

[Arxiv](https://arxiv.org/abs/2405.06368)