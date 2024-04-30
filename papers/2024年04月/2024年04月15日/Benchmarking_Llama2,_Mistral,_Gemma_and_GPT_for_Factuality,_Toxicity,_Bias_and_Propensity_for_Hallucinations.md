# 对 Llama2、Mistral、Gemma 以及 GPT 进行性能评估，主要考察它们在事实准确性、有害内容产生、偏见以及产生幻觉的倾向等多个维度上的表现。

发布时间：2024年04月15日

`LLM应用` `企业安全` `人工智能安全`

> Benchmarking Llama2, Mistral, Gemma and GPT for Factuality, Toxicity, Bias and Propensity for Hallucinations

# 摘要

> 本论文推出了十四个创新数据集，旨在评估大型语言模型（LLM）在企业任务中的安全性。我们开发了一种评估模型安全性的方法，即模型遵循指令、输出真实、公正、有根据且恰当内容的能力。研究中，我们将 OpenAI GPT 作为安全性能的标杆，因为它在安全性的各个层面上都表现出色。在开源小型模型中，Meta Llama2 在真实性和有害性方面表现优异，但容易产生幻觉。相比之下，Mistral 最少产生幻觉，但对有害内容的处理能力较弱。它在融合了多种任务和安全要素的特定垂直领域的数据集中表现良好。新推出的基于 Google Gemini 的开源模型 Gemma 整体表现均衡，但仍有提升空间。在多轮对话测试中，我们注意到开源模型的安全性显著降低。除了 OpenAI 的 GPT，Mistral 是唯一在多轮对话中仍保持良好表现的模型。

> This paper introduces fourteen novel datasets for the evaluation of Large Language Models' safety in the context of enterprise tasks. A method was devised to evaluate a model's safety, as determined by its ability to follow instructions and output factual, unbiased, grounded, and appropriate content. In this research, we used OpenAI GPT as point of comparison since it excels at all levels of safety. On the open-source side, for smaller models, Meta Llama2 performs well at factuality and toxicity but has the highest propensity for hallucination. Mistral hallucinates the least but cannot handle toxicity well. It performs well in a dataset mixing several tasks and safety vectors in a narrow vertical domain. Gemma, the newly introduced open-source model based on Google Gemini, is generally balanced but trailing behind. When engaging in back-and-forth conversation (multi-turn prompts), we find that the safety of open-source models degrades significantly. Aside from OpenAI's GPT, Mistral is the only model that still performed well in multi-turn tests.

[Arxiv](https://arxiv.org/abs/2404.09785)