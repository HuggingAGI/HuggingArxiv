# GenderCARE：一个全面框架，旨在评估并减少大型语言模型中的性别偏见。

发布时间：2024年08月22日

`LLM应用` `社会科学` `人工智能`

> GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models

# 摘要

> 大型语言模型虽在自然语言生成上表现出色，却也放大了社会偏见，尤其是性别偏见。为此，我们推出了 GenderCARE 框架，旨在通过创新准则、全面评估、减少技术和量化指标，有效应对和缓解 LLM 中的性别偏见。我们首先确立了涵盖包容性、多样性等维度的性别平等基准，进而构建了 GenderPair 基准，全面评估性别偏见，包括跨性别者等以往被忽视的群体。我们还开发了去偏见技术，通过反事实数据增强和微调策略，有效减少偏见而不影响模型性能。实验显示，性别偏见在多个基准上显著减少，平均超过 35%，且在主流语言任务中的变异性极低。我们希望通过 GenderCARE，推动 LLM 向更公平、更公正的方向迈进。更多详情请访问 https://github.com/kstanghere/GenderCARE-ccs24。

> Large language models (LLMs) have exhibited remarkable capabilities in natural language generation, but they have also been observed to magnify societal biases, particularly those related to gender. In response to this issue, several benchmarks have been proposed to assess gender bias in LLMs. However, these benchmarks often lack practical flexibility or inadvertently introduce biases. To address these shortcomings, we introduce GenderCARE, a comprehensive framework that encompasses innovative Criteria, bias Assessment, Reduction techniques, and Evaluation metrics for quantifying and mitigating gender bias in LLMs. To begin, we establish pioneering criteria for gender equality benchmarks, spanning dimensions such as inclusivity, diversity, explainability, objectivity, robustness, and realisticity. Guided by these criteria, we construct GenderPair, a novel pair-based benchmark designed to assess gender bias in LLMs comprehensively. Our benchmark provides standardized and realistic evaluations, including previously overlooked gender groups such as transgender and non-binary individuals. Furthermore, we develop effective debiasing techniques that incorporate counterfactual data augmentation and specialized fine-tuning strategies to reduce gender bias in LLMs without compromising their overall performance. Extensive experiments demonstrate a significant reduction in various gender bias benchmarks, with reductions peaking at over 90% and averaging above 35% across 17 different LLMs. Importantly, these reductions come with minimal variability in mainstream language tasks, remaining below 2%. By offering a realistic assessment and tailored reduction of gender biases, we hope that our GenderCARE can represent a significant step towards achieving fairness and equity in LLMs. More details are available at https://github.com/kstanghere/GenderCARE-ccs24.

[Arxiv](https://arxiv.org/abs/2408.12494)