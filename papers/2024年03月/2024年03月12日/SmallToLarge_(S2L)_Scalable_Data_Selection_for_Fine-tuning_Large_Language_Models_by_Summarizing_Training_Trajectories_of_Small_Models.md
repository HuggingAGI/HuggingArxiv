# [S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](https://arxiv.org/abs/2403.07384)

发布时间：2024年03月12日

`LLM应用`

> SmallToLarge (S2L): Scalable Data Selection for Fine-tuning Large Language Models by Summarizing Training Trajectories of Small Models

> 面对LLMs在预训练和指令微调时对数据选择的依赖，提升特定领域SFT阶段的数据利用率却因微调数据的复杂性而困难重重。为此，我们创新提出了一种适用于SFT的有效且易拓展的数据筛选方法——SmallToLarge（S2L）。该方法巧妙利用小型模型的训练路径指导大型模型挑选数据。大量实验证明，S2L在数学问题求解任务中大幅提高了SFT阶段的数据效率，仅用原MathInstruct数据集（Yue等人，2023）的11%数据，就实现了与全量数据媲美的性能表现，而且在6项内外部评估数据集中，平均超出当前最先进数据筛选算法4.7%的成绩。尤其引人注目的是，当用于SFT的数据仅为5万条时，S2L在极具挑战性的MATH基准测试（Hendrycks等人，2021）上取得了高达32.7%的精确度，较Phi-2（Li等人，2023b）提升了16.6%。此外，在MIMIC-III临床文本摘要数据集（Johnson等人，2016）上，S2L同样凭借50%的数据量就超过了全数据集训练的结果。更值得一提的是，S2L能够借助大小仅为目标模型1/40的参照模型进行数据筛选，从而大幅度降低数据筛选的成本。

> Despite the effectiveness of data selection for large language models (LLMs) during pretraining and instruction fine-tuning phases, improving data efficiency in supervised fine-tuning (SFT) for specialized domains poses significant challenges due to the complexity of fine-tuning data. To bridge this gap, we introduce an effective and scalable data selection method for SFT, SmallToLarge (S2L), which leverages training trajectories from small models to guide the data selection for larger models. We demonstrate through extensive experiments that S2L significantly improves data efficiency in SFT for mathematical problem-solving, reducing the training data to just 11% of the original MathInstruct dataset (Yue et al., 2023) to match full dataset performance while outperforming state-of-the-art data selection algorithms by an average of 4.7% across 6 in- and out-domain evaluation datasets. Remarkably, selecting only 50K data for SFT, S2L achieves a 32.7% accuracy on the most challenging MATH (Hendrycks et al., 2021) benchmark, improving Phi-2 (Li et al., 2023b) by 16.6%. In clinical text summarization on the MIMIC-III dataset (Johnson et al., 2016), S2L again outperforms training on the full dataset using only 50% of the data. Notably, S2L can perform data selection using a reference model 40x smaller than the target model, proportionally reducing the cost of data selection.

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x1.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x2.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x3.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x4.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x5.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x6.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x7.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x9.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x10.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x11.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x12.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x13.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x14.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x15.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x16.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x19.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x20.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x21.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x22.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x23.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x24.png)

![S2L 方法通过提炼小型模型训练历程，为大型语言模型的精细化微调提供可扩展的数据筛选方案。](../../../paper_images/2403.07384/x25.png)