# 关于大型语言模型的微调之转移学习

发布时间：2024年11月02日

`LLM应用` `语言模型` `迁移学习`

> Transfer Learning for Finetuning Large Language Models

# 摘要

> 随着大型语言模型的版图不断拓展，针对特定任务进行高效微调愈发关键。与此同时，参数高效微调方法的版图也在迅速扩张。于是，从业者在为大型语言模型寻觅最优微调流程时，面临着诸多繁杂的抉择。为给从业者减负，我们探究了大型语言模型微调的迁移学习，旨在将相关微调任务中的配置知识迁移至新任务。在此次工作中，我们借助元学习性能和新元数据集的灰箱元优化成本代理模型来开展微调的迁移学习。出人意料的是，我们主张仅依靠新数据集的迁移学习。所以，我们不采用特定任务的贝叶斯优化，而是更看重从相关任务转移来的知识，而非特定任务的反馈。我们在八个合成问答数据集以及一个由 1800 次微软 Phi-3 微调运行构成的元数据集上对我们的方法进行了评估。我们的迁移学习优于零样本、默认微调以及元优化基线。我们的成果证明了微调的可迁移性，能更有效地适配大型语言模型。

> As the landscape of large language models expands, efficiently finetuning for specific tasks becomes increasingly crucial. At the same time, the landscape of parameter-efficient finetuning methods rapidly expands. Consequently, practitioners face a multitude of complex choices when searching for an optimal finetuning pipeline for large language models. To reduce the complexity for practitioners, we investigate transfer learning for finetuning large language models and aim to transfer knowledge about configurations from related finetuning tasks to a new task. In this work, we transfer learn finetuning by meta-learning performance and cost surrogate models for grey-box meta-optimization from a new meta-dataset. Counter-intuitively, we propose to rely only on transfer learning for new datasets. Thus, we do not use task-specific Bayesian optimization but prioritize knowledge transferred from related tasks over task-specific feedback. We evaluate our method on eight synthetic question-answer datasets and a meta-dataset consisting of 1,800 runs of finetuning Microsoft's Phi-3. Our transfer learning is superior to zero-shot, default finetuning, and meta-optimization baselines. Our results demonstrate the transferability of finetuning to adapt large language models more effectively.

[Arxiv](https://arxiv.org/abs/2411.01195)