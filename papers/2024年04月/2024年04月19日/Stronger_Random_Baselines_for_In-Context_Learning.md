# 为上下文内学习构建更强大的随机基线

发布时间：2024年04月19日

`分类：LLM理论` `机器学习`

> Stronger Random Baselines for In-Context Learning

# 摘要

> 评估语言模型的上下文学习分类效果面临诸多挑战，包括数据集规模有限、验证集的广泛提示选择以及设计上的困难任务，这些因素可能导致性能接近随机水平。在评估集仅使用一次或数据集较大的情况下，标准随机基线——即随机猜测标签的预期准确率——保持稳定。针对验证集的重复使用和现有小数据集的实际情况，我们提出了一个更严格的随机基线：在多个随机分类器中预期的最大准确率。在对六个量化语言模型进行16个BIG-bench Lite任务的提示演示选择时，超过20%的少数镜头结果虽然超过了标准基线，但并未达到这一更严格的随机基线。当存在独立的测试集时，这一更严格的基线也是预测测试性能的更佳指标，从而避免了不必要的测试集评估。这个最大随机基线为标准基线提供了一个简单易行的替代方案。

> Evaluating the in-context learning classification performance of language models poses challenges due to small dataset sizes, extensive prompt-selection using the validation set, and intentionally difficult tasks that lead to near-random performance. The standard random baseline -- the expected accuracy of guessing labels uniformly at random -- is stable when the evaluation set is used only once or when the dataset is large. We account for the common practice of validation set reuse and existing small datasets with a stronger random baseline: the expected maximum accuracy across multiple random classifiers. When choosing the best prompt demonstrations across six quantized language models applied to 16 BIG-bench Lite tasks, more than 20\% of the few-shot results that exceed the standard baseline do not exceed this stronger random baseline. When held-out test sets are available, this stronger baseline is also a better predictor of held-out performance than the standard baseline, avoiding unnecessary test set evaluations. This maximum random baseline provides an easily calculated drop-in replacement for the standard baseline.

[Arxiv](https://arxiv.org/abs/2404.13020)