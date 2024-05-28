# 构建从弱到强泛化的统计框架

发布时间：2024年05月25日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）的对齐技术，特别是如何使用人类反馈来对齐具有超人能力的更强LLM，而不削弱其能力。论文通过研究预训练LLM的潜在知识，将问题转化为迁移学习，并提出了一种精炼方法来克服传统微调方法的限制。这些内容涉及LLM的理论和方法论，因此归类为LLM理论。` `人工智能` `迁移学习`

> A statistical framework for weak-to-strong generalization

# 摘要

> 现代大型语言模型（LLM）的对齐技术依赖于人类反馈，但这些技术是否限制了LLM的潜力仍是个谜。特别是，我们能否在不削弱其能力的情况下，用人类反馈来对齐具有超人能力的更强LLM？这是一个关于从弱到强泛化的问题：如何用能力较低的反馈训练出能力更强的模型。我们通过挖掘预训练LLM的潜在知识，证明了这种泛化是可行的。我们将这一问题转化为迁移学习，旨在将弱模型中的潜在概念传递给强预训练模型。我们发现，简单的微调方法存在固有限制，但基于问题结构提出的精炼方法有效地克服了这些限制。最后，我们通过三个LLM对齐任务验证了精炼方法的实际效果。

> Modern large language model (LLM) alignment techniques rely on human feedback, but it is unclear whether the techniques fundamentally limit the capabilities of aligned LLMs. In particular, it is unclear whether it is possible to align (stronger) LLMs with superhuman capabilities with (weaker) human feedback without degrading their capabilities. This is an instance of the weak-to-strong generalization problem: using weaker (less capable) feedback to train a stronger (more capable) model. We prove that weak-to-strong generalization is possible by eliciting latent knowledge from pre-trained LLMs. In particular, we cast the weak-to-strong generalization problem as a transfer learning problem in which we wish to transfer a latent concept from a weak model to a strong pre-trained model. We prove that a naive fine-tuning approach suffers from fundamental limitations, but an alternative refinement-based approach suggested by the problem structure provably overcomes the limitations of fine-tuning. Finally, we demonstrate the practical applicability of the refinement approach with three LLM alignment tasks.

[Arxiv](https://arxiv.org/abs/2405.16236)