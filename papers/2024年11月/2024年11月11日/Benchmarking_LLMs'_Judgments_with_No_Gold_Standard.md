# 用没有黄金标准的方法对大型语言模型的判断进行基准测试

发布时间：2024年11月11日

`LLM应用` `学术研究` `语言模型评估`

> Benchmarking LLMs' Judgments with No Gold Standard

# 摘要

> 我们引入了 GEM（互信息生成估计器），这是一种用于评估大型语言模型（LLM）语言生成的评估指标，特别是在生成信息性判断方面，无需黄金标准参考。GEM 拓宽了我们可以对 LLM 生成性能进行基准测试的场景——从传统的场景，如机器翻译和摘要，在这些场景中黄金标准参考很容易获得，到没有明确黄金标准的主观任务，如学术同行评审。
  GEM 使用生成模型来估计候选响应和参考响应之间的互信息，无需参考是黄金标准。在对人工注释数据集的实验中，与最先进的 GPT-4o 审查员相比，GEM 显示出与人类得分的竞争相关性，并优于所有其他基线。此外，GEM 对策略性操作（如改写或延长）更具鲁棒性，这些操作在 GPT-4o 审查员下可能人为地提高分数。
  我们还展示了 GRE-bench（生成评论评估基准），它根据大型语言模型为学术研究论文生成高质量同行评审的能力来评估它们。因为 GRE-bench 基于 GEM，所以它继承了其鲁棒性属性。此外，GRE-bench 通过每年使用新的开放获取研究论文和同行评审的持续涌入来避免数据污染问题（或数据泄漏）。我们使用 ICLR2023 数据集展示了各种流行的 LLM 在其同行评审能力方面的 GRE-bench 结果。

> We introduce the GEM (Generative Estimator for Mutual Information), an evaluation metric for assessing language generation by Large Language Models (LLMs), particularly in generating informative judgments, without the need for a gold standard reference. GEM broadens the scenarios where we can benchmark LLM generation performance-from traditional ones, like machine translation and summarization, where gold standard references are readily available, to subjective tasks without clear gold standards, such as academic peer review.
  GEM uses a generative model to estimate mutual information between candidate and reference responses, without requiring the reference to be a gold standard. In experiments on a human-annotated dataset, GEM demonstrates competitive correlations with human scores compared to the state-of-the-art GPT-4o Examiner, and outperforms all other baselines. Additionally, GEM is more robust against strategic manipulations, such as rephrasing or elongation, which can artificially inflate scores under a GPT-4o Examiner.
  We also present GRE-bench (Generating Review Evaluation Benchmark) which evaluates LLMs based on how well they can generate high-quality peer reviews for academic research papers. Because GRE-bench is based upon GEM, it inherits its robustness properties. Additionally, GRE-bench circumvents data contamination problems (or data leakage) by using the continuous influx of new open-access research papers and peer reviews each year. We show GRE-bench results of various popular LLMs on their peer review capabilities using the ICLR2023 dataset.

[Arxiv](https://arxiv.org/abs/2411.07127)