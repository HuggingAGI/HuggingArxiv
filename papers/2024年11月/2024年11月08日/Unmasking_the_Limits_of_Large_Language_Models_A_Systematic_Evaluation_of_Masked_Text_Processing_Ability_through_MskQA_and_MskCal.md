# 揭示大型语言模型的局限性：通过 MskQA 和 MskCal 对掩码文本处理能力的系统评估

发布时间：2024年11月08日

`LLM应用` `语言模型评估`

> Unmasking the Limits of Large Language Models: A Systematic Evaluation of Masked Text Processing Ability through MskQA and MskCal

# 摘要

> 这篇论文通过严格评估大型语言模型（LLM）处理掩码文本的能力，揭示了它们的局限性。我们引入了两个新任务：MskQA，用于测量在像 RealtimeQA 这样的掩码问答数据集上的推理能力；MskCal，用于评估在掩码算术问题上的数值推理能力。对 GPT-4o 和 4o-mini 的测试表明，虽然 LLM 对掩码文本表现出一定的适应性，但它们的性能在很大程度上取决于掩码率和语义线索。具体来说，与保留了一些语义信息的“部分解除掩码”相比，“完全掩码”（其中语义线索完全不存在）会导致性能显著下降，这表明 LLM 依赖于表面模式。有趣的是，GPT-4o 在 MskCal 中始终优于 4o-mini，表现出处理掩码文本的数值推理的更强能力。这突显了语义线索在 LLM 推理过程中的关键作用。我们的研究阐明了在掩码文本处理中背景知识和推理能力之间的相互作用，为更深入地理解 LLM 的能力和局限性铺平了道路，并强调了需要更强大的评估方法来准确评估它们的真正理解能力。

> This paper sheds light on the limitations of Large Language Models (LLMs) by rigorously evaluating their ability to process masked text. We introduce two novel tasks: MskQA, measuring reasoning on masked question-answering datasets like RealtimeQA, and MskCal, assessing numerical reasoning on masked arithmetic problems.Testing GPT-4o and 4o-mini reveals that while LLMs exhibit some resilience to masked text, their performance is highly contingent on masking rates and semantic cues. Specifically, "solid masking," where semantic clues are entirely absent, leads to a significant performance drop compared to "partial lifting," where some semantic information is retained, indicating LLMs' reliance on surface-level patterns. Interestingly, GPT-4o consistently outperforms 4o-mini, particularly in MskCal, demonstrating a greater ability to handle numerical reasoning with masked text. This underscores the crucial role of semantic cues in the reasoning process of LLMs. Our study illuminates the interplay between background knowledge and reasoning ability in masked text processing, paving the way for a deeper understanding of LLM capabilities and limitations, and highlighting the need for more robust evaluation methods to accurately assess their true comprehension abilities.

[Arxiv](https://arxiv.org/abs/2411.05665)