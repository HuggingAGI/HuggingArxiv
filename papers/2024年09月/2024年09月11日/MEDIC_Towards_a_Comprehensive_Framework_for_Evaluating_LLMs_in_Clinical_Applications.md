# MEDIC：构建全面框架，评估 LLM 在临床应用中的表现

发布时间：2024年09月11日

`LLM应用` `人工智能`

> MEDIC: Towards a Comprehensive Framework for Evaluating LLMs in Clinical Applications

# 摘要

> 医疗领域 LLM 的迅猛发展呼吁超越 USMLE 等传统基准的全面评估，以更真实地反映其实际表现。尽管现实评估具有重要价值，但其更新速度往往跟不上 LLM 的进化，可能导致部署时信息过时。为此，我们提出了 MEDIC 框架，从医学推理、伦理偏见、数据语言理解、上下文学习及临床安全五个维度全面评估 LLM。MEDIC 通过创新的交叉检验方法，无需参考输出即可量化模型在覆盖率和幻觉检测等方面的表现。我们将其应用于医学问答、安全、总结等任务，发现不同模型间存在显著性能差异，这对低幻觉或低成本推理等特定需求下的模型选择具有指导意义。MEDIC 的多维度评估不仅揭示了性能权衡，更弥合了理论与实践间的鸿沟，确保最优模型能适应多样化的医疗应用场景。

> The rapid development of Large Language Models (LLMs) for healthcare applications has spurred calls for holistic evaluation beyond frequently-cited benchmarks like USMLE, to better reflect real-world performance. While real-world assessments are valuable indicators of utility, they often lag behind the pace of LLM evolution, likely rendering findings obsolete upon deployment. This temporal disconnect necessitates a comprehensive upfront evaluation that can guide model selection for specific clinical applications. We introduce MEDIC, a framework assessing LLMs across five critical dimensions of clinical competence: medical reasoning, ethics and bias, data and language understanding, in-context learning, and clinical safety. MEDIC features a novel cross-examination framework quantifying LLM performance across areas like coverage and hallucination detection, without requiring reference outputs. We apply MEDIC to evaluate LLMs on medical question-answering, safety, summarization, note generation, and other tasks. Our results show performance disparities across model sizes, baseline vs medically finetuned models, and have implications on model selection for applications requiring specific model strengths, such as low hallucination or lower cost of inference. MEDIC's multifaceted evaluation reveals these performance trade-offs, bridging the gap between theoretical capabilities and practical implementation in healthcare settings, ensuring that the most promising models are identified and adapted for diverse healthcare applications.

[Arxiv](https://arxiv.org/abs/2409.07314)