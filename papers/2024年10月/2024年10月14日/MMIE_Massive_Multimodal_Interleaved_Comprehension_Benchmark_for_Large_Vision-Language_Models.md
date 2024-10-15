# MMIE：大型视觉-语言模型的大规模多模态交错理解基准

发布时间：2024年10月14日

`LLM应用` `人工智能` `计算机视觉`

> MMIE: Massive Multimodal Interleaved Comprehension Benchmark for Large Vision-Language Models

# 摘要

> 交错多模态理解和生成已成为多模态学习的核心领域，但现有评估方法仍显不足。为此，我们推出了MMIE，一个大规模知识密集型基准，专为评估大型视觉语言模型（LVLMs）而设计。MMIE包含20K多模态查询，涵盖广泛领域，支持交错输入输出，并提供多样化的评估格式。我们还提出了一种可靠的自动化评估指标，旨在提升评估的准确性和公正性。实验表明，MMIE能全面评估LVLMs，揭示了现有模型的改进空间。我们已在https://mmie-bench.github.io/公开发布基准和代码，期待推动LVLMs的进一步发展。

> Interleaved multimodal comprehension and generation, enabling models to produce and interpret both images and text in arbitrary sequences, have become a pivotal area in multimodal learning. Despite significant advancements, the evaluation of this capability remains insufficient. Existing benchmarks suffer from limitations in data scale, scope, and evaluation depth, while current evaluation metrics are often costly or biased, lacking in reliability for practical applications. To address these challenges, we introduce MMIE, a large-scale knowledge-intensive benchmark for evaluating interleaved multimodal comprehension and generation in Large Vision-Language Models (LVLMs). MMIE comprises 20K meticulously curated multimodal queries, spanning 3 categories, 12 fields, and 102 subfields, including mathematics, coding, physics, literature, health, and arts. It supports both interleaved inputs and outputs, offering a mix of multiple-choice and open-ended question formats to evaluate diverse competencies. Moreover, we propose a reliable automated evaluation metric, leveraging a scoring model fine-tuned with human-annotated data and systematic evaluation criteria, aimed at reducing bias and improving evaluation accuracy. Extensive experiments demonstrate the effectiveness of our benchmark and metrics in providing a comprehensive evaluation of interleaved LVLMs. Specifically, we evaluate eight LVLMs, revealing that even the best models show significant room for improvement, with most achieving only moderate results. We believe MMIE will drive further advancements in the development of interleaved LVLMs. We publicly release our benchmark and code in https://mmie-bench.github.io/.

[Arxiv](https://arxiv.org/abs/2410.10139)