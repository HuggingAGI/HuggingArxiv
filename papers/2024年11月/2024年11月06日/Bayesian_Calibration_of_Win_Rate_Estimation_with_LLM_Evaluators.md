# 贝叶斯校准具有 LLM 评估器的胜率估计

发布时间：2024年11月06日

`LLM应用` `语言模型` `文本评估`

> Bayesian Calibration of Win Rate Estimation with LLM Evaluators

# 摘要

> 大型语言模型（LLMs）的最新进展显示了使用 LLMs 作为评估器来评估 LLMs 生成的文本质量的潜力。然而，天真地应用 LLM 评估器来比较或判断不同系统可能会由于 LLM 评估器固有的胜率估计偏差而导致不可靠的结果。为了减轻这个问题，我们提出了两种校准方法，贝叶斯胜率抽样（BWRS）和贝叶斯 Dawid-Skene，这两种方法都利用贝叶斯推理来更准确地推断生成语言模型的真实胜率。我们在涵盖故事生成、摘要和指令遵循任务的六个数据集上对我们的方法进行了实证验证。我们表明，我们的两种方法在使用 LLMs 作为评估器提高胜率估计的准确性方面都是有效的，为可靠的自动文本质量评估提供了一个有前途的方向。

> Recent advances in large language models (LLMs) show the potential of using LLMs as evaluators for assessing the quality of text generations from LLMs. However, applying LLM evaluators naively to compare or judge between different systems can lead to unreliable results due to the intrinsic win rate estimation bias of LLM evaluators. In order to mitigate this problem, we propose two calibration methods, Bayesian Win Rate Sampling (BWRS) and Bayesian Dawid-Skene, both of which leverage Bayesian inference to more accurately infer the true win rate of generative language models. We empirically validate our methods on six datasets covering story generation, summarization, and instruction following tasks. We show that both our methods are effective in improving the accuracy of win rate estimation using LLMs as evaluators, offering a promising direction for reliable automatic text quality evaluation.

[Arxiv](https://arxiv.org/abs/2411.04424)