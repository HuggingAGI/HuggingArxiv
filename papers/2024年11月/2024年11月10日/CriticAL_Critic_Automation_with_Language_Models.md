# CriticAL: 利用语言模型的批评自动化

发布时间：2024年11月10日

`LLM应用` `科学研究` `模型批评`

> CriticAL: Critic Automation with Language Models

# 摘要

> 通过模型理解世界是科学研究的一个基本目标。虽然基于大型语言模型（LLM）的方法在自动化科学发现方面显示出前景，但它们往往忽视了批评科学模型的重要性。批评模型加深了科学理解，并推动了更准确模型的发展。自动化模型批评是困难的，因为它传统上需要人类专家来定义如何将模型与数据进行比较，并评估差异是否显著——这两者都严重依赖于对建模假设和领域的理解。尽管基于 LLM 的批评方法很有吸引力，但它们带来了新的挑战：LLM 可能会产生幻觉般的批评。出于这个原因，我们引入了 CriticAL（使用语言模型的批评自动化）。CriticAL 使用 LLM 生成捕获模型预测和数据之间差异的汇总统计信息，并应用假设检验来评估其显著性。我们可以将 CriticAL 视为一个验证器，通过将它们嵌入假设检验框架中来验证模型及其批评。在实验中，我们在关键的定量和定性维度上评估 CriticAL。在我们合成模型和数据集之间差异的设置中，CriticAL 可靠地生成正确的批评，而不会产生错误的幻觉批评。我们表明，在透明度和可操作性方面，人类和 LLM 评委都一致更喜欢 CriticAL 的批评而不是其他方法。最后，我们表明 CriticAL 的批评使 LLM 科学家能够在真实世界的数据集上改进人类设计的模型。

> Understanding the world through models is a fundamental goal of scientific research. While large language model (LLM) based approaches show promise in automating scientific discovery, they often overlook the importance of criticizing scientific models. Criticizing models deepens scientific understanding and drives the development of more accurate models. Automating model criticism is difficult because it traditionally requires a human expert to define how to compare a model with data and evaluate if the discrepancies are significant--both rely heavily on understanding the modeling assumptions and domain. Although LLM-based critic approaches are appealing, they introduce new challenges: LLMs might hallucinate the critiques themselves. Motivated by this, we introduce CriticAL (Critic Automation with Language Models). CriticAL uses LLMs to generate summary statistics that capture discrepancies between model predictions and data, and applies hypothesis tests to evaluate their significance. We can view CriticAL as a verifier that validates models and their critiques by embedding them in a hypothesis testing framework. In experiments, we evaluate CriticAL across key quantitative and qualitative dimensions. In settings where we synthesize discrepancies between models and datasets, CriticAL reliably generates correct critiques without hallucinating incorrect ones. We show that both human and LLM judges consistently prefer CriticAL's critiques over alternative approaches in terms of transparency and actionability. Finally, we show that CriticAL's critiques enable an LLM scientist to improve upon human-designed models on real-world datasets.

[Arxiv](https://arxiv.org/abs/2411.06590)