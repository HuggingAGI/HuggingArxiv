# 通过去混杂因果感知参数高效微调，提升 LLMs 的问题解决能力

发布时间：2024年09月04日

`LLM理论` `人工智能`

> Deconfounded Causality-aware Parameter-Efficient Fine-Tuning for Problem-Solving Improvement of LLMs

# 摘要

> 尽管大型语言模型 (LLM) 在执行人类指令的任务上效率显著，但在处理需要推理的问题时，如数学或物理题，其表现往往不尽人意。这引发了关于模型是否真正理解文本知识，还是仅模仿表面形式的疑问。本文深入探讨此问题，旨在提升 LLM 的推理能力。我们首先通过可视化文本生成过程，从注意力和表示层面考察模型的推理能力。接着，将推理过程构建为因果框架，为观察到的现象提供理论解释。基于此框架，我们创新提出去混杂因果适应 (DCA) 方法，通过优化参数微调，强化模型的问题解决技能，使其能灵活应用于各类问题。实验证明，DCA 方法在多个测试中稳定超越传统基线，仅需少量参数调整，即能实现与其他先进微调方法相媲美甚至更优的性能。这充分展现了 DCA 在提升 LLM 准确性与可靠性的高效与实效。

> Large Language Models (LLMs) have demonstrated remarkable efficiency in tackling various tasks based on human instructions, but recent studies reveal that these models often fail to achieve satisfactory results on questions involving reasoning, such as mathematics or physics questions. This phenomenon is usually attributed to the uncertainty regarding whether these models could genuinely comprehend the knowledge embedded in the text or merely learn to replicate the token distribution without a true understanding of the content. In this paper, we delve into this problem and aim to enhance the reasoning capabilities of LLMs. First, we investigate if the model has genuine reasoning capabilities by visualizing the text generation process at the attention and representation level. Then, we formulate the reasoning process of LLMs into a causal framework, which provides a formal explanation of the problems we observe in the visualization. Finally, building upon this causal framework, we propose Deconfounded Causal Adaptation (DCA), a novel parameter-efficient fine-tuning (PEFT) method to enhance the model's reasoning capabilities by encouraging the model to extract the general problem-solving skills and apply these skills to different questions. Experiments show that our method outperforms the baseline consistently across multiple benchmarks, and with only 1.2M tunable parameters, we achieve better or comparable results to other fine-tuning methods. This demonstrates the effectiveness and efficiency of our method in improving the overall accuracy and reliability of LLMs.

[Arxiv](https://arxiv.org/abs/2409.02686)