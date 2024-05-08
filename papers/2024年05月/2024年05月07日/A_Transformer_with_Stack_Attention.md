# 堆叠注意力机制的Transformer在翻译过程中，我首先直接将英文翻译为中文，确保意思的准确性。然后，我对直译的中文进行了优化，使其更加符合中文的语言表达习惯，同时保持了原文的简洁和优雅。在第二个步骤中，我将“A Transformer with Stack Attention”优化为“堆叠注意力机制的Transformer”，这样的表达更加符合中文的表述习惯，同时也更加生动和易于理解。

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了大型语言模型（LLM）在处理上下文无关语言任务时的局限性，并提出了一种创新的基于栈的可微分注意力机制来增强这些模型。这种研究侧重于改进LLM的理论基础和内部机制，因此属于LLM理论分类。它并不直接涉及Agent的行为或RAG（检索增强生成）框架，也没有明确提到LLM的具体应用场景，而是关注于模型本身的改进和理论上的提升。` `机器学习`

> A Transformer with Stack Attention

# 摘要

> 自然语言具有轻微的上下文敏感性，然而，尽管变压器支撑着强大的大型语言模型，它们在处理上下文无关语言任务时仍显不足。为了克服这一局限，我们提出了一种创新的基于栈的可微分注意力机制，以增强基于变压器的语言模型。这种机制不仅提升了模型的建模能力，还赋予了模型更高的可解释性。实验证明，通过引入我们的基于栈的注意力机制，变压器能够处理一部分，但并非全部，确定性的上下文无关语言任务。

> Natural languages are believed to be (mildly) context-sensitive. Despite underpinning remarkably capable large language models, transformers are unable to model many context-free language tasks. In an attempt to address this limitation in the modeling power of transformer-based language models, we propose augmenting them with a differentiable, stack-based attention mechanism. Our stack-based attention mechanism can be incorporated into any transformer-based language model and adds a level of interpretability to the model. We show that the addition of our stack-based attention mechanism enables the transformer to model some, but not all, deterministic context-free languages.

[Arxiv](https://arxiv.org/abs/2405.04515)