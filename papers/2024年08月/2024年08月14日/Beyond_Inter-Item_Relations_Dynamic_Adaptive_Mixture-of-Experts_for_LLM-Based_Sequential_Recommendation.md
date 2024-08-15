# 突破项目间关系的限制，我们提出了一种基于LLM的序列推荐系统，采用动态自适应的混合专家模型，以提升推荐效果。

发布时间：2024年08月14日

`LLM应用` `人工智能`

> Beyond Inter-Item Relations: Dynamic Adaptive Mixture-of-Experts for LLM-Based Sequential Recommendation

# 摘要

> 顺序推荐系统 (SRS) 通过分析用户历史行为预测其下一偏好。随着大型语言模型 (LLM) 在 AI 领域的广泛应用，基于 LLM 的 SRS 研究日益增多。尽管这些系统性能卓越，但仍存在忽视项目内部关联、忽略长期协作信息及架构适应性差等问题。为此，我们推出了 MixRec，一种基于 LLM 的 SRS，它通过粗粒度适应捕捉项目间关系，并引入 (1) 上下文掩码以深入理解项目语义，(2) 协作知识注入强化长期协作信息的整合，以及 (3) 动态自适应的混合专家架构，根据贝叶斯优化灵活选择架构，优化序列信息的处理。实验证明，MixRec 能高效动态地适应并提升推荐效果。

> Sequential recommender system (SRS) predicts the next items that users may prefer based on user historical interaction sequences. Inspired by the rise of large language models (LLMs) in various AI applications, there is a surge of work on LLM-based SRS. Despite their attractive performance, existing LLM-based SRS still exhibit some limitations, including neglecting intra-item relations, ignoring long-term collaborative knowledge and using inflexible architecture designs for adaption. To alleviate these issues, we propose an LLM-based SRS named MixRec. Built on top of coarse-grained adaption for capturing inter-item relations, MixRec is further enhanced with (1) context masking that models intra-item relations to help LLM better understand token and item semantics in the context of SRS, (2) collaborative knowledge injection that helps LLM incorporate long-term collaborative knowledge, and (3) a dynamic adaptive mixture-of-experts design that can flexibly choose expert architectures based on Bayesian optimization to better incorporate different sequential information. Extensive experiments demonstrate that MixRec can effectively handle sequential recommendation in a dynamic and adaptive manner.

[Arxiv](https://arxiv.org/abs/2408.07427)