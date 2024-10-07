# 结构增强的蛋白质指令调优：探索通用蛋白质理解的奥秘

发布时间：2024年10月04日

`LLM应用` `生物技术` `蛋白质研究`

> Structure-Enhanced Protein Instruction Tuning: Towards General-Purpose Protein Understanding

# 摘要

> 蛋白质作为生物过程中的关键分子，其性质和功能的准确预测至关重要。尽管通过监督微调的蛋白质语言模型（pLMs）提供了有前景的解决方案，但实现通用蛋白质理解仍具挑战。为此，我们提出了结构增强的蛋白质指令微调（SEPIT）框架，通过集成结构感知模块和连接大型语言模型（LLMs），增强对蛋白质的理解。我们设计了两阶段指令微调流程，先通过标题指令建立基础理解，再利用专家混合（MoEs）深化复杂性质和功能的学习。此外，我们构建了最大最全面的蛋白质指令数据集，用于训练和评估通用模型。实验结果显示，SEPIT在开放式生成和封闭集回答任务中，均优于现有模型。

> Proteins, as essential biomolecules, play a central role in biological processes, including metabolic reactions and DNA replication. Accurate prediction of their properties and functions is crucial in biological applications. Recent development of protein language models (pLMs) with supervised fine tuning provides a promising solution to this problem. However, the fine-tuned model is tailored for particular downstream prediction task, and achieving general-purpose protein understanding remains a challenge. In this paper, we introduce Structure-Enhanced Protein Instruction Tuning (SEPIT) framework to bridge this gap. Our approach integrates a noval structure-aware module into pLMs to inform them with structural knowledge, and then connects these enhanced pLMs to large language models (LLMs) to generate understanding of proteins. In this framework, we propose a novel two-stage instruction tuning pipeline that first establishes a basic understanding of proteins through caption-based instructions and then refines this understanding using a mixture of experts (MoEs) to learn more complex properties and functional information with the same amount of activated parameters. Moreover, we construct the largest and most comprehensive protein instruction dataset to date, which allows us to train and evaluate the general-purpose protein understanding model. Extensive experimental results on open-ended generation and closed-set answer tasks demonstrate the superior performance of SEPIT over both closed-source general LLMs and open-source LLMs trained with protein knowledge.

[Arxiv](https://arxiv.org/abs/2410.03553)