# MMIE：专为大型视觉-语言模型设计的大规模多模态交错理解基准

发布时间：2024年10月14日

`LLM应用` `人工智能`

> MMIE: Massive Multimodal Interleaved Comprehension Benchmark for Large Vision-Language Models

# 摘要

> 交错多模态理解和生成，即模型能以任意顺序处理图像和文本，已成为多模态学习的核心。尽管技术进步显著，但评估体系仍显不足。现有基准在数据规模、广度和深度上存在局限，评估指标也常因成本高或偏见多而不够可靠。为此，我们推出了MMIE，一个大规模知识密集型基准，专为评估大型视觉语言模型（LVLMs）中的交错多模态能力。MMIE包含20K精心设计的多模态查询，覆盖数学、编码、物理、文学、健康和艺术等3大类、12领域、102子领域。它支持交错输入输出，采用多选和开放式问题混合，全面评估模型能力。我们还提出了一个基于人类标注数据微调的评分模型，旨在减少偏见，提高评估准确性。实验表明，MMIE能有效评估LVLMs，揭示了即使是顶尖模型也有巨大提升空间。我们相信MMIE将推动该领域的发展，并在https://mmie-bench.github.io/公开了基准和代码。

> Interleaved multimodal comprehension and generation, enabling models to produce and interpret both images and text in arbitrary sequences, have become a pivotal area in multimodal learning. Despite significant advancements, the evaluation of this capability remains insufficient. Existing benchmarks suffer from limitations in data scale, scope, and evaluation depth, while current evaluation metrics are often costly or biased, lacking in reliability for practical applications. To address these challenges, we introduce MMIE, a large-scale knowledge-intensive benchmark for evaluating interleaved multimodal comprehension and generation in Large Vision-Language Models (LVLMs). MMIE comprises 20K meticulously curated multimodal queries, spanning 3 categories, 12 fields, and 102 subfields, including mathematics, coding, physics, literature, health, and arts. It supports both interleaved inputs and outputs, offering a mix of multiple-choice and open-ended question formats to evaluate diverse competencies. Moreover, we propose a reliable automated evaluation metric, leveraging a scoring model fine-tuned with human-annotated data and systematic evaluation criteria, aimed at reducing bias and improving evaluation accuracy. Extensive experiments demonstrate the effectiveness of our benchmark and metrics in providing a comprehensive evaluation of interleaved LVLMs. Specifically, we evaluate eight LVLMs, revealing that even the best models show significant room for improvement, with most achieving only moderate results. We believe MMIE will drive further advancements in the development of interleaved LVLMs. We publicly release our benchmark and code in https://mmie-bench.github.io/.

[Arxiv](https://arxiv.org/abs/2410.10139)