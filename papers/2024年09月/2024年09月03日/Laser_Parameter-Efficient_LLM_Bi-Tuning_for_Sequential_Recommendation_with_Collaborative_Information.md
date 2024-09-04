# 激光技术：通过协同信息，实现序列推荐的参数高效大型语言模型双调优

发布时间：2024年09月03日

`LLM应用` `电子商务` `个性化推荐`

> Laser: Parameter-Efficient LLM Bi-Tuning for Sequential Recommendation with Collaborative Information

# 摘要

> 顺序推荐系统对于精准把握用户历史行为并提供个性化推荐至关重要。尽管大型语言模型 (LLM) 的应用在此领域取得了进展，但它们往往需要繁琐的参数调整且资源消耗大，且忽视了用户类型的多样性，影响了推荐质量。为此，我们提出了一个高效的 LLM 双调框架 (Laser)，通过在输入序列前后插入可训练的虚拟令牌并冻结 LLM 参数，实现对 LLM 的优化以适应顺序推荐。Laser 利用前缀整合用户-项目协同信息，使 LLM 更贴合推荐任务，同时通过后缀将输出嵌入转换至推荐空间，提升后续推荐效果。为更好地捕捉用户多样性，我们设计了 M-Former，一种轻量级 MoE 查询变换器，它能有效整合多样化用户协同信息，大幅提升推荐准确性。实验结果显示，Laser 在参数高效性方面表现卓越，显著优于现有顶尖方法。

> Sequential recommender systems are essential for discerning user preferences from historical interactions and facilitating targeted recommendations. Recent innovations employing Large Language Models (LLMs) have advanced the field by encoding item semantics, yet they often necessitate substantial parameter tuning and are resource-demanding. Moreover, these works fails to consider the diverse characteristics of different types of users and thus diminishes the recommendation accuracy. In this paper, we propose a parameter-efficient Large Language Model Bi-Tuning framework for sequential recommendation with collaborative information (Laser). Specifically, Bi-Tuning works by inserting trainable virtual tokens at both the prefix and suffix of the input sequence and freezing the LLM parameters, thus optimizing the LLM for the sequential recommendation. In our Laser, the prefix is utilized to incorporate user-item collaborative information and adapt the LLM to the recommendation task, while the suffix converts the output embeddings of the LLM from the language space to the recommendation space for the follow-up item recommendation. Furthermore, to capture the characteristics of different types of users when integrating the collaborative information via the prefix, we introduce M-Former, a lightweight MoE-based querying transformer that uses a set of query experts to integrate diverse user-specific collaborative information encoded by frozen ID-based sequential recommender systems, significantly improving the accuracy of recommendations. Extensive experiments on real-world datasets demonstrate that Laser can parameter-efficiently adapt LLMs to effective recommender systems, significantly outperforming state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2409.01605)