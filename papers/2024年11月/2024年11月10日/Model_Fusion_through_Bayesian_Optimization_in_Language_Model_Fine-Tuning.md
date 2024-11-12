# 通过贝叶斯优化在语言模型微调中的模型融合

发布时间：2024年11月10日

`LLM应用` `预训练模型` `贝叶斯优化`

> Model Fusion through Bayesian Optimization in Language Model Fine-Tuning

# 摘要

> 对下游任务的预训练模型进行微调是一种被广泛采用的技术，因其在各个领域的适应性和可靠性而闻名。尽管其概念简单，但微调需要做出一些麻烦的工程选择，例如选择超参数和从优化轨迹确定检查点。为了解决选择最佳模型的困难，一种有效的解决方案是模型融合，它在参数空间中组合多个模型。然而，我们观察到在预训练语言模型的微调期间，损失和指标景观之间存在很大差异。基于这一观察，我们引入了一种新颖的模型融合技术，通过多目标贝叶斯优化同时优化所需的指标和损失。此外，为了有效地选择超参数，我们通过将贝叶斯优化过程集成到我们的框架中建立了一个两阶段的程序。在各种下游任务中的实验表明，使用我们的贝叶斯优化引导方法性能有了相当大的提升。

> Fine-tuning pre-trained models for downstream tasks is a widely adopted technique known for its adaptability and reliability across various domains. Despite its conceptual simplicity, fine-tuning entails several troublesome engineering choices, such as selecting hyperparameters and determining checkpoints from an optimization trajectory. To tackle the difficulty of choosing the best model, one effective solution is model fusion, which combines multiple models in a parameter space. However, we observe a large discrepancy between loss and metric landscapes during the fine-tuning of pre-trained language models. Building on this observation, we introduce a novel model fusion technique that optimizes both the desired metric and loss through multi-objective Bayesian optimization. In addition, to effectively select hyperparameters, we establish a two-stage procedure by integrating Bayesian optimization processes into our framework. Experiments across various downstream tasks show considerable performance improvements using our Bayesian optimization-guided method.

[Arxiv](https://arxiv.org/abs/2411.06710)