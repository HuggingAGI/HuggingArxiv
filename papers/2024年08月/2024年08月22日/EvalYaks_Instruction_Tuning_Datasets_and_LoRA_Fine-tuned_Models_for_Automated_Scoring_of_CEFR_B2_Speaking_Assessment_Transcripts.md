# EvalYaks 提供了一套指令调整数据集和 LoRA 微调模型，专门用于自动评估 CEFR B2 口语测试的转录文本。

发布时间：2024年08月22日

`LLM应用` `语言评估`

> EvalYaks: Instruction Tuning Datasets and LoRA Fine-tuned Models for Automated Scoring of CEFR B2 Speaking Assessment Transcripts

# 摘要

> 在电子学习环境中，依赖人类专家进行CEFR口语评估存在扩展难题，因其限制了评估的速度和范围。我们旨在通过对话记录自动化CEFR B2英语口语评估。首先，我们测试了顶尖的开源和商业LLM在全球及印度特定语境下对CEFR B2口语考试多维度评分的能力。随后，我们构建了一个经专家验证、与CEFR标准相符的合成对话数据集，包含不同评分等级的转录文本。同时，基于英语词汇概况（至B2级）和CEFR-SP WikiAuto数据集，开发了新的指令调整数据集。最终，利用这些数据集，我们对Mistral Instruct 7B v0.2进行了高效参数调整，推出了名为EvalYaks的模型系列，涵盖CEFR B2口语考试四个部分评估、词汇及文本CEFR级别识别与生成。EvalYaks平均准确率达96%，级别波动0.35级，性能领先其他模型三倍，证实了高质量CEFR对齐数据指令调整的7B参数LLM在自动化语言能力评估方面的潜力。

> Relying on human experts to evaluate CEFR speaking assessments in an e-learning environment creates scalability challenges, as it limits how quickly and widely assessments can be conducted. We aim to automate the evaluation of CEFR B2 English speaking assessments in e-learning environments from conversation transcripts. First, we evaluate the capability of leading open source and commercial Large Language Models (LLMs) to score a candidate's performance across various criteria in the CEFR B2 speaking exam in both global and India-specific contexts. Next, we create a new expert-validated, CEFR-aligned synthetic conversational dataset with transcripts that are rated at different assessment scores. In addition, new instruction-tuned datasets are developed from the English Vocabulary Profile (up to CEFR B2 level) and the CEFR-SP WikiAuto datasets. Finally, using these new datasets, we perform parameter efficient instruction tuning of Mistral Instruct 7B v0.2 to develop a family of models called EvalYaks. Four models in this family are for assessing the four sections of the CEFR B2 speaking exam, one for identifying the CEFR level of vocabulary and generating level-specific vocabulary, and another for detecting the CEFR level of text and generating level-specific text. EvalYaks achieved an average acceptable accuracy of 96%, a degree of variation of 0.35 levels, and performed 3 times better than the next best model. This demonstrates that a 7B parameter LLM instruction tuned with high-quality CEFR-aligned assessment data can effectively evaluate and score CEFR B2 English speaking assessments, offering a promising solution for scalable, automated language proficiency evaluation.

[Arxiv](https://arxiv.org/abs/2408.12226)