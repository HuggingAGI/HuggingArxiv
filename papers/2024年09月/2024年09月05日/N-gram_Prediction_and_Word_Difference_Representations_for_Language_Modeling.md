# 语言建模中的 N-gram 预测与词差异表示

发布时间：2024年09月05日

`LLM理论` `人工智能`

> N-gram Prediction and Word Difference Representations for Language Modeling

# 摘要

> 因果语言建模 (CLM) 是支撑大型语言模型 (LLM) 成功的基石。然而，下一个词预测的训练方法可能导致模型过度关注句子中的局部依赖。本研究中，我们为 CLM 任务引入了简单的 N-gram 预测框架，并结合词差异表示 (WDR) 进行模型训练。此外，我们提出了一种集成方法，以提升下一个词预测的质量。实证结果显示，我们的方法在多个基准数据集上显著优于传统 CLM。

> Causal language modeling (CLM) serves as the foundational framework underpinning remarkable successes of recent large language models (LLMs). Despite its success, the training approach for next word prediction poses a potential risk of causing the model to overly focus on local dependencies within a sentence. While prior studies have been introduced to predict future N words simultaneously, they were primarily applied to tasks such as masked language modeling (MLM) and neural machine translation (NMT). In this study, we introduce a simple N-gram prediction framework for the CLM task. Moreover, we introduce word difference representation (WDR) as a surrogate and contextualized target representation during model training on the basis of N-gram prediction framework. To further enhance the quality of next word prediction, we propose an ensemble method that incorporates the future N words' prediction results. Empirical evaluations across multiple benchmark datasets encompassing CLM and NMT tasks demonstrate the significant advantages of our proposed methods over the conventional CLM.

[Arxiv](https://arxiv.org/abs/2409.03295)