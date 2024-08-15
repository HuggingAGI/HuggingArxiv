# 通过在成对数据中建立关联模型，实现直接偏好优化

发布时间：2024年08月14日

`LLM理论` `问答系统` `人工智能`

> Bridging and Modeling Correlations in Pairwise Data for Direct Preference Optimization

# 摘要

> 直接偏好优化（DPO）算法通过成对偏好数据对齐大型语言模型（LLM）与人类期望行为，但成对数据中的响应孤立生成，相关性弱且对齐效果不佳。为此，我们提出BMC框架，增强成对数据相关性：首先，通过改进失败响应基于获胜响应合成伪获胜响应，提升信号一致性与信息量；其次，发现DPO无法充分建模这些相关性，故引入策略模型置信度动态学习令牌级相关性。实验表明，我们的方法在QA、数学和指令遵循任务中显著优于DPO等基准，深入分析揭示了其优越性的原因，并展示了其广泛适用性。

> Direct preference optimization (DPO), a widely adopted offline preference optimization algorithm, aims to align large language models (LLMs) with human-desired behaviors using pairwise preference data. However, the winning response and the losing response within pairwise data are generated isolatedly, leading to weak correlations between them as well as suboptimal alignment performance. To address this issue, we propose an effective framework named BMC, for bridging and modeling correlations in pairwise data. Firstly, we increase the consistency and informativeness of the pairwise preference signals by targeted modifications, synthesizing a pseudo winning response through improving the losing response based on the winning response. Secondly, we identify that DPO alone is insufficient to model these correlations and capture nuanced variations. Therefore, we propose learning token-level correlations by dynamically leveraging the policy model's confidence during training. Comprehensive experiments on QA, math, and instruction-following tasks demonstrate the effectiveness of our approach, significantly surpassing competitive baselines, including DPO. Additionally, our in-depth quantitative analysis reveals the reasons behind our method's superior performance over DPO and showcases its versatility to other DPO variants.

[Arxiv](https://arxiv.org/abs/2408.07471)