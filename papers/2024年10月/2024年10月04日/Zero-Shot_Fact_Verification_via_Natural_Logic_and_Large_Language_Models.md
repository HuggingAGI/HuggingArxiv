# 通过自然逻辑与大型语言模型实现零-shot 事实验证

发布时间：2024年10月04日

`LLM应用` `人工智能`

> Zero-Shot Fact Verification via Natural Logic and Large Language Models

# 摘要

> 最近，通过自然逻辑开发的事实验证系统通过集合论操作符将声明与证据对齐，增强了其可解释性。然而，这些系统通常依赖大量带有自然逻辑注释的训练数据。为此，我们提出了一种零-shot方法，利用指令调优的大型语言模型的泛化能力。我们全面评估了该方法及其他系统的零-shot能力，涵盖人工和真实世界声明，包括多语言数据集。在零-shot泛化设置中，我们的方法优于未专门针对自然逻辑数据训练的系统，平均准确率提升8.96点。在零-shot迁移设置中，我们发现当前基于自然逻辑数据训练的系统在其他领域泛化能力不佳，而我们的方法在所有包含真实世界声明的数据集上均表现更优。

> The recent development of fact verification systems with natural logic has enhanced their explainability by aligning claims with evidence through set-theoretic operators, providing faithful justifications. Despite these advancements, such systems often rely on a large amount of training data annotated with natural logic. To address this issue, we propose a zero-shot method that utilizes the generalization capabilities of instruction-tuned large language models. To comprehensively assess the zero-shot capabilities of our method and other fact verification systems, we evaluate all models on both artificial and real-world claims, including multilingual datasets. We also compare our method against other fact verification systems in two setups. First, in the zero-shot generalization setup, we demonstrate that our approach outperforms other systems that were not specifically trained on natural logic data, achieving an average accuracy improvement of 8.96 points over the best-performing baseline. Second, in the zero-shot transfer setup, we show that current systems trained on natural logic data do not generalize well to other domains, and our method outperforms these systems across all datasets with real-world claims.

[Arxiv](https://arxiv.org/abs/2410.03341)