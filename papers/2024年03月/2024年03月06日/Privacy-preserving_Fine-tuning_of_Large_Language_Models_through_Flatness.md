# 针对大型语言模型，我们提出了一种基于“平坦性”的隐私保护微调方法。该方法旨在在保持模型性能的同时，有效保障用户数据隐私，特别是在对大型语言模型进行针对性优化时。

发布时间：2024年03月06日

`LLM理论`

> Privacy-preserving Fine-tuning of Large Language Models through Flatness

> 随着ChatGPT等LLMs的崛起，隐私问题愈发引人关注。当前研究尝试通过DP技术来缓解LLMs的隐私风险，但可能影响模型的泛化能力。本文发现，DP训练模型损失曲面的平坦程度对平衡隐私保护与泛化性能至关重要。为此，我们设计了一个全方位框架，有效地调整模型权重的适当平坦度，不仅确保强有力的隐私保护，还显著提升了模型泛化力。这一创新框架涵盖了三个层次的技术手段，如基于扰动感知的层内模型权重MinMax优化、依据平坦度引导的跨层稀疏前缀调优，以及在DP与非DP权重版本间进行的知识蒸馏。我们针对黑盒和白盒场景开展了全面实验，证实了本方案能够有效提升模型泛化性能并维持DP特性。例如，在QNLI文本分类数据集上，当隐私预算为$ε=3$时，DP-Flat方法能够在满足DP保证的前提下，实现与无隐私全量微调相当的性能表现，而在更大隐私预算下，性能还能得到进一步提升。附带的补充资料中包含了相关代码。

> The privacy concerns associated with the use of Large Language Models (LLMs) have grown recently with the development of LLMs such as ChatGPT. Differential Privacy (DP) techniques are explored in existing work to mitigate their privacy risks at the cost of generalization degradation. Our paper reveals that the flatness of DP-trained models' loss landscape plays an essential role in the trade-off between their privacy and generalization. We further propose a holistic framework to enforce appropriate weight flatness, which substantially improves model generalization with competitive privacy preservation. It innovates from three coarse-to-grained levels, including perturbation-aware min-max optimization on model weights within a layer, flatness-guided sparse prefix-tuning on weights across layers, and weight knowledge distillation between DP \& non-DP weights copies. Comprehensive experiments of both black-box and white-box scenarios are conducted to demonstrate the effectiveness of our proposal in enhancing generalization and maintaining DP characteristics. For instance, on text classification dataset QNLI, DP-Flat achieves similar performance with non-private full fine-tuning but with DP guarantee under privacy budget $ε=3$, and even better performance given higher privacy budgets. Codes are provided in the supplement.

[Arxiv](https://arxiv.org/abs/2403.04124)