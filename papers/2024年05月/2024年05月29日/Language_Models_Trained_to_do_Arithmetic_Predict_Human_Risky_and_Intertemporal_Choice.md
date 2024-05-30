# 语言模型通过算术训练，能够预测人类的风险决策和时间偏好选择。

发布时间：2024年05月29日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）作为人类认知模型的可能性，并提出了一种创新策略来提升LLMs在这方面的效用。它涉及对LLMs在特定认知任务中的表现进行深入分析，并探讨了LLMs与人类行为相似性的根源。这些内容更多地关注于LLMs的理论和内部机制，以及它们如何模拟人类认知过程，因此属于LLM理论分类。` `认知科学` `决策分析`

> Language Models Trained to do Arithmetic Predict Human Risky and Intertemporal Choice

# 摘要

> 人类与大型语言模型（LLMs）行为上的相似性激发了研究者探索LLMs作为人类认知模型的可能性。但要真正将LLMs视为认知模型，还需克服若干关键挑战。例如，LLMs训练所用的数据量远超人类日常接触的范围，且可能在特定认知任务中直接采用人类数据或与人类偏好相匹配。因此，这些行为相似性的根源尚不明晰。本文提出了一种创新策略，旨在提升LLMs作为认知模型的效用。该策略涉及两个方面：一是利用LLM和理性代理在解决认知问题时所需掌握的计算等价任务；二是探究使LLM表现出人类行为特征所需的特定任务分布。我们特别将此策略应用于风险决策和跨期选择，其中核心的计算等价任务是期望值计算的算术。我们发现，经过生态有效算术数据集预训练的LLM，即我们命名的Arithmetic-GPT，在预测人类行为方面优于众多传统认知模型。此外，预训练于生态有效算术数据集的LLMs足以在模型与人类决策之间建立紧密联系。研究结果还提示，作为认知模型使用的LLMs应通过对其预训练数据的深入消融研究进行细致考察。

> The observed similarities in the behavior of humans and Large Language Models (LLMs) have prompted researchers to consider the potential of using LLMs as models of human cognition. However, several significant challenges must be addressed before LLMs can be legitimately regarded as cognitive models. For instance, LLMs are trained on far more data than humans typically encounter, and may have been directly trained on human data in specific cognitive tasks or aligned with human preferences. Consequently, the origins of these behavioral similarities are not well understood. In this paper, we propose a novel way to enhance the utility of LLMs as cognitive models. This approach involves (i) leveraging computationally equivalent tasks that both an LLM and a rational agent need to master for solving a cognitive problem and (ii) examining the specific task distributions required for an LLM to exhibit human-like behaviors. We apply this approach to decision-making -- specifically risky and intertemporal choice -- where the key computationally equivalent task is the arithmetic of expected value calculations. We show that an LLM pretrained on an ecologically valid arithmetic dataset, which we call Arithmetic-GPT, predicts human behavior better than many traditional cognitive models. Pretraining LLMs on ecologically valid arithmetic datasets is sufficient to produce a strong correspondence between these models and human decision-making. Our results also suggest that LLMs used as cognitive models should be carefully investigated via ablation studies of the pretraining data.

![语言模型通过算术训练，能够预测人类的风险决策和时间偏好选择。](../../../paper_images/2405.19313/x1.png)

![语言模型通过算术训练，能够预测人类的风险决策和时间偏好选择。](../../../paper_images/2405.19313/x2.png)

[Arxiv](https://arxiv.org/abs/2405.19313)