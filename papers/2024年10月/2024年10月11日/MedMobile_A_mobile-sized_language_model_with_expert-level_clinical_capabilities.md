# MedMobile：一款具备专家级临床能力的移动端语言模型

发布时间：2024年10月11日

`LLM应用` `人工智能`

> MedMobile: A mobile-sized language model with expert-level clinical capabilities

# 摘要

> 语言模型在医学领域展现了专家级的推理和记忆能力，但计算成本和隐私问题成为广泛应用的障碍。我们推出了 MedMobile，一个 38 亿参数的移动端语言模型，专为医疗应用设计。MedMobile 在 MedQA (USMLE) 上的得分高达 75.7%，超越了医生的及格线，并接近大型模型的表现。通过一系列消融实验，我们发现思维链、集成和微调显著提升了性能，而检索增强生成并未带来预期效果。

> Language models (LMs) have demonstrated expert-level reasoning and recall abilities in medicine. However, computational costs and privacy concerns are mounting barriers to wide-scale implementation. We introduce a parsimonious adaptation of phi-3-mini, MedMobile, a 3.8 billion parameter LM capable of running on a mobile device, for medical applications. We demonstrate that MedMobile scores 75.7% on the MedQA (USMLE), surpassing the passing mark for physicians (~60%), and approaching the scores of models 100 times its size. We subsequently perform a careful set of ablations, and demonstrate that chain of thought, ensembling, and fine-tuning lead to the greatest performance gains, while unexpectedly retrieval augmented generation fails to demonstrate significant improvements

[Arxiv](https://arxiv.org/abs/2410.09019)