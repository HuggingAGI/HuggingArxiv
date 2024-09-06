# 提升医疗LLM的信任度：非典型表现的重新校准

发布时间：2024年09月04日

`LLM应用` `人工智能`

> Enhancing Healthcare LLM Trust with Atypical Presentations Recalibration

# 摘要

> 黑箱大型语言模型 (LLM) 在各种环境中越来越广泛地部署，使得这些模型有效地传达其信心和不确定性变得至关重要，尤其是在高风险环境中。然而，这些模型往往表现出过度自信，导致潜在的风险和误判。现有的引发和校准 LLM 信心的技术主要集中在一般推理数据集上，仅取得了适度的改进。准确的校准对于知情决策和防止不良后果至关重要，但由于这些模型执行的任务的复杂性和可变性，仍然具有挑战性。在这项工作中，我们研究了黑箱 LLM 在医疗保健环境中的校准不当行为。我们提出了一种新颖的方法，\textit{Atypical Presentations Recalibration}，该方法利用非典型表现来调整模型的信心估计。我们的方法显著改善了校准，在三个医学问答数据集上将校准误差减少了约 60\%，并优于现有的方法，如普通口头信心、CoT 口头信心等。此外，我们深入分析了非典型性在校准框架中的作用。

> Black-box large language models (LLMs) are increasingly deployed in various environments, making it essential for these models to effectively convey their confidence and uncertainty, especially in high-stakes settings. However, these models often exhibit overconfidence, leading to potential risks and misjudgments. Existing techniques for eliciting and calibrating LLM confidence have primarily focused on general reasoning datasets, yielding only modest improvements. Accurate calibration is crucial for informed decision-making and preventing adverse outcomes but remains challenging due to the complexity and variability of tasks these models perform. In this work, we investigate the miscalibration behavior of black-box LLMs within the healthcare setting. We propose a novel method, \textit{Atypical Presentations Recalibration}, which leverages atypical presentations to adjust the model's confidence estimates. Our approach significantly improves calibration, reducing calibration errors by approximately 60\% on three medical question answering datasets and outperforming existing methods such as vanilla verbalized confidence, CoT verbalized confidence and others. Additionally, we provide an in-depth analysis of the role of atypicality within the recalibration framework.

[Arxiv](https://arxiv.org/abs/2409.03225)