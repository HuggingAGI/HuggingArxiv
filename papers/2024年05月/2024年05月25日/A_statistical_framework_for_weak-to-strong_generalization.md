# 构建从弱到强泛化的统计框架

发布时间：2024年05月25日

`LLM理论

这篇论文探讨了大型语言模型（LLM）的对齐技术，特别是关于如何使用人类反馈来对齐具有超人能力的LLM而不削弱其潜力的问题。论文通过研究预训练LLM的潜在知识，提出了一种转移学习的方法，旨在将弱模型中的潜在概念迁移到强大的预训练模型中。这种方法通过精炼过程克服了简单微调方法的局限性，并通过三个LLM对齐任务验证了其有效性。因此，这篇论文更偏向于LLM的理论研究，探讨了模型对齐和泛化能力的理论问题。` `人工智能`

> A statistical framework for weak-to-strong generalization

# 摘要

> 现代大型语言模型（LLM）的对齐技术依赖于人类反馈，但这些技术是否限制了LLM的潜力仍是个谜。特别是，我们能否在不削弱其能力的情况下，用人类反馈来对齐具有超人能力的强大LLM？这是一个典型的弱到强泛化问题：用能力较弱的反馈训练能力更强的模型。我们通过挖掘预训练LLM的潜在知识，证明了这种泛化是可行的。我们将这一问题视为转移学习，旨在将弱模型中的潜在概念迁移到强大的预训练模型中。虽然简单的微调方法存在局限，但基于问题结构提出的精炼方法有效克服了这些限制。最后，我们通过三个LLM对齐任务验证了精炼方法的实用性。

> Modern large language model (LLM) alignment techniques rely on human feedback, but it is unclear whether the techniques fundamentally limit the capabilities of aligned LLMs. In particular, it is unclear whether it is possible to align (stronger) LLMs with superhuman capabilities with (weaker) human feedback without degrading their capabilities. This is an instance of the weak-to-strong generalization problem: using weaker (less capable) feedback to train a stronger (more capable) model. We prove that weak-to-strong generalization is possible by eliciting latent knowledge from pre-trained LLMs. In particular, we cast the weak-to-strong generalization problem as a transfer learning problem in which we wish to transfer a latent concept from a weak model to a strong pre-trained model. We prove that a naive fine-tuning approach suffers from fundamental limitations, but an alternative refinement-based approach suggested by the problem structure provably overcomes the limitations of fine-tuning. Finally, we demonstrate the practical applicability of the refinement approach with three LLM alignment tasks.

[Arxiv](https://arxiv.org/abs/2405.16236)