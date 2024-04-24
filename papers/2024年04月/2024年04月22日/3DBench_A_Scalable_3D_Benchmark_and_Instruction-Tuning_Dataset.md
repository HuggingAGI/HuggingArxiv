# 3DBench：一个可扩展的三维基准测试及指令微调数据集

发布时间：2024年04月22日

`LLM应用` `人工智能` `计算机视觉`

> 3DBench: A Scalable 3D Benchmark and Instruction-Tuning Dataset

# 摘要

> 对融合点云与语言的多模态大型语言模型（MLLMs）进行性能评估，面临着显著挑战。目前缺乏全面评估手段，这不仅限制了我们对模型进步性的认识，也制约了该领域的进步。现行的评估方法多侧重于分类和字幕任务，未能充分考量MLLMs的空间理解与表达能力。因此，开发一种能够深入分析这些能力的高级评估方法显得尤为迫切。为应对这些挑战，我们推出了一个可扩展的3D基准测试平台——3DBench，它配备了大规模的指令调优数据集，为MLLMs的全面评估提供了坚实基础。该基准测试覆盖了从个体到场景的多个空间和语义层次，同时涉及感知与规划任务。此外，我们还构建了一个自动化流程，用于创建可扩展的3D指令调优数据集，涵盖了10种多样的多模态任务，共生成了超过23万个问答对。通过一系列深入的实验，我们评估了当前流行的MLLMs，与现有数据集进行了比较，并探索了不同的训练协议，从而证明了3DBench的优越性，并为当前的局限性和未来研究方向提供了深刻见解。

> Evaluating the performance of Multi-modal Large Language Models (MLLMs), integrating both point cloud and language, presents significant challenges. The lack of a comprehensive assessment hampers determining whether these models truly represent advancements, thereby impeding further progress in the field. Current evaluations heavily rely on classification and caption tasks, falling short in providing a thorough assessment of MLLMs. A pressing need exists for a more sophisticated evaluation method capable of thoroughly analyzing the spatial understanding and expressive capabilities of these models. To address these issues, we introduce a scalable 3D benchmark, accompanied by a large-scale instruction-tuning dataset known as 3DBench, providing an extensible platform for a comprehensive evaluation of MLLMs. Specifically, we establish the benchmark that spans a wide range of spatial and semantic scales, from object-level to scene-level, addressing both perception and planning tasks. Furthermore, we present a rigorous pipeline for automatically constructing scalable 3D instruction-tuning datasets, covering 10 diverse multi-modal tasks with more than 0.23 million QA pairs generated in total. Thorough experiments evaluating trending MLLMs, comparisons against existing datasets, and variations of training protocols demonstrate the superiority of 3DBench, offering valuable insights into current limitations and potential research directions.

[Arxiv](https://arxiv.org/abs/2404.14678)