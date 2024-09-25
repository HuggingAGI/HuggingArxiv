# NLP 模型的隐私评估标准

发布时间：2024年09月24日

`LLM应用` `网络安全`

> Privacy Evaluation Benchmarks for NLP Models

# 摘要

> 通过在 NLP 模型上实施隐私攻击，攻击者能够获取训练数据和模型参数等敏感信息。尽管已有研究深入探讨了几种 NLP 模型中的攻击，但这些分析缺乏系统性，未能全面理解攻击的影响。例如，我们需要明确哪些攻击适用于哪些场景，不同攻击的性能受哪些共同因素影响，攻击之间的关系如何，以及数据集和模型如何影响攻击效果。因此，我们需要一个基准来全面评估 NLP 模型的隐私风险。本文提出一个 NLP 领域的隐私攻击与防御评估基准，涵盖常规/小型模型及大型语言模型 (LLM)。该基准支持多种模型、数据集和协议，并提供标准化模块，用于全面评估攻击与防御策略。基于此框架，我们探讨了不同领域辅助数据与隐私攻击强度之间的关联，并在知识蒸馏 (KD) 的帮助下，提出了一种改进的攻击方法。此外，我们设计了一个链式框架，允许将多个攻击链接起来，以实现更高级别的攻击目标，并提供了相应的防御与增强攻击策略。相关代码可在 https://github.com/user2311717757/nlp_doctor 获取。

> By inducing privacy attacks on NLP models, attackers can obtain sensitive information such as training data and model parameters, etc. Although researchers have studied, in-depth, several kinds of attacks in NLP models, they are non-systematic analyses. It lacks a comprehensive understanding of the impact caused by the attacks. For example, we must consider which scenarios can apply to which attacks, what the common factors are that affect the performance of different attacks, the nature of the relationships between different attacks, and the influence of various datasets and models on the effectiveness of the attacks, etc. Therefore, we need a benchmark to holistically assess the privacy risks faced by NLP models. In this paper, we present a privacy attack and defense evaluation benchmark in the field of NLP, which includes the conventional/small models and large language models (LLMs). This benchmark supports a variety of models, datasets, and protocols, along with standardized modules for comprehensive evaluation of attacks and defense strategies. Based on the above framework, we present a study on the association between auxiliary data from different domains and the strength of privacy attacks. And we provide an improved attack method in this scenario with the help of Knowledge Distillation (KD). Furthermore, we propose a chained framework for privacy attacks. Allowing a practitioner to chain multiple attacks to achieve a higher-level attack objective. Based on this, we provide some defense and enhanced attack strategies. The code for reproducing the results can be found at https://github.com/user2311717757/nlp_doctor.

[Arxiv](https://arxiv.org/abs/2409.15868)