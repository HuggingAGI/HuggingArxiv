# Tangram：几何元素识别的挑战性标杆

发布时间：2024年08月25日

`LLM应用` `人工智能`

> Tangram: A Challenging Benchmark for Geometric Element Recognizing

# 摘要

> 大型多模态模型（LMMs）在视觉-数学推理方面取得了显著进步，但它们在几何元素识别方面的能力尚未得到充分探索。为此，我们推出了Tangram基准，专门评估LMMs在几何元素识别上的表现。Tangram包含1,080个多样化的几何图表，源自中小学考试、竞赛及教科书，从基础形状到复杂组合应有尽有，每个图表附带四个问题，总计4,320个视觉-问题-答案对。不同于追求高阶认知的基准，Tangram侧重于几何元素的基础理解，要求模型完成看似简单却颇具趣味的计数任务。对包括GPT-4o和Claude 3.5 Sonnet在内的10个知名LMMs的评估表明，即便在简单任务中，这些模型也面临挑战，最佳模型的整体准确率仅为56.8%，远低于人类水平。这些结果揭示了当前多模态AI在基础感知任务上的局限，预示着新一代专家级多模态基础模型的发展方向。Tangram及其评估代码即将发布。

> Significant advancements in Large Multimodal Models (LMMs) have enabled them to tackle complex problems involving visual-mathematical reasoning. However, their ability to identify geometric elements remains understudied. To bridge this gap, we introduce Tangram, a novel benchmark designed to evaluate the performance of LMMs on geometric element recognition. Tangram includes 1,080 diverse geometric diagrams sourced from primary and secondary school exams, competitions, and textbooks, covering from simple basic geometric shapes to complex combinations. Each diagram is associated with four questions, resulting in a total of 4,320 visual-question-answer pairs. Unlike existing benchmarks that seek higher-level cognition and reasoning, Tangram focuses on the understanding of geometric elements, requiring models to perform a "simple but interesting" counting task. Systematic evaluation of 10 prominent LMMs, such as GPT-4o and Claude 3.5 Sonnet, shows that even in the seemingly simple task, these models still face significant challenges. Notably, the overall accuracy of the top performer across all tested models is only 56.8%, marking a significant gap when compared to human performance. These findings highlight the limitations of current multimodal artificial intelligence systems in handling basic perception tasks, and will inspire the development of the next generation of expert-level multimodal foundational models. The Tangram and evaluation code will be available soon.

[Arxiv](https://arxiv.org/abs/2408.13854)