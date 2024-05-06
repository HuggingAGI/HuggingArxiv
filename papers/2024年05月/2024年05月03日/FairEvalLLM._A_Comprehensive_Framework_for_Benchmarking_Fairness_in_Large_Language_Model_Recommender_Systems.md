# FairEvalLLM，为大型语言模型推荐系统公平性评估提供了一个全面的基准框架。

发布时间：2024年05月03日

`LLM应用` `推荐系统` `公平性评估`

> FairEvalLLM. A Comprehensive Framework for Benchmarking Fairness in Large Language Model Recommender Systems

# 摘要

> 本论文介绍了一套评估大型语言模型驱动的推荐系统（RecLLMs）公平性的框架，旨在整合包括用户属性敏感度、内在公平性以及基于潜在益处的公平性讨论等多个公平维度。该框架还引入了反事实评估，并考虑了不同用户群体的多样性，以丰富RecLLMs公平性评估的讨论。我们的主要贡献是构建了一个稳健的LLM推荐系统公平性评估框架，并提出了一种从人口统计数据、用户历史偏好和最新互动中构建“信息丰富的用户档案”的结构化方法。我们强调，这对于提升系统个性化，尤其是在时间敏感场景中至关重要。通过在LastFM-1K和ML-1M两个数据集上的应用实例，我们展示了框架的实用性。我们对每个数据集中的80名用户子样本进行了实验，测试了超过50种不同的提示构建和上下文学习场景，产生了4000多个推荐。研究发现，尽管在涉及敏感属性的场景中未发现显著的不公平问题，但在不涉及直接敏感性的内在公平性方面，不同人口统计群体之间仍存在显著的不公平现象。本研究使用的相关代码和数据已在\url{https://shorturl.at/awBFM}上公开。

> This paper presents a framework for evaluating fairness in recommender systems powered by Large Language Models (RecLLMs), addressing the need for a unified approach that spans various fairness dimensions including sensitivity to user attributes, intrinsic fairness, and discussions of fairness based on underlying benefits. In addition, our framework introduces counterfactual evaluations and integrates diverse user group considerations to enhance the discourse on fairness evaluation for RecLLMs.
  Our key contributions include the development of a robust framework for fairness evaluation in LLM-based recommendations and a structured method to create \textit{informative user profiles} from demographic data, historical user preferences, and recent interactions. We argue that the latter is essential for enhancing personalization in such systems, especially in temporal-driven scenarios. We demonstrate the utility of our framework through practical applications on two datasets, LastFM-1K and ML-1M. We conduct experiments on a subsample of 80 users from each dataset, testing and assessing the effectiveness of various prompt construction scenarios and in-context learning, comprising more than 50 scenarios. This results in more than 4000 recommendations (80 * 50 = 4000). Our study reveals that while there are no significant unfairness issues in scenarios involving sensitive attributes, some concerns remain. However, in terms of intrinsic fairness, which does not involve direct sensitivity, unfairness across demographic groups remains significant. The code and data used for this paper are available at: \url{https://shorturl.at/awBFM}.

[Arxiv](https://arxiv.org/abs/2405.02219)