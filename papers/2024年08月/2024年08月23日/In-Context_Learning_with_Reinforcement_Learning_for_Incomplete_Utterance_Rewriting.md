# 结合强化学习的上下文学习技术，应用于不完整话语的重写任务。

发布时间：2024年08月23日

`LLM应用` `人工智能`

> In-Context Learning with Reinforcement Learning for Incomplete Utterance Rewriting

# 摘要

> 大型语言模型的上下文学习正受到越来越多关注，这些模型通过结合少量示例的指令进行预测。尽管现有方法通过稀疏或密集检索器取得了一定成效，但它们未能利用模型的直接反馈来优化检索过程，且所选示例未必能提升模型的类比能力。为此，我们设计了一个基于策略的强化学习框架，用于优化示例选择，该框架包含一个语言模型选择器和一个大型语言模型生成器。选择器将候选示例转化为密集表示，并精选出最优的 k 个示例供模型学习。通过模型输出计算奖励和梯度，进一步优化选择器。实验结果显示，我们的方法在多个数据集上超越了现有技术，并在少样本场景下优于传统的监督微调模型。深入分析表明，示例的多样性与测试案例的相似性对提升模型的上下文学习能力至关重要。

> In-context learning (ICL) of large language models (LLMs) has attracted increasing attention in the community where LLMs make predictions only based on instructions augmented with a few examples. Existing example selection methods for ICL utilize sparse or dense retrievers and derive effective performance. However, these methods do not utilize direct feedback of LLM to train the retriever and the examples selected can not necessarily improve the analogy ability of LLM. To tackle this, we propose our policy-based reinforcement learning framework for example selection (RLS), which consists of a language model (LM) selector and an LLM generator. The LM selector encodes the candidate examples into dense representations and selects the top-k examples into the demonstration for LLM. The outputs of LLM are adopted to compute the reward and policy gradient to optimize the LM selector. We conduct experiments on different datasets and significantly outperform existing example selection methods. Moreover, our approach shows advantages over supervised finetuning (SFT) models in few shot setting. Further experiments show the balance of abundance and the similarity with the test case of examples is important for ICL performance of LLM.

[Arxiv](https://arxiv.org/abs/2408.13028)