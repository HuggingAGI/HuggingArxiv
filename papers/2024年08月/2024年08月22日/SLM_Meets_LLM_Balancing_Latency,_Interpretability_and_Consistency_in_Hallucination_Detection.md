# 当 SLM 与 LLM 相遇，我们致力于在幻觉检测中实现延迟、可解释性和一致性的平衡。

发布时间：2024年08月22日

`LLM应用` `互联网` `人工智能`

> SLM Meets LLM: Balancing Latency, Interpretability and Consistency in Hallucination Detection

# 摘要

> 大型语言模型虽强，但在实时应用中存在延迟问题，如在线幻觉检测。为此，我们设计了一个新框架：先用小型语言模型分类器初筛，再用大型语言模型深入解析。通过精妙的提示技术，确保解释与初筛一致，优化了实时检测。实验证明有效，大幅提升了用户体验。

> Large language models (LLMs) are highly capable but face latency challenges in real-time applications, such as conducting online hallucination detection. To overcome this issue, we propose a novel framework that leverages a small language model (SLM) classifier for initial detection, followed by a LLM as constrained reasoner to generate detailed explanations for detected hallucinated content. This study optimizes the real-time interpretable hallucination detection by introducing effective prompting techniques that align LLM-generated explanations with SLM decisions. Empirical experiment results demonstrate its effectiveness, thereby enhancing the overall user experience.

[Arxiv](https://arxiv.org/abs/2408.12748)