# 借助怀疑建模，我们有望减轻大型语言模型中的幻觉问题。

发布时间：2024年09月10日

`LLM理论` `人工智能`

> Alleviating Hallucinations in Large Language Models with Scepticism Modeling

# 摘要

> 大型语言模型（LLM）面临的主要难题之一是幻觉问题，这限制了其在多领域的应用。不确定性估计或许能缓解这一问题。人类的怀疑情绪可能有助于提升模型的自我评估能力。基于这一观察，我们提出了“怀疑建模”（SM）的新方法，通过整合标记和logits信息进行自我评估。我们构建了包含怀疑情绪的数据集，进行持续预训练并微调LLM，从而提升其自我评估能力。实验结果显示，该方法显著增强了模型的不确定性评估能力，并通过跨领域实验验证了其广泛适用性。

> Hallucinations is a major challenge for large language models (LLMs), prevents adoption in diverse fields. Uncertainty estimation could be used for alleviating the damages of hallucinations. The skeptical emotion of human could be useful for enhancing the ability of self estimation. Inspirited by this observation, we proposed a new approach called Skepticism Modeling (SM). This approach is formalized by combining the information of token and logits for self estimation. We construct the doubt emotion aware data, perform continual pre-training, and then fine-tune the LLMs, improve their ability of self estimation. Experimental results demonstrate this new approach effectively enhances a model's ability to estimate their uncertainty, and validate its generalization ability of other tasks by out-of-domain experiments.

[Arxiv](https://arxiv.org/abs/2409.06601)