# 变化是唯一的常量：基于层冗余的动态 LLM 切片

发布时间：2024年11月05日

`LLM应用` `模型压缩`

> Change Is the Only Constant: Dynamic LLM Slicing based on Layer Redundancy

# 摘要

> 这篇论文通过在大型语言模型（LLMs）中的动态特定层剪枝引入了一种新颖的模型压缩方法，改进了由 SliceGPT 建立的传统方法。通过从恒定切片转变为动态切片，我们的方法利用了新提出的层冗余（LR）分数，该分数通过测量层的输入与输出的余弦相似度来评估每一层对其输入的改变程度。我们使用这个分数根据冗余来剪枝各个层的部分，使得所有层的平均剪枝百分比为一个固定值。我们使用像 Llama3-8B 和 Mistral-7B 这样的模型在多个数据集上进行了广泛的实验，评估了不同的切片基础和百分比，以确定平衡效率和性能的最佳配置。我们的研究结果表明，与由恒定切片方法建立的基线相比，我们的动态切片方法不仅保持而且在许多情况下提高了模型性能。例如，在几种设置中，我们看到性能比 SliceGPT 基线提高了多达 5％。此外，在多个基准测试中观察到困惑度降低多达 7％，验证了我们方法的有效性。代码、模型权重和数据集在 https://github.com/RazvanDu/DynamicSlicing 开源。

> This paper introduces a novel model compression approach through dynamic layer-specific pruning in Large Language Models (LLMs), enhancing the traditional methodology established by SliceGPT. By transitioning from constant to dynamic slicing, our method leverages the newly proposed Layer Redundancy (LR) score, which assesses how much change each layer changes its input by measuring the cosine similarity of the input to the output of the layer. We use this score to prune parts of individual layers based on redundancy in such a way that the average pruned percentage for all layers is a fixed value. We conducted extensive experiments using models like Llama3-8B and Mistral-7B on multiple datasets, evaluating different slicing bases and percentages to determine optimal configurations that balance efficiency and performance. Our findings show that our dynamic slicing approach not only maintains but, in many cases, enhances model performance compared to the baseline established by constant slicing methods. For instance, in several settings, we see performance improvements of up to 5% over the SliceGPT baseline. Additionally, a perplexity decrease by as much as 7% was observed across multiple benchmarks, validating the effectiveness of our method. The code, model weights, and datasets are open-sourced at https://github.com/RazvanDu/DynamicSlicing.

[Arxiv](https://arxiv.org/abs/2411.03513)