# 探究大型语言模型在时间泛化评估中的表现力

发布时间：2024年05月14日

`LLM理论

这篇论文关注的是大型语言模型（LLMs）的评估方法，特别是针对传统评估标准的不足，提出了一个创新的评估框架——Freshbench。这个框架旨在解决LLMs在时间泛化和预测中存在的时间偏差问题，并通过动态生成基于最新现实世界预测的评估基准来更准确地反映模型的实际表现。这属于对LLMs理论层面的探讨和改进，因此归类为LLM理论。` `模型评估`

> Evaluating LLMs at Evaluating Temporal Generalization

# 摘要

> 随着大型语言模型（LLMs）的飞速进步，我们迫切需要与之同步进化的评估方法，以确保能够准确衡量这些模型在语言理解和信息处理上的进步，尤其是在不断变化的信息环境中。传统的评估标准因其静态特性而显得力不从心，它们无法捕捉到现实世界中信息环境的动态变化，从而导致我们对LLMs在实际应用中的表现产生了误解。此外，这些标准也未能全面评估模型在时间维度上的泛化能力和适应性。我们的研究揭示了LLMs在时间泛化和预测中存在的时间偏差，这提醒我们在使用这些模型时必须警惕并努力减少这些偏差。为此，我们提出了一个创新的评估框架——Freshbench，它能够动态生成基于最新现实世界预测的评估基准，以更准确地反映LLMs的实际表现。我们的代码已经公开在GitHub上，而数据集也即将发布。

> The rapid advancement of Large Language Models (LLMs) highlights the urgent need for evolving evaluation methodologies that keep pace with improvements in language comprehension and information processing. However, traditional benchmarks, which are often static, fail to capture the continually changing information landscape, leading to a disparity between the perceived and actual effectiveness of LLMs in ever-changing real-world scenarios. Furthermore, these benchmarks do not adequately measure the models' capabilities over a broader temporal range or their adaptability over time. We examine current LLMs in terms of temporal generalization and bias, revealing that various temporal biases emerge in both language likelihood and prognostic prediction. This serves as a caution for LLM practitioners to pay closer attention to mitigating temporal biases. Also, we propose an evaluation framework Freshbench for dynamically generating benchmarks from the most recent real-world prognostication prediction. Our code is available at https://github.com/FreedomIntelligence/FreshBench. The dataset will be released soon.

[Arxiv](https://arxiv.org/abs/2405.08460)