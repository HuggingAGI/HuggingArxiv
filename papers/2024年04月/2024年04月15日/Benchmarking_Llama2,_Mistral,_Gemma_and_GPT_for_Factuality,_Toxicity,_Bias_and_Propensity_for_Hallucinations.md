# 本研究旨在对Llama2、Mistral、Gemma以及GPT等模型进行综合评估，探究它们在事实准确性、有害内容产生、偏见表现以及产生幻觉文本的倾向上的差异性。

发布时间：2024年04月15日

`LLM应用` `企业安全` `数据集评估`

> Benchmarking Llama2, Mistral, Gemma and GPT for Factuality, Toxicity, Bias and Propensity for Hallucinations

# 摘要

> 本文推出了十四个创新数据集，旨在评估大型语言模型在企业任务中的安全性。我们开发了一种评估方法，通过模型遵循指令并产出真实、公正、可靠和适宜内容的能力来衡量其安全性。研究以OpenAI GPT为参照标准，因其在各个安全层面的卓越表现。在开源模型中，Meta Llama2在确保事实性和减少毒性方面表现不俗，但容易产生幻觉。Mistral幻觉现象最少，但在处理毒性方面稍显不足，它在涉及多个任务和安全因素的特定领域数据集上表现优异。基于Google Gemini的新开源模型Gemma整体表现平衡，但稍显落后。在多轮对话中，我们注意到开源模型的安全性显著降低。除OpenAI GPT外，Mistral是唯一在多轮对话测试中保持良好表现的模型。

> This paper introduces fourteen novel datasets for the evaluation of Large Language Models' safety in the context of enterprise tasks. A method was devised to evaluate a model's safety, as determined by its ability to follow instructions and output factual, unbiased, grounded, and appropriate content. In this research, we used OpenAI GPT as point of comparison since it excels at all levels of safety. On the open-source side, for smaller models, Meta Llama2 performs well at factuality and toxicity but has the highest propensity for hallucination. Mistral hallucinates the least but cannot handle toxicity well. It performs well in a dataset mixing several tasks and safety vectors in a narrow vertical domain. Gemma, the newly introduced open-source model based on Google Gemini, is generally balanced but trailing behind. When engaging in back-and-forth conversation (multi-turn prompts), we find that the safety of open-source models degrades significantly. Aside from OpenAI's GPT, Mistral is the only model that still performed well in multi-turn tests.

[Arxiv](https://arxiv.org/abs/2404.09785)