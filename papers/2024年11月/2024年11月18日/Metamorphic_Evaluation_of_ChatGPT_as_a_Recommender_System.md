# 对 ChatGPT 作为推荐系统的变态评估

发布时间：2024年11月18日

`LLM应用` `推荐系统` `大型语言模型`

> Metamorphic Evaluation of ChatGPT as a Recommender System

# 摘要

> 随着 ChatGPT 等大型语言模型（LLMs）的兴起，研究人员一直在探索如何利用 LLMs 实现更优的推荐。然而，尽管 LLMs 具有黑箱和概率特性（即内部运作不可见），但评估这些基于 LLM 的推荐系统（RS）所采用的评估框架却与传统推荐系统相同。为弥补这一差距，我们引入了针对基于 GPT 的 RS 的变形测试。该测试技术包括定义输入之间的变形关系（MRs），并检验输出是否满足此关系。具体而言，我们从 RS 和 LLMs 两个角度审视了 MRs，涵盖了 RS 中的评级乘法/移位，以及通过提示扰动在 LLMs 提示中添加空格/随机性。通过使用相似性度量指标（如肯德尔 tau 和排名偏差重叠（RBO））来衡量 MRs 的输出是否满足该关系。在带有 GPT3.5 的 MovieLens 数据集上的实验结果显示，就肯德尔 $τ$ 和 RBO 而言，所得相似性较低，这表明除了传统推荐系统现有的评估指标外，还需对基于 LLM 的 RS 进行全面评估。

> With the rise of Large Language Models (LLMs) such as ChatGPT, researchers have been working on how to utilize the LLMs for better recommendations. However, although LLMs exhibit black-box and probabilistic characteristics (meaning their internal working is not visible), the evaluation framework used for assessing these LLM-based recommender systems (RS) are the same as those used for traditional recommender systems. To address this gap, we introduce the metamorphic testing for the evaluation of GPT-based RS. This testing technique involves defining of metamorphic relations (MRs) between the inputs and checking if the relationship has been satisfied in the outputs. Specifically, we examined the MRs from both RS and LLMs perspectives, including rating multiplication/shifting in RS and adding spaces/randomness in the LLMs prompt via prompt perturbation. Similarity metrics (e.g. Kendall tau and Ranking Biased Overlap(RBO)) are deployed to measure whether the relationship has been satisfied in the outputs of MRs. The experiment results on MovieLens dataset with GPT3.5 show that lower similarity are obtained in terms of Kendall $τ$ and RBO, which concludes that there is a need of a comprehensive evaluation of the LLM-based RS in addition to the existing evaluation metrics used for traditional recommender systems.

[Arxiv](https://arxiv.org/abs/2411.12121)