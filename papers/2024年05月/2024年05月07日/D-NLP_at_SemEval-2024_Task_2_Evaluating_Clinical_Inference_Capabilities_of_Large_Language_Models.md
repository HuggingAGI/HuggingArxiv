# SemEval-2024 第二任务：探究大型语言模型在临床推理领域的评估能力在 SemEval-2024 的第二项任务中，我们将深入探讨大型语言模型在临床推理方面的表现。这项研究旨在评估这些模型在处理医疗相关文本时的推理能力，以及它们如何理解和分析临床情境中的复杂信息。通过这一评估，我们期望能够揭示大型语言模型在医疗领域应用中的潜力和局限性，为未来的医疗人工智能发展提供宝贵的见解。

发布时间：2024年05月07日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在临床试验报告的自然语言推理能力方面。它分析了LLMs在处理医学缩写和数值推理难题时的表现，并通过Gemini模型的测试结果展示了LLMs在医疗推理任务中的潜力。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在特定领域（医疗）的实际应用和性能评估。`

> D-NLP at SemEval-2024 Task 2: Evaluating Clinical Inference Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）因其卓越的性能在多个领域备受瞩目，但同时也伴随着幻觉、事实错误和数值推理局限等挑战。在医疗领域，LLMs的应用引发了关于准确性、安全性和固有限制的讨论。本文深入探讨了LLMs在临床试验报告上的自然语言推理能力，揭示了它们在处理医学缩写和数值推理难题时的表现。Gemini，作为我们的旗舰LLM，在测试中以0.748的F1分数位列第九，展现了其在医疗推理任务中的潜力。我们的研究首次全面审视了LLMs在医疗领域的推理能力，为未来的医疗AI应用提供了宝贵的见解。

> Large language models (LLMs) have garnered significant attention and widespread usage due to their impressive performance in various tasks. However, they are not without their own set of challenges, including issues such as hallucinations, factual inconsistencies, and limitations in numerical-quantitative reasoning. Evaluating LLMs in miscellaneous reasoning tasks remains an active area of research. Prior to the breakthrough of LLMs, Transformers had already proven successful in the medical domain, effectively employed for various natural language understanding (NLU) tasks. Following this trend, LLMs have also been trained and utilized in the medical domain, raising concerns regarding factual accuracy, adherence to safety protocols, and inherent limitations. In this paper, we focus on evaluating the natural language inference capabilities of popular open-source and closed-source LLMs using clinical trial reports as the dataset. We present the performance results of each LLM and further analyze their performance on a development set, particularly focusing on challenging instances that involve medical abbreviations and require numerical-quantitative reasoning. Gemini, our leading LLM, achieved a test set F1-score of 0.748, securing the ninth position on the task scoreboard. Our work is the first of its kind, offering a thorough examination of the inference capabilities of LLMs within the medical domain.

[Arxiv](https://arxiv.org/abs/2405.04170)