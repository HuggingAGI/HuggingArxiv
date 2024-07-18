# 循环中的 LLM 第一章：专为生物医学文本翻译设计的小型 AI 专家模型

发布时间：2024年07月16日

`LLM应用` `机器翻译`

> LLMs-in-the-loop Part-1: Expert Small AI Models for Bio-Medical Text Translation

# 摘要

> 在医疗领域，机器翻译对于跨语言传播医学知识至关重要。然而，复杂的医学术语为高质量翻译带来了挑战。本研究采用“LLMs-in-the-loop”策略，针对医学文本优化神经机器翻译模型。研究表明，即使小型专业模型，通过高质量合成数据训练，也能超越大型通用模型。我们从科学文献、合成临床文档和医学文本中构建了六种语言的平行语料库。通过合成数据生成、严格评估和智能编排，我们的方法显著提升了翻译性能。基于MarianMT模型，我们开发了小型医学翻译模型，并引入新的测试数据集以标准化评估。评估结果显示，我们的模型在多项指标上超越了Google Translate、DeepL和GPT-4-Turbo。研究结果表明，结合高质量领域数据微调的LLMs-in-the-loop方法，能够使专业模型在性能上超越通用和某些大型系统。作为专家小型模型研究系列的一部分，本研究为未来医疗AI发展，如去标识化和生物医学实体提取，奠定了基础。我们的工作展示了定制神经翻译模型和LLMs-in-the-loop方法在改进数据处理、评估和建模技术方面的潜力，有望推动医疗翻译领域的进步。

> Machine translation is indispensable in healthcare for enabling the global dissemination of medical knowledge across languages. However, complex medical terminology poses unique challenges to achieving adequate translation quality and accuracy. This study introduces a novel "LLMs-in-the-loop" approach to develop supervised neural machine translation models optimized specifically for medical texts. While large language models (LLMs) have demonstrated powerful capabilities, this research shows that small, specialized models trained on high-quality in-domain (mostly synthetic) data can outperform even vastly larger LLMs.
  Custom parallel corpora in six languages were compiled from scientific articles, synthetically generated clinical documents, and medical texts. Our LLMs-in-the-loop methodology employs synthetic data generation, rigorous evaluation, and agent orchestration to enhance performance. We developed small medical translation models using the MarianMT base model. We introduce a new medical translation test dataset to standardize evaluation in this domain. Assessed using BLEU, METEOR, ROUGE, and BERT scores on this test set, our MarianMT-based models outperform Google Translate, DeepL, and GPT-4-Turbo.
  Results demonstrate that our LLMs-in-the-loop approach, combined with fine-tuning high-quality, domain-specific data, enables specialized models to outperform general-purpose and some larger systems. This research, part of a broader series on expert small models, paves the way for future healthcare-related AI developments, including deidentification and bio-medical entity extraction models. Our study underscores the potential of tailored neural translation models and the LLMs-in-the-loop methodology to advance the field through improved data generation, evaluation, agent, and modeling techniques.

[Arxiv](https://arxiv.org/abs/2407.12126)