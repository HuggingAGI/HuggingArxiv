# 在 Llama-3 70B 模型上进行训练后实践，通过最佳选择的额外语言混合比例优化效果

发布时间：2024年09月10日

`LLM应用` `人工智能`

> A Practice of Post-Training on Llama-3 70B with Optimal Selection of Additional Language Mixture Ratio

# 摘要

> 大型语言模型 (LLM) 通常需要持续预训练 (CPT) 以掌握新语言或适应新领域。然而，CPT 的高昂成本要求我们谨慎选择超参数，如语料库混合比例。本文中，我们对 Llama-3 8B 和 70B 进行了 CPT，以提升其中文能力。我们探讨了 8B 模型中额外语言混合比例 (ALMR) 与学习率 (LR) 的最佳组合，并通过精细调整，不仅提升了中文基准表现，还在数学、编码和情感智能等领域取得了进步。最终，我们将 70B 版本的 LLM 应用于实际聊天系统，表现出色。

> Large Language Models (LLM) often needs to be Continual Pre-Trained (CPT) to obtain the unfamiliar language skill or adapt into new domains. The huge training cost of CPT often asks for cautious choice of key hyper-parameters such as the mixture ratio of extra language or domain corpus. However, there is no systematic study which bridge the gap between the optimal mixture ratio and the actual model performance, and the gap between experimental scaling law and the actual deployment in the full model size. In this paper, we perform CPT on Llama-3 8B and 70B to enhance its Chinese ability. We study the optimal correlation between the Additional Language Mixture Ratio (ALMR) and the Learning Rate (LR) on the 8B size which directly indicate the optimal experimental set up. By thorough choice of hyper-parameter, and subsequent fine-tuning, the model capability is improved not only on the Chinese-related benchmark, but also some specific domains including math, coding and emotional intelligence. We deploy the final 70B version of LLM on an real-life chat system which obtain satisfying performance.

[Arxiv](https://arxiv.org/abs/2409.06624)