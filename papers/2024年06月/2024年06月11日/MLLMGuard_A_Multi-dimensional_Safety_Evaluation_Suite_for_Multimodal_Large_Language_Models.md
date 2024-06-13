# MLLMGuard：多模态大型语言模型的全方位安全评估工具

发布时间：2024年06月11日

`LLM应用

这篇论文介绍了MLLMGuard，一个专为多模态大型语言模型（MLLMs）设计的安全评估工具。它专注于评估MLLMs在多个安全领域的表现，包括隐私、偏见、毒性、真实性和合法性，并使用了双语图像-文本数据集和自动评估器GuardRank。这个工具的开发和应用直接关联到LLM技术的实际应用和安全性评估，因此属于LLM应用类别。` `人工智能安全` `社交媒体分析`

> MLLMGuard: A Multi-dimensional Safety Evaluation Suite for Multimodal Large Language Models

# 摘要

> 随着大型语言模型（LLMs）技术的飞跃发展，多模态大型语言模型（MLLMs）在各类任务中大放异彩。然而，这些模型的实际应用环境错综复杂，易受恶意指令侵扰，潜藏安全隐患。现有的安全基准虽有所考量，但往往覆盖不全，缺乏应有的严谨与稳健。例如，GPT-4V既当裁判又当运动员的做法，因其自评倾向而信誉受损。为此，我们推出了MLLMGuard，一款专为MLLMs量身打造的多维安全评估工具，涵盖双语图像-文本数据集、推理辅助及轻量级评估器。MLLMGuard深入挖掘英汉双语及隐私、偏见、毒性、真实性、合法性五大安全领域，每个领域下设丰富子任务。我们的数据集源自社交媒体，融合了文本与图像的红队策略，并由专家精心标注，有效规避了开源数据集可能带来的评估偏差，确保了基准的严谨与挑战性。此外，我们还研发了全自动评估器GuardRank，其准确度远超GPT-4。对13款尖端模型的评估揭示，MLLMs在安全与责任之路上尚需砥砺前行。

> Powered by remarkable advancements in Large Language Models (LLMs), Multimodal Large Language Models (MLLMs) demonstrate impressive capabilities in manifold tasks. However, the practical application scenarios of MLLMs are intricate, exposing them to potential malicious instructions and thereby posing safety risks. While current benchmarks do incorporate certain safety considerations, they often lack comprehensive coverage and fail to exhibit the necessary rigor and robustness. For instance, the common practice of employing GPT-4V as both the evaluator and a model to be evaluated lacks credibility, as it tends to exhibit a bias toward its own responses. In this paper, we present MLLMGuard, a multidimensional safety evaluation suite for MLLMs, including a bilingual image-text evaluation dataset, inference utilities, and a lightweight evaluator. MLLMGuard's assessment comprehensively covers two languages (English and Chinese) and five important safety dimensions (Privacy, Bias, Toxicity, Truthfulness, and Legality), each with corresponding rich subtasks. Focusing on these dimensions, our evaluation dataset is primarily sourced from platforms such as social media, and it integrates text-based and image-based red teaming techniques with meticulous annotation by human experts. This can prevent inaccurate evaluation caused by data leakage when using open-source datasets and ensures the quality and challenging nature of our benchmark. Additionally, a fully automated lightweight evaluator termed GuardRank is developed, which achieves significantly higher evaluation accuracy than GPT-4. Our evaluation results across 13 advanced models indicate that MLLMs still have a substantial journey ahead before they can be considered safe and responsible.

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x1.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x2.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x3.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x4.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x5.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x6.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x7.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x8.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x9.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x10.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x11.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x12.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x13.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x14.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x15.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x16.png)

![MLLMGuard：多模态大型语言模型的全方位安全评估工具](../../../paper_images/2406.07594/x17.png)

[Arxiv](https://arxiv.org/abs/2406.07594)