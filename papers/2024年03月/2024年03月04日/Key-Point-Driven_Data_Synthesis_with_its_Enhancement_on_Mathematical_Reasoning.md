# [通过关键点驱动的数据合成技术，并对其进行优化，以提升数学推理性能。这项研究聚焦于利用关键点引导的数据合成方法，有效增强模型在数学推理任务上的表现。](https://arxiv.org/abs/2403.02333)

发布时间：2024年03月04日

`LLM应用`

> Key-Point-Driven Data Synthesis with its Enhancement on Mathematical Reasoning

> 面对高质量推理训练数据集匮乏阻碍LLMs在复杂推理任务中发挥实力的问题，我们创新提出了关键点驱动数据合成方法(KPDDS)，它能借助真实数据源的关键信息与实例对高效合成问题-答案配对。KPDDS有力保障了新问题的质量把控及规模化生产，由此催生出迄今规模最大、专为数学推理定制的合成数据集KPMath，内含百万级的问题-答案对。在此基础上，我们融合更多深度推理内容，打造了综合性更强的KPMath-Plus数据集。当将Mistral-7B模型在KPMath-Plus上进行微调后，其在MATH测试集上的零样本PASS@1准确率达到39.3%，这一成绩不仅优于同类已微调的7B模型，甚至比肩部分34B模型。此外，我们的消融实验还揭示了LLMs在多种数学推理子领域的显著增强效果，标志着LLMs推理能力取得重大突破。

> Large language models (LLMs) have shown great potential in complex reasoning tasks, yet their performance is often hampered by the scarcity of high-quality, reasoning-focused training datasets. Addressing this challenge, we propose Key-Point-Driven Data Synthesis (KPDDS), a novel data synthesis framework that synthesizes question-answer pairs by leveraging key points and exemplar pairs from authentic data sources. KPDDS ensures the generation of novel questions with rigorous quality control and substantial scalability. As a result, we present KPMath, the most extensive synthetic dataset tailored for mathematical reasoning to date, comprising over one million question-answer pairs. Utilizing KPMath and augmenting it with additional reasoning-intensive corpora, we create the comprehensive KPMath-Plus dataset. Fine-tuning the Mistral-7B model on KPMath-Plus yields a zero-shot PASS@1 accuracy of 39.3% on the MATH test set, a performance that not only outpaces other finetuned 7B models but also exceeds that of certain 34B models. Our ablation studies further confirm the substantial enhancement in mathematical reasoning across various subtopics, marking a significant stride in LLMs' reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2403.02333)