# 仅使用 API 即可实现：无需访问 logits，也能为大型语言模型应用相符预测技术。

发布时间：2024年03月02日

`LLM应用`

> API Is Enough: Conformal Prediction for Large Language Models Without Logit-Access

> 面对大型语言模型中难以量化的不确定性问题，特别是当logit信息无法获取时，本研究提出了一种创新的一致性预测(CP)方法。该方法特别适应于仅能通过API访问的LLMs，且无需依赖logits，同时力求缩小预测集尺寸，并确保达到用户指定的统计覆盖率要求。其核心理念在于结合使用粗略（如样本频率）和精细（如语义相似度）两种不确定性衡量标准来设计非一致性度量。实验证明，在封闭式和开放式问题回答任务上，我们的方法在多数情况下都能优于基于logits的传统CP基准方法。

> This study aims to address the pervasive challenge of quantifying uncertainty in large language models (LLMs) without logit-access. Conformal Prediction (CP), known for its model-agnostic and distribution-free features, is a desired approach for various LLMs and data distributions. However, existing CP methods for LLMs typically assume access to the logits, which are unavailable for some API-only LLMs. In addition, logits are known to be miscalibrated, potentially leading to degraded CP performance. To tackle these challenges, we introduce a novel CP method that (1) is tailored for API-only LLMs without logit-access; (2) minimizes the size of prediction sets; and (3) ensures a statistical guarantee of the user-defined coverage. The core idea of this approach is to formulate nonconformity measures using both coarse-grained (i.e., sample frequency) and fine-grained uncertainty notions (e.g., semantic similarity). Experimental results on both close-ended and open-ended Question Answering tasks show our approach can mostly outperform the logit-based CP baselines.

[Arxiv](https://arxiv.org/abs/2403.01216)