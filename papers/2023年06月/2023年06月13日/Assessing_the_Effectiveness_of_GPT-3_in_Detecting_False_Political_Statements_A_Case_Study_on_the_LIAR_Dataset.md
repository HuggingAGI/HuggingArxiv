# 探究 GPT-3 识别虚假政治言论的能力：基于 LIAR 数据集的案例分析

发布时间：2023年06月13日

`LLM应用` `政治分析` `信息安全`

> Assessing the Effectiveness of GPT-3 in Detecting False Political Statements: A Case Study on the LIAR Dataset

# 摘要

> 识别政治谎言对于保持信息的纯洁性和防止虚假信息在社会中蔓延具有重要意义。传统上，尖端的机器学习模型采取了多种策略来识别虚假陈述，包括利用元数据、n-gram分析、语言特性以及文体学特征。随着大型语言模型如GPT-3的出现，我们在多项任务上见证了前所未有的性能提升。本研究中，我们在LIAR数据集上运用GPT-3进行实验，无需额外的元数据或语言特征，便超越了现有最先进模型的准确度。我们还尝试了零样本学习，通过精心构造的提示，达到了接近顶尖的成绩。这种方法的优势在于模型为其判断提供了依据，不仅增强了决策过程的透明度，也让用户有机会检验所提供证据的真实性。

> The detection of political fake statements is crucial for maintaining information integrity and preventing the spread of misinformation in society. Historically, state-of-the-art machine learning models employed various methods for detecting deceptive statements. These methods include the use of metadata (W. Wang et al., 2018), n-grams analysis (Singh et al., 2021), and linguistic (Wu et al., 2022) and stylometric (Islam et al., 2020) features. Recent advancements in large language models, such as GPT-3 (Brown et al., 2020) have achieved state-of-the-art performance on a wide range of tasks. In this study, we conducted experiments with GPT-3 on the LIAR dataset (W. Wang et al., 2018) and achieved higher accuracy than state-of-the-art models without using any additional meta or linguistic features. Additionally, we experimented with zero-shot learning using a carefully designed prompt and achieved near state-of-the-art performance. An advantage of this approach is that the model provided evidence for its decision, which adds transparency to the model's decision-making and offers a chance for users to verify the validity of the evidence provided.

[Arxiv](https://arxiv.org/abs/2306.08190)