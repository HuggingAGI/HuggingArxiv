# F$^3$OCUS -- 借助多目标元启发式算法，以最优客户端层更新策略对视觉语言基础模型实施联邦微调

发布时间：2024年11月17日

`LLM应用` `联邦学习`

> F$^3$OCUS -- Federated Finetuning of Vision-Language Foundation Models with Optimal Client Layer Updating Strategy via Multi-objective Meta-Heuristics

# 摘要

> 在联邦学习（FL）中，要在资源受限的客户端设备上对大型视觉语言模型（VLMs）进行有效训练，就得运用参数高效微调（PEFT）策略。为此，我们揭示了两个因素的作用，一是用于挑选微调最重要的 VLM 层的客户端特定层重要性得分，二是鼓励客户端间进行不同层选择的客户端间层多样性得分，以达成最佳的 VLM 层选择。我们先是从理论上激发并利用层状神经切线核的主特征值大小，证明其作为客户端特定层重要性得分的有效性。接着，我们提出了一种叫 F$^3$OCUS 的新层更新策略，通过在服务器上采用无数据、多目标、元启发式优化，共同优化层重要性和多样性因素。我们探究了 5 种不同的元启发式算法，并对比了它们在选择模型层和适配器层以实现 PEFT-FL 方面的成效。另外，我们发布了一个新的 MedVQA-FL 数据集，其中涵盖总计 707,962 个 VQA 三元组和 9 个特定模态的客户端，并借此来训练和评估我们的方法。总之，我们在 6 个涉及 58 个医学图像数据集和 4 种不同规模的 VLM 架构的视觉语言 FL 任务设置上开展了超 10,000 次客户端级别的实验，以彰显所提方法的有效性。

> Effective training of large Vision-Language Models (VLMs) on resource-constrained client devices in Federated Learning (FL) requires the usage of parameter-efficient fine-tuning (PEFT) strategies. To this end, we demonstrate the impact of two factors \textit{viz.}, client-specific layer importance score that selects the most important VLM layers for fine-tuning and inter-client layer diversity score that encourages diverse layer selection across clients for optimal VLM layer selection. We first theoretically motivate and leverage the principal eigenvalue magnitude of layerwise Neural Tangent Kernels and show its effectiveness as client-specific layer importance score. Next, we propose a novel layer updating strategy dubbed F$^3$OCUS that jointly optimizes the layer importance and diversity factors by employing a data-free, multi-objective, meta-heuristic optimization on the server. We explore 5 different meta-heuristic algorithms and compare their effectiveness for selecting model layers and adapter layers towards PEFT-FL. Furthermore, we release a new MedVQA-FL dataset involving overall 707,962 VQA triplets and 9 modality-specific clients and utilize it to train and evaluate our method. Overall, we conduct more than 10,000 client-level experiments on 6 Vision-Language FL task settings involving 58 medical image datasets and 4 different VLM architectures of varying sizes to demonstrate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2411.11912)