# 预训练中，关键批量大小是如何缩放的？

发布时间：2024年10月28日

`LLM理论` `模型训练`

> How Does Critical Batch Size Scale in Pre-training?

# 摘要

> 在给定资源的情况下训练大规模模型，得精心设计并行策略。尤其是，关键批量大小这一效率概念，涉及时间与计算的权衡，它标志着超过某个阈值后，更多的数据并行会导致收益递减。为落实这一点，我们提出了 CBS 的衡量标准，并在 C4 数据集上对从 8500 万到 12 亿参数的一系列自回归语言模型进行了预训练。通过大量的超参数扫描，以及对批量大小、动量、学习率及其调度等因素的精细把控，我们系统探究了规模对 CBS 的影响。接着，我们依据模型和数据大小拟合缩放定律，以分离它们的作用。总之，我们的结果表明，CBS 主要随数据大小而非模型大小缩放，这一发现我们通过对神经网络的无限宽度限制和无限维最小二乘回归的分析从理论上加以了论证。另外，我们突出了常见超参数的选择以及策略对于研究超出固定训练时长的大规模预训练的重要性。

> Training large-scale models under given resources requires careful design of parallelism strategies. In particular, the efficiency notion of critical batch size, concerning the compromise between time and compute, marks the threshold beyond which greater data parallelism leads to diminishing returns. To operationalize it, we propose a measure of CBS and pre-train a series of auto-regressive language models, ranging from 85 million to 1.2 billion parameters, on the C4 dataset. Through extensive hyper-parameter sweeps and careful control on factors such as batch size, momentum, and learning rate along with its scheduling, we systematically investigate the impact of scale on CBS. Then we fit scaling laws with respect to model and data sizes to decouple their effects. Overall, our results demonstrate that CBS scales primarily with data size rather than model size, a finding we justify theoretically through the analysis of infinite-width limits of neural networks and infinite-dimensional least squares regression. Of independent interest, we highlight the importance of common hyper-parameter choices and strategies for studying large-scale pre-training beyond fixed training durations.

[Arxiv](https://arxiv.org/abs/2410.21676)