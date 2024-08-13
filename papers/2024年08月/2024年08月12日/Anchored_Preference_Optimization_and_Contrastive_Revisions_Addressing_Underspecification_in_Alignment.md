# 通过锚定偏好优化与对比修订，我们致力于解决对齐过程中的未明确指定问题。

发布时间：2024年08月12日

`LLM理论` `人工智能`

> Anchored Preference Optimization and Contrastive Revisions: Addressing Underspecification in Alignment

# 摘要

> 大型语言模型 (LLM) 的对齐过程因模型、配对数据和目标的复杂交互而显得复杂，有时结果不尽如人意。我们研究发现，当底层响应具有对比性时，偏好数据能提供更有效的学习信号；同时，对齐目标在训练中对模型的控制越强，性能提升越显著。基于此，我们提出了 AI 修订的对比学习 (CLAIR) 和锚定的偏好优化 (APO)，前者能生成更多对比性强的偏好对，后者则提供了一个更可控且稳定的对齐目标。通过使用多种数据集和对齐目标对 Llama-3-8B-Instruct 进行对齐，并评估与人类判断高度相关的 MixEval-Hard 分数，我们发现 CLAIR 偏好显著提升了模型性能，而 APO 在可控性方面表现更优。最终，我们使用 32K CLAIR 偏好和 APO 训练的模型将 Llama-3-8B-Instruct 性能提升了 7.65%，与 GPT4-turbo 的差距大幅缩小了 45%。相关代码已公开在 https://github.com/ContextualAI/CLAIR_and_APO。

> Large Language Models (LLMs) are often aligned using contrastive alignment objectives and preference pair datasets. The interaction between model, paired data, and objective makes alignment a complicated procedure, sometimes producing subpar results. We study this and find that (i) preference data gives a better learning signal when the underlying responses are contrastive, and (ii) alignment objectives lead to better performance when they specify more control over the model during training. Based on these insights, we introduce Contrastive Learning from AI Revisions (CLAIR), a data-creation method which leads to more contrastive preference pairs, and Anchored Preference Optimization (APO), a controllable and more stable alignment objective. We align Llama-3-8B-Instruct using various comparable datasets and alignment objectives and measure MixEval-Hard scores, which correlate highly with human judgments. The CLAIR preferences lead to the strongest performance out of all datasets, and APO consistently outperforms less controllable objectives. Our best model, trained on 32K CLAIR preferences with APO, improves Llama-3-8B-Instruct by 7.65%, closing the gap with GPT4-turbo by 45%. Our code is available at https://github.com/ContextualAI/CLAIR_and_APO.

[Arxiv](https://arxiv.org/abs/2408.06266)