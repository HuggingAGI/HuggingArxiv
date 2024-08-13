# 针对代码，对大型语言模型进行即时修复

发布时间：2024年08月11日

`LLM应用` `软件开发` `人工智能`

> Hotfixing Large Language Models for Cod

# 摘要

> LLM4Code 已成为开发者工具箱中的关键一员，助力代码补全与生成。然而，这些模型在实际应用中常生成缺陷代码，根源在于其训练数据中包含了大量此类代码。尽管开源社区不断修复这些缺陷，但将这些改进融入模型以减少不良行为却颇具挑战，因重新训练模型耗时且耗资源。为此，我们提出 LLM4Code 热修复方案，旨在高效、低副作用地改善模型行为。本文聚焦于通过热修复提升 LLM4Code 的代码质量。我们发现 CodeGen 系列模型常产出缺陷代码，并为此设定了三个热修复学习目标：学习理想行为、遗忘不良行为、保留其他代码知识，并为每个目标设计了相应的损失函数。通过对比四种微调方法，我们发现结合 LoRA 的优化策略显著提升了修复代码的生成率（高达 108.42%），同时大幅降低了缺陷代码的生成率（高达 50.47%）。统计验证表明，热修复并未损害模型在 HumanEval 基准上的功能正确性，且展现了卓越的时间效率。

> Large Language Models for Code (LLM4Code) have become an integral part of developers' workflows, assisting with tasks such as code completion and generation. However, these models are found to exhibit undesired behaviors after their release, like generating buggy code, due to their extensive training on vast amounts of source code that contain such buggy code. The training data (usually coming from open-source software) keeps evolving, e.g., developers fix the buggy code. However, adapting such evolution to mitigate LLM4Code's undesired behaviors is non-trivial, as retraining models on the updated dataset usually takes much time and resources. This motivates us to propose the concept of hotfixing LLM4Code, mitigating LLM4Code's undesired behaviors effectively and efficiently with minimal negative effects.
  This paper mainly focuses on hotfixing LLM4Code to make them generate less buggy code and more fixed code. We begin by demonstrating that models from the popular CodeGen family frequently generate buggy code. Then, we define three learning objectives in hotfixing and design multiple loss functions for each objective: (1) learn the desired behaviors, (2) unlearn the undesired behaviors, and (3) retain knowledge of other code. We evaluate four different fine-tuning techniques for hotfixing the models and gain the following insights. Optimizing these three learning goals together, using LoRA (low-rank adaptation), effectively influences the model's behavior. Specifically, it increases the generation of fixed code by up to 108.42% and decreases the generation of buggy code by up to 50.47%. Statistical tests confirm that hotfixing does not significantly affect the models' functional correctness on the HumanEval benchmark. We also show that hotfixing demonstrates strong time efficiency.

[Arxiv](https://arxiv.org/abs/2408.05727)