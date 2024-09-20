# Michelangelo：借助潜在结构查询，实现超越干草堆的长上下文精准评估

发布时间：2024年09月19日

`LLM应用` `人工智能`

> Michelangelo: Long Context Evaluations Beyond Haystacks via Latent Structure Queries

# 摘要

> 我们推出了 Michelangelo，这是一个专为大型语言模型设计的长上下文推理评估工具，它不仅简洁、合成且未泄露，还易于自动评分。该评估基于一个创新的统一框架，旨在测试模型在处理任意长度上下文时的深层能力，而不仅仅是检索单一信息。\frameworkshort 框架的核心在于设计任务，要求模型剔除无关信息，揭示潜在结构。为验证模型对这些结构的理解，我们进行细节查询。通过 \frameworkshort，我们在代码和自然语言领域创建了三个诊断性评估，以更准确地反映模型的长上下文处理能力。我们对多个顶尖模型进行了测试，结果显示，这些评估极具参考价值，同时表明在长上下文信息合成方面仍有巨大提升空间。

> We introduce Michelangelo: a minimal, synthetic, and unleaked long-context reasoning evaluation for large language models which is also easy to automatically score. This evaluation is derived via a novel, unifying framework for evaluations over arbitrarily long contexts which measure the model's ability to do more than retrieve a single piece of information from its context. The central idea of the \frameworkname framework (\frameworkshort) is to construct tasks which require a model to ``chisel away'' the irrelevant information in the context, revealing a latent structure in the context. To verify a model's understanding of this latent structure, we query the model for details of the structure. Using \frameworkshort, we produce three diagnostic long-context evaluations across code and natural-language domains intended to provide a stronger signal of long-context language model capabilities. We perform evaluations on several state-of-the-art models and demonstrate both that a) the proposed evaluations are high-signal and b) that there is significant room for improvement in synthesizing long-context information.

[Arxiv](https://arxiv.org/abs/2409.12640)