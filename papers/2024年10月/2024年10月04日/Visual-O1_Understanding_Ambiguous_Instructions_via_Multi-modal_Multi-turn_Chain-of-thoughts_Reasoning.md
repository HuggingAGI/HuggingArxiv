# 借助多模态多轮链式思维推理，深入解析模糊指令的奥秘。

发布时间：2024年10月04日

`LLM应用` `人工智能` `多模态学习`

> Visual-O1: Understanding Ambiguous Instructions via Multi-modal Multi-turn Chain-of-thoughts Reasoning

# 摘要

> 随着大规模模型的进步，语言指令在多模态任务中的应用日益增多。然而，由于人类语言的天然模糊性，这些指令在实际应用中往往需要结合视觉信息或常识才能准确理解。即使是高度智能的模型，在面对模糊指令时也容易出现严重错误。为此，我们提出了 Visual-O1，一个多模态多轮推理框架，模拟人类的多模态思维过程，帮助模型更好地理解模糊指令。与传统方法相比，我们的框架不仅计算效率高，而且适用性广，即使是普通智能的模型也能受益。实验结果显示，我们的方法显著提升了模型在模糊指令和通用数据集上的表现。这项工作展示了人工智能在处理现实世界复杂性和模糊性方面的潜力。我们将公开相关数据和代码。

> As large-scale models evolve, language instructions are increasingly utilized in multi-modal tasks. Due to human language habits, these instructions often contain ambiguities in real-world scenarios, necessitating the integration of visual context or common sense for accurate interpretation. However, even highly intelligent large models exhibit significant performance limitations on ambiguous instructions, where weak reasoning abilities of disambiguation can lead to catastrophic errors. To address this issue, this paper proposes Visual-O1, a multi-modal multi-turn chain-of-thought reasoning framework. It simulates human multi-modal multi-turn reasoning, providing instantial experience for highly intelligent models or empirical experience for generally intelligent models to understand ambiguous instructions. Unlike traditional methods that require models to possess high intelligence to understand long texts or perform lengthy complex reasoning, our framework does not significantly increase computational overhead and is more general and effective, even for generally intelligent models. Experiments show that our method not only significantly enhances the performance of models of different intelligence levels on ambiguous instructions but also improves their performance on general datasets. Our work highlights the potential of artificial intelligence to work like humans in real-world scenarios with uncertainty and ambiguity. We will release our data and code.

[Arxiv](https://arxiv.org/abs/2410.03321)