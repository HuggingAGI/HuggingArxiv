# 从连续提示的表示中提取文本描述

发布时间：2024年10月15日

`LLM理论` `人工智能`

> Eliciting Textual Descriptions from Representations of Continuous Prompts

# 摘要

> 连续提示（软提示）虽是大型语言模型中常用的参数高效调优策略，但其不透明性常令人诟病。以往的解释方法多将单个提示标记映射到词汇空间，然而，这种方法可能导致任意或矛盾的文本，且仅单独解释标记。我们提出一种新方法，在模型推理时从提示表示中提取文本描述。通过 InSPEcT（Patchscopes 的变体），我们发现该方法在多种任务中能生成准确的任务描述，且随着任务性能提升，描述的准确性也提高。此外，InSPEcT 还能揭示提示中的偏差特征，这些特征与模型预测的偏差相关。InSPEcT 不仅提供了一种有效的解释方案，还能帮助开发者调试和缓解连续提示中的不良属性。

> Continuous prompts, or "soft prompts", are a widely-adopted parameter-efficient tuning strategy for large language models, but are often less favorable due to their opaque nature. Prior attempts to interpret continuous prompts relied on projecting individual prompt tokens onto the vocabulary space. However, this approach is problematic as performant prompts can yield arbitrary or contradictory text, and it interprets prompt tokens individually. In this work, we propose a new approach to interpret continuous prompts that elicits textual descriptions from their representations during model inference. Using a Patchscopes variant (Ghandeharioun et al., 2024) called InSPEcT over various tasks, we show our method often yields accurate task descriptions which become more faithful as task performance increases. Moreover, an elaborated version of InSPEcT reveals biased features in continuous prompts, whose presence correlates with biased model predictions. Providing an effective interpretability solution, InSPEcT can be leveraged to debug unwanted properties in continuous prompts and inform developers on ways to mitigate them.

[Arxiv](https://arxiv.org/abs/2410.11660)