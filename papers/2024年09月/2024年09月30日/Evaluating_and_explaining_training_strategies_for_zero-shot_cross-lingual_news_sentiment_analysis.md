# 探索与解读零-shot 跨语言新闻情感分析的训练策略

发布时间：2024年09月30日

`LLM应用` `情感分析`

> Evaluating and explaining training strategies for zero-shot cross-lingual news sentiment analysis

# 摘要

> 我们探索了零-shot 跨语言新闻情感检测，目标是打造无需目标语言训练数据的强大情感分类器。我们创建了多个人口较少语言的评估数据集，并尝试了多种方法，包括机器翻译、大型语言模型的 in-context learning，以及利用段落级信息的新颖任务目标 POA。实验结果显示，in-context learning 通常表现最佳，而 POA 方法则以低计算成本提供了有力竞争。此外，我们发现，仅凭语言相似性不足以预测跨语言迁移的成功，语义内容和结构的相似性同样关键。

> We investigate zero-shot cross-lingual news sentiment detection, aiming to develop robust sentiment classifiers that can be deployed across multiple languages without target-language training data. We introduce novel evaluation datasets in several less-resourced languages, and experiment with a range of approaches including the use of machine translation; in-context learning with large language models; and various intermediate training regimes including a novel task objective, POA, that leverages paragraph-level information. Our results demonstrate significant improvements over the state of the art, with in-context learning generally giving the best performance, but with the novel POA approach giving a competitive alternative with much lower computational overhead. We also show that language similarity is not in itself sufficient for predicting the success of cross-lingual transfer, but that similarity in semantic content and structure can be equally important.

[Arxiv](https://arxiv.org/abs/2409.20054)