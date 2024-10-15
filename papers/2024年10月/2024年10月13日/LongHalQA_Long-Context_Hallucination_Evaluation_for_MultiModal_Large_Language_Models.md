# LongHalQA：评估多模态大型语言模型在长上下文中的幻觉现象

发布时间：2024年10月13日

`LLM应用` `人工智能` `计算机视觉`

> LongHalQA: Long-Context Hallucination Evaluation for MultiModal Large Language Models

# 摘要

> 幻觉现象，即多模态大型语言模型 (MLLM) 生成看似合理但与图像不符的文本，已成为 MLLM 应用的一大难题。现有基准通过提出关于对象存在的区分性问题或引入 LLM 评估器对生成的文本进行评分来衡量幻觉水平。然而，这些基准的区分性数据过于简单，与现实世界文本不符，而生成性数据则因计算密集且不稳定而受限。为此，我们推出了 LongHalQA，一个无需 LLM 的幻觉基准，包含 6K 个长且复杂的幻觉文本。LongHalQA 的幻觉数据由 GPT4V 生成，与现实世界场景高度一致，涵盖对象描述、图像描述及多轮对话，平均字数分别为 14/130 和 189 字。该基准引入了幻觉区分和幻觉补全两个新任务，将区分性和生成性评估整合为单一的多项选择题形式，实现更可靠高效的评估，无需 LLM 评估器。此外，我们还提出了一种先进的管道，极大简化了未来幻觉基准的建设。对多个最新 MLLM 的广泛实验显示，它们在处理长且复杂的文本数据时面临诸多新挑战。数据集和评估代码已公开，详见 https://github.com/hanqiu-hq/LongHalQA。

> Hallucination, a phenomenon where multimodal large language models~(MLLMs) tend to generate textual responses that are plausible but unaligned with the image, has become one major hurdle in various MLLM-related applications. Several benchmarks have been created to gauge the hallucination levels of MLLMs, by either raising discriminative questions about the existence of objects or introducing LLM evaluators to score the generated text from MLLMs. However, the discriminative data largely involve simple questions that are not aligned with real-world text, while the generative data involve LLM evaluators that are computationally intensive and unstable due to their inherent randomness. We propose LongHalQA, an LLM-free hallucination benchmark that comprises 6K long and complex hallucination text. LongHalQA is featured by GPT4V-generated hallucinatory data that are well aligned with real-world scenarios, including object/image descriptions and multi-round conversations with 14/130 words and 189 words, respectively, on average. It introduces two new tasks, hallucination discrimination and hallucination completion, unifying both discriminative and generative evaluations in a single multiple-choice-question form and leading to more reliable and efficient evaluations without the need for LLM evaluators. Further, we propose an advanced pipeline that greatly facilitates the construction of future hallucination benchmarks with long and complex questions and descriptions. Extensive experiments over multiple recent MLLMs reveal various new challenges when they are handling hallucinations with long and complex textual data. Dataset and evaluation code are available at https://github.com/hanqiu-hq/LongHalQA.

[Arxiv](https://arxiv.org/abs/2410.09962)