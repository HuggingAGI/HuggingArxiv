# 越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。

发布时间：2024年03月31日

`LLM理论` `资源优化`

> The Larger the Better? Improved LLM Code-Generation via Budget Reallocation

# 摘要

> 大家普遍认为，大型语言模型的性能超越了小型模型。但大模型在推理时也消耗更多的时间和计算资源。那么，在同等资源限制下，两者的表现如何？我们通过比较不同规模的代码生成模型，例如运行一次70B模型与运行13B模型五次并挑选最佳结果，来探讨这一问题。研究发现，在标准的单元测试环境中，多次运用小型模型能带来显著提升，五个任务的准确率提高了最多15%。然而，在缺乏单元测试的情况下，通过排名筛选小型模型的结果，其性能仍不及大型模型的单一输出。这一研究结果强调了小型模型的潜力，并指出了研究LLM输出排名方法的重要性。

> It is a common belief that large language models (LLMs) are better than smaller-sized ones. However, larger models also require significantly more time and compute during inference. This begs the question: what happens when both models operate under the same budget? (e.g., compute, run-time). To address this question, we analyze code generation LLMs of various sizes and make comparisons such as running a 70B model once vs. generating five outputs from a 13B model and selecting one. Our findings reveal that, in a standard unit-test setup, the repeated use of smaller models can yield consistent improvements, with gains of up to 15% across five tasks. On the other hand, in scenarios where unit-tests are unavailable, a ranking-based selection of candidates from the smaller model falls short of the performance of a single output from larger ones. Our results highlight the potential of using smaller models instead of larger ones, and the importance of studying approaches for ranking LLM outputs.

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x1.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x2.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x3.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x4.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x5.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x6.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x7.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x8.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x9.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x10.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x11.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x12.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x13.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x14.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x15.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x16.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x17.png)

![越大越好？通过合理分配资源，优化大型语言模型的代码生成能力。](../../../paper_images/2404.00725/x18.png)

[Arxiv](https://arxiv.org/abs/2404.00725)