# 借助大型语言模型，边缘学习在配电系统状态估计中展现出新的活力，为电力系统的智能化管理提供了强有力的技术支撑。

发布时间：2024年05月11日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在分布系统状态估计（DSSE）中的应用，特别是在处理配电网络中缺失数据的问题。通过提出一个基于边缘学习的预测后估计框架，该论文展示了LLMs如何结合自然语言提示和历史数据来预测缺失数据，并生成伪测量，从而提高状态估计的鲁棒性。这种方法特别适用于处理传感器故障或通信延迟导致的数据缺失问题。此外，论文还提出了一个多任务学习框架，并通过不确定性加权算法来优化任务间的平衡，以避免过拟合。因此，这篇论文的内容属于LLM在实际应用中的一个具体案例，即在配电网络监控和操作中的应用，因此被归类为LLM应用。` `配电网络` `状态估计

根据论文摘要内容` `该研究主要关注于配电网络的状态估计问题` `并提出了一种基于边缘学习的预测后估计框架。因此` `最相关的行业领域标签是“配电网络”和“状态估计”。`

> Large Language Model-aided Edge Learning in Distribution System State Estimation

# 摘要

> 分布系统状态估计（DSSE）对于配电网络的实时监控、控制和操作至关重要。然而，传统方法不仅计算需求高，还需要高质量的测量数据，而传感器故障或通信延迟常导致数据缺失。为此，我们提出了一种基于边缘学习的预测后估计框架，利用大型语言模型（LLMs）预测缺失数据并生成伪测量。首先，我们的LLM结合自然语言提示和测量序列，从历史数据中学习模式，提供精准预测。其次，我们引入了基于卷积层的神经网络，增强在数据缺失时的状态估计鲁棒性。为避免过拟合，我们将DSSE重构为多任务学习框架，包含共享层和特定任务层，并通过不确定性加权算法优化任务间的平衡。通过Simbench案例的数值模拟，我们验证了这一框架的有效性。

> Distribution system state estimation (DSSE) plays a crucial role in the real-time monitoring, control, and operation of distribution networks. Besides intensive computational requirements, conventional DSSE methods need high-quality measurements to obtain accurate states, whereas missing values often occur due to sensor failures or communication delays. To address these challenging issues, a forecast-then-estimate framework of edge learning is proposed for DSSE, leveraging large language models (LLMs) to forecast missing measurements and provide pseudo-measurements. Firstly, natural language-based prompts and measurement sequences are integrated by the proposed LLM to learn patterns from historical data and provide accurate forecasting results. Secondly, a convolutional layer-based neural network model is introduced to improve the robustness of state estimation under missing measurement. Thirdly, to alleviate the overfitting of the deep learning-based DSSE, it is reformulated as a multi-task learning framework containing shared and task-specific layers. The uncertainty weighting algorithm is applied to find the optimal weights to balance different tasks. The numerical simulation on the Simbench case is used to demonstrate the effectiveness of the proposed forecast-then-estimate framework.

[Arxiv](https://arxiv.org/abs/2405.06999)