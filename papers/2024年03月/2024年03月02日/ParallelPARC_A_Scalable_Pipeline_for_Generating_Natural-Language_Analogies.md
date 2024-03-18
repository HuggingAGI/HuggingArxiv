# ParallelPARC，一款专为高效生成自然语言类比而设计的可扩展式处理流程

发布时间：2024年03月02日

`LLM应用`

> ParallelPARC: A Scalable Pipeline for Generating Natural-Language Analogies

> 类比思维是人类认知的核心，帮助我们应对新奇场景，而现有的AI系统尚未完全掌握这一能力。现今多数类比数据集专注于基础的词语类比，涉及复杂类比的数据集因多依赖人工整理，往往规模较小，这在一定程度上限制了计算类比的进步。本研究中，我们创新设计了一种名为ParallelPARC的数据生成流水线，借助尖端大型语言模型(LLMs)生成基于段落的复杂类比及各种难度级别的干扰项。我们展示了这一流水线的实际应用，并构建出一个名为ProPara-Logy的科学过程间类比数据集，其中包含了经人工验证的金标准集和自动生产的银标准集。通过在二选一和多选模式下对LLMs和人类进行类比识别能力的测试，我们发现，在轻度指导之后，人类的表现明显优于最优模型（差距约为13%）。同时，实验表明，银标准集对模型训练极具价值。另外，我们揭示了具有一定挑战性的干扰项会误导LLMs，但并不会困扰人类。我们期待这项研究提出的流水线能激发更多在这个新兴领域内的探索与研究。

> Analogy-making is central to human cognition, allowing us to adapt to novel situations -- an ability that current AI systems still lack. Most analogy datasets today focus on simple analogies (e.g., word analogies); datasets including complex types of analogies are typically manually curated and very small. We believe that this holds back progress in computational analogy. In this work, we design a data generation pipeline, ParallelPARC (Parallel Paragraph Creator) leveraging state-of-the-art Large Language Models (LLMs) to create complex, paragraph-based analogies, as well as distractors, both simple and challenging. We demonstrate our pipeline and create ProPara-Logy, a dataset of analogies between scientific processes. We publish a gold-set, validated by humans, and a silver-set, generated automatically. We test LLMs' and humans' analogy recognition in binary and multiple-choice settings, and found that humans outperform the best models (~13% gap) after a light supervision. We demonstrate that our silver-set is useful for training models. Lastly, we show challenging distractors confuse LLMs, but not humans. We hope our pipeline will encourage research in this emerging field.

[Arxiv](https://arxiv.org/abs/2403.01139)