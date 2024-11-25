# 一个用于化学设计与性质预测的基础模型

发布时间：2024年10月28日

`LLM应用` `人工智能`

> A Foundation Model for Chemical Design and Property Prediction

# 摘要

> 人工智能（AI）显著推动了计算化学研究的进程。然而，传统的 AI 方法往往依赖针对特定任务的模型设计与训练，这既制约了模型规模的可扩展性，又限制了其在不同任务中的通用性。在此，我们推出 ChemFM，这是一个专为化学领域打造的大规模基础模型，参数多达 30 亿。ChemFM 借助自监督因果语言模型，在 1.78 亿个分子上进行预训练，以获取可通用的分子表征。该模型能够通过全参数和高效参数微调的方式，适配各类下游化学应用。ChemFM 在多项化学任务中的表现始终优于前沿方法。尤为值得一提的是，它在 34 个性质预测基准中，性能提升高达 67.48%；在条件分子生成任务里，生成分子的条件属性与实际属性间的平均偏差降低幅度高达 33.31%；在 4 个反应预测数据集中，top-1 准确率提升高达 3.7%。此外，ChemFM 在预测抗生素活性和细胞毒性方面表现卓越，凸显了其在助力新型抗生素发现方面的潜力。我们预期，ChemFM 会通过提供一个能在众多任务中有效通用且只需少量额外训练的基础模型，有力地推动化学研究的发展。

> Artificial intelligence (AI) has significantly advanced computational chemistry research. However, traditional AI methods often rely on task-specific model designs and training, which constrain both the scalability of model size and generalization across different tasks. Here, we introduce ChemFM, a large-scale foundation model specifically developed for chemistry, comprising up to 3 billion parameters. ChemFM is pre-trained on 178 million molecules using self-supervised causal language modeling to extract generalizable molecular representations. This model can be adapted to diverse downstream chemical applications using both full-parameter and parameter-efficient fine-tuning methods. ChemFM consistently outperforms state-of-the-art approaches across multiple chemical tasks. Notably, it achieves up to 67.48% performance improvement across 34 property prediction benchmarks, up to 33.31% reduction in mean average deviation between conditioned and actual properties of generated molecules in conditional molecular generation tasks, and up to 3.7% top-1 accuracy improvement across 4 reaction prediction datasets. Moreover, ChemFM demonstrates superior performance in predicting antibiotic activity and cytotoxicity, highlighting its potential to advance the discovery of novel antibiotics. We anticipate that ChemFM will significantly advance chemistry research by providing a foundation model capable of effectively generalizing across a broad range of tasks with minimal additional training.

[Arxiv](https://arxiv.org/abs/2410.21422)