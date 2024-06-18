# 语言模型中的拒绝行为，其机制受单一方向的影响。

发布时间：2024年06月17日

`LLM理论

这篇论文探讨了大型语言模型（LLM）在处理指令时的拒绝行为背后的机制，并提出了一种新的白盒越狱技术。研究集中在模型内部的特定方向，这对于模型的拒绝行为至关重要。此外，论文还讨论了对抗性后缀对拒绝机制的影响，以及现有安全微调方法的脆弱性。这些内容主要涉及LLM的理论分析和模型内部工作原理的深入探讨，因此归类为LLM理论。` `人工智能安全` `对话系统`

> Refusal in Language Models Is Mediated by a Single Direction

# 摘要

> 对话大型语言模型经过精心微调，既能遵循指令又确保安全，它们能接受良性请求，却拒绝有害请求。尽管这种拒绝行为在聊天模型中普遍存在，但其背后的工作原理仍是个谜。本研究揭示，这种拒绝行为是通过一个一维空间介导的，涉及13个流行的开源聊天模型，参数规模高达720亿。我们发现，每个模型中存在一个关键方向，移除它，模型便不再拒绝有害指令；反之，增加它，连无害指令也会遭到拒绝。基于此，我们提出了一种创新的白盒越狱技术，精准地关闭拒绝功能，同时尽量不影响其他能力。此外，我们还揭示了对抗性后缀如何抑制拒绝机制的传播，强调了现有安全微调方法的脆弱性。我们的研究不仅展示了深入理解模型内部如何助力开发实用的行为控制方法，也为模型安全性的提升指明了方向。

> Conversational large language models are fine-tuned for both instruction-following and safety, resulting in models that obey benign requests but refuse harmful ones. While this refusal behavior is widespread across chat models, its underlying mechanisms remain poorly understood. In this work, we show that refusal is mediated by a one-dimensional subspace, across 13 popular open-source chat models up to 72B parameters in size. Specifically, for each model, we find a single direction such that erasing this direction from the model's residual stream activations prevents it from refusing harmful instructions, while adding this direction elicits refusal on even harmless instructions. Leveraging this insight, we propose a novel white-box jailbreak method that surgically disables refusal with minimal effect on other capabilities. Finally, we mechanistically analyze how adversarial suffixes suppress propagation of the refusal-mediating direction. Our findings underscore the brittleness of current safety fine-tuning methods. More broadly, our work showcases how an understanding of model internals can be leveraged to develop practical methods for controlling model behavior.

[Arxiv](https://arxiv.org/abs/2406.11717)