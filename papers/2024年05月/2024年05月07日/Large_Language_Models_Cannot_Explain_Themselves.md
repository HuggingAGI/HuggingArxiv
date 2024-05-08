# 巨型语言模型自解谜团难，其内在逻辑尚待深究。

发布时间：2024年05月07日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）生成的解释与其内部运作机制之间的关系，提出了“外生解释”（exoplanations）的概念，并讨论了在设计和实施这些解释时可能遇到的问题和挑战。这属于对LLM理论层面的探讨，因为它关注的是模型输出解释的本质和模型本身的理解，而不是具体的应用场景或Agent的行为。因此，它更适合归类于LLM理论。` `人工智能伦理` `模型解释性`

> Large Language Models Cannot Explain Themselves

# 摘要

> 大型语言模型虽能通过提示生成文本及其“解释”，但这些解释并非真实反映模型运作机制，可能误导人们以为它们揭示了推理过程，从而带来风险。这些“解释”的价值在于激发批判性思维，而非深入理解模型。我建议重新审视这些“解释”，并引入“外生解释”（exoplanations）这一概念，以凸显其非内在特性。同时，我探讨了在设计和技术层面上的相关影响，包括在模型生成解释时设置恰当的防护机制和应对策略。

> Large language models can be prompted to produce text. They can also be prompted to produce "explanations" of their output. But these are not really explanations, because they do not accurately reflect the mechanical process underlying the prediction. The illusion that they reflect the reasoning process can result in significant harms. These "explanations" can be valuable, but for promoting critical thinking rather than for understanding the model. I propose a recontextualisation of these "explanations", using the term "exoplanations" to draw attention to their exogenous nature. I discuss some implications for design and technology, such as the inclusion of appropriate guardrails and responses when models are prompted to generate explanations.

[Arxiv](https://arxiv.org/abs/2405.04382)