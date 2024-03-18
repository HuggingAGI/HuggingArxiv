# [AutoLoRA 是一种创新方法，它运用元学习技术，在低秩适应过程中自动化地优化矩阵的秩。这项研究旨在解决在模型适应时对矩阵秩高效且智能调节的问题。](https://arxiv.org/abs/2403.09113)

发布时间：2024年03月14日

`LLM应用` `` `模型压缩`

> AutoLoRA: Automatically Tuning Matrix Ranks in Low-Rank Adaptation Based on Meta Learning

> 大规模预训练加任务特定微调策略在各类NLP任务中表现出色，但全量微调大模型参数时面临的计算和存储难题不容忽视。为此，人们开发了诸如LoRA这样的高效微调技术，它在预训练权重冻结的基础上仅对低秩增量更新矩阵进行微调。尽管如此，LoRA因在所有层级统一分配秩且依赖于耗时的穷举搜索寻找最优秩，从而带来了高昂计算成本及微调效果欠佳的问题。为此，我们创新性地提出AutoLoRA，这是一个基于元学习的框架，能自动识别每个LoRA层的最佳秩配置。AutoLoRA巧妙地为低秩更新矩阵中的每个秩-1矩阵关联一个选择变量，以判断是否剔除该矩阵。借助元学习方法学习这些选择变量，并通过设定阈值确定最优秩。我们在广泛的自然语言理解、生成及序列标注任务上进行了深入实验，充分证明了AutoLoRA的有效性和优越性。

> Large-scale pretraining followed by task-specific finetuning has achieved great success in various NLP tasks. Since finetuning all parameters of large pretrained models poses substantial computational and memory challenges, several efficient finetuning methods have been developed. Among them, low-rank adaptation (LoRA), which finetunes low-rank incremental update matrices on top of frozen pretrained weights, has proven particularly effective. Nonetheless, LoRA's uniform rank assignment across all layers, along with its reliance on an exhaustive search to find the best rank, leads to high computation costs and suboptimal finetuning performance. To address these limitations, we introduce AutoLoRA, a meta learning based framework for automatically identifying the optimal rank of each LoRA layer. AutoLoRA associates each rank-1 matrix in a low-rank update matrix with a selection variable, which determines whether the rank-1 matrix should be discarded. A meta learning based method is developed to learn these selection variables. The optimal rank is determined by thresholding the values of these variables. Our comprehensive experiments on natural language understanding, generation, and sequence labeling demonstrate the effectiveness of AutoLoRA.

![AutoLoRA 是一种创新方法，它运用元学习技术，在低秩适应过程中自动化地优化矩阵的秩。这项研究旨在解决在模型适应时对矩阵秩高效且智能调节的问题。](../../../paper_images/2403.09113/x1.png)

![AutoLoRA 是一种创新方法，它运用元学习技术，在低秩适应过程中自动化地优化矩阵的秩。这项研究旨在解决在模型适应时对矩阵秩高效且智能调节的问题。](../../../paper_images/2403.09113/large.png)

![AutoLoRA 是一种创新方法，它运用元学习技术，在低秩适应过程中自动化地优化矩阵的秩。这项研究旨在解决在模型适应时对矩阵秩高效且智能调节的问题。](../../../paper_images/2403.09113/rank.png)

[Arxiv](https://arxiv.org/abs/2403.09113)