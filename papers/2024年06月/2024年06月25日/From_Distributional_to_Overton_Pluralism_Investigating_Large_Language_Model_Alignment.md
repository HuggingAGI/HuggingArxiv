# 从分布式模型到奥弗顿多元论：深入探讨大型语言模型的对齐策略

发布时间：2024年06月25日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）在对齐过程中的行为变化，包括响应多样性的减少和对齐模型与基础模型之间的关系。这些研究内容涉及LLM的理论层面，特别是对齐技术如何影响LLM的输出分布和行为。论文通过分析对齐后的模型行为，探讨了基础模型与对齐模型之间的差异和联系，这些内容属于LLM理论研究的范畴。此外，论文中提到的“表面对齐假说”和上下文对齐的潜力，都是对LLM理论深层次理解的探讨。` `人工智能`

> From Distributional to Overton Pluralism: Investigating Large Language Model Alignment

# 摘要

> 对齐过程显著改变了大型语言模型输出分布的特性。我们深入探讨了LLM响应对齐后分布变化的两个关键方面。首先，我们重新评估了对齐后响应多样性减少的现象，发现这种减少很大程度上是由于质量控制和信息整合所致。对齐不仅抑制了无关紧要的内容，还促使输出更倾向于包含多方面信息的长篇响应。其次，我们探讨了对齐模型是否揭示了基础模型无法恢复的信息，结果显示对齐模型的行为可从基础模型中无微调地恢复。通过结合上下文示例和响应内容的语义提示，基础LLM能够产生与对齐调整的LLM响应相似的结果。这些发现共同表明，当前的对齐技术虽能捕捉到基础LLM的有用行为，但并未扩展其范围，支持了表面对齐假说。同时，这也展示了上下文对齐在无需微调的情况下，能够有效模仿对齐LLM的潜力。相关代码和数据已公开在https://github.com/thomlake/investigating-alignment。

> The alignment process changes several properties of a large language model's (LLM's) output distribution. We analyze two aspects of post-alignment distributional shift of LLM responses. First, we re-examine previously reported reductions in response diversity post-alignment. Our analysis suggests that an apparent drop in the diversity of responses is largely explained by quality control and information aggregation. Alignment suppresses irrelevant and unhelpful content while shifting the output distribution toward longer responses that cover information spanning several responses from the base LLM, essentially presenting diverse information in a single response. Finding little evidence that alignment suppresses useful information, it is natural to ask the opposite question: do aligned models surface information that cannot be recovered from base models? Our second investigation shows this is not the case and the behavior of aligned models is recoverable from base models without fine-tuning. A combination of in-context examples and lower-resolution semantic hints about response content can elicit responses from base LLMs that are as similar to alignment-tuned LLM responses as alignment-tuned LLM responses are to each other. Taken together, these results indicate that current alignment techniques capture but do not extend the useful subset of assistant-like base LLM behavior, providing further evidence for the Superficial Alignment Hypothesis. They also show that in-context alignment can go surprisingly far as a strategy for imitating aligned LLMs without fine-tuning. Our code and data is available at https://github.com/thomlake/investigating-alignment.

[Arxiv](https://arxiv.org/abs/2406.17692)