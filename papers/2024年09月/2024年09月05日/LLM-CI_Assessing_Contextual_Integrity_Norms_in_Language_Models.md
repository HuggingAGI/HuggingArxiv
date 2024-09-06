# LLM-CI：探究语言模型中的上下文完整性规范

发布时间：2024年09月05日

`LLM理论` `隐私保护` `人工智能`

> LLM-CI: Assessing Contextual Integrity Norms in Language Models

# 摘要

> 大型语言模型（LLM）在记忆互联网数据的同时，也可能无意中编码了社会偏好和规范。随着这些模型融入社会技术系统，确保其编码的规范符合社会期望至关重要。然而，这些规范因模型、超参数、优化技术和数据集的不同而异，且提示的微小变化会导致不同响应，使得现有评估方法不可靠。因此，我们提出了 LLM-CI，首个开源框架，用于评估 LLM 中的隐私规范。LLM-CI 采用基于上下文完整性的因子小插图方法，评估不同上下文和 LLM 中的规范。我们还提出了多提示评估方法，通过仅评估在多个变体中产生一致响应的提示中的规范，来解决提示敏感性问题。通过 LLM-CI 和我们提出的方法，我们全面评估了 LLM，使用了物联网和 COPPA 小插图数据集，检查了模型属性和优化策略的影响。

> Large language models (LLMs), while memorizing parts of their training data scraped from the Internet, may also inadvertently encode societal preferences and norms. As these models are integrated into sociotechnical systems, it is crucial that the norms they encode align with societal expectations. These norms could vary across models, hyperparameters, optimization techniques, and datasets. This is especially challenging due to prompt sensitivity$-$small variations in prompts yield different responses, rendering existing assessment methodologies unreliable. There is a need for a comprehensive framework covering various models, optimization, and datasets, along with a reliable methodology to assess encoded norms.
  We present LLM-CI, the first open-sourced framework to assess privacy norms encoded in LLMs. LLM-CI uses a Contextual Integrity-based factorial vignette methodology to assess the encoded norms across different contexts and LLMs. We propose the multi-prompt assessment methodology to address prompt sensitivity by assessing the norms from only the prompts that yield consistent responses across multiple variants. Using LLM-CI and our proposed methodology, we comprehensively evaluate LLMs using IoT and COPPA vignettes datasets from prior work, examining the impact of model properties (e.g., hyperparameters, capacity) and optimization strategies (e.g., alignment, quantization).

[Arxiv](https://arxiv.org/abs/2409.03735)