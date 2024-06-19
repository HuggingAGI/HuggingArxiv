# PRePair：强化指令遵循评估的点式推理与配对评估结合策略

发布时间：2024年06月18日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在自然语言生成（NLG）任务中的评估方法，特别是对比了基于LLM的逐点评估与配对评估方法，并提出了一种结合逐点推理的混合评估方法。这些内容主要关注LLM在实际应用中的评估问题，因此属于LLM应用分类。` `评估方法`

> PRePair: Pointwise Reasoning Enhance Pairwise Evaluating for Robust Instruction-Following Assessments

# 摘要

> 大型语言模型（LLMs）常用于自然语言生成（NLG）任务的配对评估，但其可靠性常因偏好冗长和权威语气等偏见而受损。本研究对比了基于LLM的逐点评估与配对评估方法，发现逐点评估更能抵御不良偏好。尽管配对评估能准确指出低质量输出的不足，但其判断有时并不准确，显示出LLMs在配对评估中更易受偏见影响。为此，我们提出了一种结合逐点推理的混合评估方法，实验证明该方法在保持对正常样本准确性的同时，显著提升了对抗样本的鲁棒性。

> Pairwise evaluation using large language models (LLMs) is widely used for evaluating natural language generation (NLG) tasks. However, the reliability of LLMs is often compromised by biases, such as favoring verbosity and authoritative tone. In the study, we focus on the comparison of two LLM-based evaluation approaches, pointwise and pairwise. Our findings demonstrate that pointwise evaluators exhibit more robustness against undesirable preferences. Further analysis reveals that pairwise evaluators can accurately identify the shortcomings of low-quality outputs even when their judgment is incorrect. These results indicate that LLMs are more severely influenced by their bias in a pairwise evaluation setup. To mitigate this, we propose a hybrid method that integrates pointwise reasoning into pairwise evaluation. Experimental results show that our method enhances the robustness of pairwise evaluators against adversarial samples while preserving accuracy on normal samples.

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x1.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x2.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x3.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x4.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x5.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x6.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x8.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x9.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x10.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x11.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x12.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x13.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x14.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x15.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x16.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x18.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x19.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x21.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x22.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x24.png)

![PRePair：强化指令遵循评估的点式推理与配对评估结合策略](../../../paper_images/2406.12319/x25.png)

[Arxiv](https://arxiv.org/abs/2406.12319)