# 利用强化学习与合成偏好提升自动生成问题的难度

发布时间：2024年10月10日

`RAG` `文化遗产` `问答系统`

> Increasing the Difficulty of Automatically Generated Questions via Reinforcement Learning with Synthetic Preference

# 摘要

> 随着文化遗产领域越来越多地采用 RAG 等技术，提供个性化搜索体验并实现与收藏数据的对话，对专门评估数据集的需求日益增长。虽然端到端系统测试至关重要，但评估各个组件同样重要。我们专注于最终的回答任务，这非常适合 MRC。尽管现有 MRC 数据集涵盖了通用领域，但缺乏文化遗产信息所需的特定性。手动创建此类数据集成本过高。本文提出了一种利用 RLHF 生成难度增加的领域特定 MRC 数据集的成本效益方法。我们利用现有问答模型在 SQuAD 子集上的表现来创建难度指标，假设更难的问题正确回答的频率较低。本研究贡献包括：(1) 使用 PPO 和合成数据增加问题难度的方法；(2) 该方法有效性的实证证据，包括人类评估；(3) 深入的错误分析和新兴现象研究；以及 (4) 一个开源代码库和三个用于可重复性和适应性的 llama-2-chat 适配器。

> As the cultural heritage sector increasingly adopts technologies like Retrieval-Augmented Generation (RAG) to provide more personalised search experiences and enable conversations with collections data, the demand for specialised evaluation datasets has grown. While end-to-end system testing is essential, it's equally important to assess individual components. We target the final, answering task, which is well-suited to Machine Reading Comprehension (MRC). Although existing MRC datasets address general domains, they lack the specificity needed for cultural heritage information. Unfortunately, the manual creation of such datasets is prohibitively expensive for most heritage institutions. This paper presents a cost-effective approach for generating domain-specific MRC datasets with increased difficulty using Reinforcement Learning from Human Feedback (RLHF) from synthetic preference data. Our method leverages the performance of existing question-answering models on a subset of SQuAD to create a difficulty metric, assuming that more challenging questions are answered correctly less frequently. This research contributes: (1) A methodology for increasing question difficulty using PPO and synthetic data; (2) Empirical evidence of the method's effectiveness, including human evaluation; (3) An in-depth error analysis and study of emergent phenomena; and (4) An open-source codebase and set of three llama-2-chat adapters for reproducibility and adaptation.

[Arxiv](https://arxiv.org/abs/2410.08289)