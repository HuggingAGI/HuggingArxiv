# 大型语言模型中的评估数据污染：我们如何测量它以及（何时）它重要？

发布时间：2024年11月06日

`LLM应用` `语言模型` `评估指标`

> Evaluation data contamination in LLMs: how do we measure it and (when) does it matter?

# 摘要

> 妨碍基准分数的解释，评估数据污染在大型语言模型（LLM）的评估中已成为一个日益令人担忧的问题，并且一个活跃的研究领域正在研究其影响。虽然评估数据污染直观上很容易理解，但令人惊讶的是，很难精确地定义哪些样本应被视为受污染，因此，也很难确定它如何影响基准分数。我们建议这些问题应一起解决，并且可以根据模型是否从它们标记为受污染的示例中受益来评估污染指标。我们提出了一种称为 ConTAM 的新分析方法，并通过对来自 2 个不同家族的 13 个基准和 7 个模型的现有和新的基于 n 元语法的污染指标进行大规模调查表明，ConTAM 可用于更好地理解评估数据污染及其影响。我们发现，污染可能比最近的 LLM 发布中所报告的影响大得多，并且在不同规模上对模型的益处不同。我们还发现，仅考虑最长的受污染子串比考虑所有受污染子串的并集提供了更好的信号，并且进行特定于模型和基准的阈值分析大大提高了结果的特异性。最后，我们研究了超参数选择的影响，发现除其他事项外，使用较大的 n 值和忽略在预训练数据中不常见的匹配会导致许多假阴性。通过 ConTAM，我们提供了一种根据下游影响对评估数据污染指标进行实证基础的方法。通过我们的探索，我们揭示了评估数据污染如何影响 LLM，并为进行污染分析时的重要考虑因素提供了见解。我们在论文的结尾更详细地讨论了这些内容，并为未来的工作提供了具体的建议。

> Hampering the interpretation of benchmark scores, evaluation data contamination has become a growing concern in the evaluation of LLMs, and an active area of research studies its effects. While evaluation data contamination is easily understood intuitively, it is surprisingly difficult to define precisely which samples should be considered contaminated and, consequently, how it impacts benchmark scores. We propose that these questions should be addressed together and that contamination metrics can be assessed based on whether models benefit from the examples they mark contaminated. We propose a novel analysis method called ConTAM, and show with a large scale survey of existing and novel n-gram based contamination metrics across 13 benchmarks and 7 models from 2 different families that ConTAM can be used to better understand evaluation data contamination and its effects. We find that contamination may have a much larger effect than reported in recent LLM releases and benefits models differently at different scales. We also find that considering only the longest contaminated substring provides a better signal than considering a union of all contaminated substrings, and that doing model and benchmark specific threshold analysis greatly increases the specificity of the results. Lastly, we investigate the impact of hyperparameter choices, finding that, among other things, both using larger values of n and disregarding matches that are infrequent in the pre-training data lead to many false negatives. With ConTAM, we provide a method to empirically ground evaluation data contamination metrics in downstream effects. With our exploration, we shed light on how evaluation data contamination can impact LLMs and provide insight into the considerations important when doing contamination analysis. We end our paper by discussing these in more detail and providing concrete suggestions for future work.

[Arxiv](https://arxiv.org/abs/2411.03923)