# 奖励增强数据助力 LLM 直接偏好对齐

发布时间：2024年10月10日

`LLM理论` `人工智能`

> Reward-Augmented Data Enhances Direct Preference Alignment of LLMs

# 摘要

> 大型语言模型（LLM）中的偏好对齐显著提升了其遵循人类指令的能力。然而，现有算法多关注相对偏好，忽视了响应的质性。我们提出了一种奖励条件化的策略，通过辨别并学习数据集中所有响应质量，帮助模型外推至更优区域。实验表明，该方法在多个基准测试中显著提升了模型性能，并有效缓解了遗忘问题。代码已开源。

> Preference alignment in Large Language Models (LLMs) has significantly improved their ability to adhere to human instructions and intentions. However, existing direct alignment algorithms primarily focus on relative preferences and often overlook the qualitative aspects of responses. Striving to maximize the implicit reward gap between the chosen and the slightly inferior rejected responses can cause overfitting and unnecessary unlearning of the high-quality rejected responses. The unawareness of the reward scores also drives the LLM to indiscriminately favor the low-quality chosen responses and fail to generalize to responses with the highest rewards, which are sparse in data. To overcome these shortcomings, our study introduces reward-conditioned LLM policies that discern and learn from the entire spectrum of response quality within the dataset, helping extrapolate to more optimal regions. We propose an effective yet simple data relabeling method that conditions the preference pairs on quality scores to construct a reward-augmented dataset. This dataset is easily integrated with existing direct alignment algorithms and is applicable to any preference dataset. The experimental results across instruction-following benchmarks including AlpacaEval, MT-Bench, and Arena-Hard-Auto demonstrate that our approach consistently boosts the performance of DPO by a considerable margin across diverse models. Additionally, our method improves the average accuracy on various academic benchmarks. When applying our method to on-policy data, the resulting DPO model achieves SOTA results on AlpacaEval. Through ablation studies, we demonstrate that our method not only maximizes the utility of preference data but also mitigates the issue of unlearning, demonstrating its broad effectiveness beyond mere dataset expansion. Our code is available at https://github.com/shenao-zhang/reward-augmented-preference.

[Arxiv](https://arxiv.org/abs/2410.08067)