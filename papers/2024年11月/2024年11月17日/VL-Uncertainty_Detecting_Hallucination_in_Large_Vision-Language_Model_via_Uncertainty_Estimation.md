# VL-不确定性：借助不确定性估计来检测大型视觉语言模型中的幻觉现象

发布时间：2024年11月17日

`LLM应用` `视觉语言模型` `幻觉检测`

> VL-Uncertainty: Detecting Hallucination in Large Vision-Language Model via Uncertainty Estimation

# 摘要

> 由于大型视觉语言模型（LVLMs）处理的信息量比单模态的大型语言模型（LLMs）更多，检测LVLM的幻觉需要耗费更多人力和时间，也引发了更广泛的安全忧虑。在本文中，我们推出了VL-Uncertainty，这是首个用于检测LVLMs中幻觉的基于不确定性的框架。和大多数需要真实标注或伪标注的现有方法不同，VL-Uncertainty把不确定性当作一种内在指标。我们通过分析在语义等效但受干扰的提示（涵盖视觉和文本数据）下的预测方差来衡量不确定性。当LVLMs信心满满时，它们对语义相同的查询给出一致的回应。然而，当不确定时，目标LVLM的回应就会变得更随机。考虑到语义相似但措辞不同的答案，我们依据其语义内容对LVLM的回应进行聚类，然后将聚类分布熵当作检测幻觉的不确定性度量。我们在涵盖自由形式和多项选择任务的四个基准上对10个LVLMs展开了大量实验，结果显示VL-Uncertainty在幻觉检测方面显著优于强大的基线方法。

> Given the higher information load processed by large vision-language models (LVLMs) compared to single-modal LLMs, detecting LVLM hallucinations requires more human and time expense, and thus rise a wider safety concerns. In this paper, we introduce VL-Uncertainty, the first uncertainty-based framework for detecting hallucinations in LVLMs. Different from most existing methods that require ground-truth or pseudo annotations, VL-Uncertainty utilizes uncertainty as an intrinsic metric. We measure uncertainty by analyzing the prediction variance across semantically equivalent but perturbed prompts, including visual and textual data. When LVLMs are highly confident, they provide consistent responses to semantically equivalent queries. However, when uncertain, the responses of the target LVLM become more random. Considering semantically similar answers with different wordings, we cluster LVLM responses based on their semantic content and then calculate the cluster distribution entropy as the uncertainty measure to detect hallucination. Our extensive experiments on 10 LVLMs across four benchmarks, covering both free-form and multi-choice tasks, show that VL-Uncertainty significantly outperforms strong baseline methods in hallucination detection.

[Arxiv](https://arxiv.org/abs/2411.11919)