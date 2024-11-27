# 借助数据变换实现对大型语言模型中遗忘的稳健评估

发布时间：2024年11月23日

`LLM应用` `信息安全`

> Towards Robust Evaluation of Unlearning in LLMs via Data Transformations

# 摘要

> 大型语言模型（LLMs）在众多应用领域，从常规的基于自然语言处理的用例到人工智能代理，都大获成功。LLMs 基于来自各种来源的海量文本语料库进行训练；尽管在训练时的数据预处理阶段已竭尽全力，但仍可能获取一些不良信息，比如个人身份识别信息（PII）。正因如此，近来机器遗忘（MUL）领域的研究活跃起来，其核心思想是促使 LLMs 忘却（遗忘）某些信息（如 PII），且在常规任务中不出现性能损失。在本研究中，我们考察了现有 MUL 技术使 LLMs 实现防泄漏遗忘的能力。特别是，我们探究了数据转换对遗忘的影响，即输入格式改变时，未学习的 LLMs 能否回想起遗忘的信息？我们在 TOFU 数据集上的发现凸显了使用多种数据格式更可靠地量化 LLMs 中的遗忘的必要性。

> Large Language Models (LLMs) have shown to be a great success in a wide range of applications ranging from regular NLP-based use cases to AI agents. LLMs have been trained on a vast corpus of texts from various sources; despite the best efforts during the data pre-processing stage while training the LLMs, they may pick some undesirable information such as personally identifiable information (PII). Consequently, in recent times research in the area of Machine Unlearning (MUL) has become active, the main idea is to force LLMs to forget (unlearn) certain information (e.g., PII) without suffering from performance loss on regular tasks. In this work, we examine the robustness of the existing MUL techniques for their ability to enable leakage-proof forgetting in LLMs. In particular, we examine the effect of data transformation on forgetting, i.e., is an unlearned LLM able to recall forgotten information if there is a change in the format of the input? Our findings on the TOFU dataset highlight the necessity of using diverse data formats to quantify unlearning in LLMs more reliably.

[Arxiv](https://arxiv.org/abs/2411.15477)