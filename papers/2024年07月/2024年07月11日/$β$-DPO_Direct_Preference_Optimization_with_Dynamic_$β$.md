# 动态 $β$ 直接偏好优化（$β$-DPO）

发布时间：2024年07月11日

`LLM理论` `人工智能` `数据科学`

> $β$-DPO: Direct Preference Optimization with Dynamic $β$

# 摘要

> Direct Preference Optimization (DPO) 已成为训练大型语言模型 (LLM) 遵循人类偏好的有力方法。但 DPO 性能对 $β$ 参数的微调和数据质量极为敏感。我们研究发现，最佳 $β$ 值因数据信息量而异。为此，我们提出动态调整 $β$ 的新框架，并结合 $β$ 引导的数据过滤，有效提升 DPO 性能，增强模型对人类反馈的适应性。实证显示，该技术在多模型和数据集上表现卓越。代码已公开，详见 \url{https://github.com/junkangwu/beta-DPO}。

> Direct Preference Optimization (DPO) has emerged as a compelling approach for training Large Language Models (LLMs) to adhere to human preferences. However, the performance of DPO is sensitive to the fine-tuning of its trade-off parameter $β$, as well as to the quality of the preference data. We analyze the impact of $β$ and data quality on DPO, uncovering that optimal $β$ values vary with the informativeness of pairwise data. Addressing the limitations of static $β$ values, we introduce a novel framework that dynamically calibrates $β$ at the batch level, informed by data quality considerations. Additionally, our method incorporates $β$-guided data filtering to safeguard against the influence of outliers. Through empirical evaluation, we demonstrate that our dynamic $β$ adjustment technique significantly improves DPO's performance across a range of models and datasets, offering a more robust and adaptable training paradigm for aligning LLMs with human feedback. The code is available at \url{https://github.com/junkangwu/beta-DPO}.

[Arxiv](https://arxiv.org/abs/2407.08639)