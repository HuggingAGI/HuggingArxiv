# 信赖大型语言模型的时机：确保信心与回答品质相匹配

发布时间：2024年04月26日

`LLM应用` `人工智能`

> When to Trust LLMs: Aligning Confidence with Response Quality

# 摘要

> 尽管大型语言模型（LLMs）在自然语言生成领域取得了显著成就，但它们有时仍会产生错误或不合逻辑的文本。这一问题凸显了在安全至关重要的领域中，如何正确信任LLMs的重要性。目前的方法，通常依赖于通过生成置信度来评估模型的可靠性，但由于缺乏客观的置信度指导，这些方法常常失效。为了改善这一状况，我们提出了一种名为CONQORD的新型方法，该方法结合了强化学习和特别设计的双重奖励机制。这种机制不仅包含质量奖励，还包括顺序保持奖励，以激励模型对更高质量的输出表达更高的置信度，从而实现置信度与质量的一致性。实验结果证明，CONQORD显著提升了置信度与响应准确性的一致性，同时避免了模型过于保守。此外，CONQORD所提供的置信度对齐机制，不仅指导我们何时可以信赖LLMs，还作为触发外部知识检索过程的关键因素。通过确保置信度与响应质量的一致性，CONQORD确保了模型提供更透明、更可靠的输出，增强了其可信度。

> Despite the success of large language models (LLMs) in natural language generation, much evidence shows that LLMs may produce incorrect or nonsensical text. This limitation highlights the importance of discerning when to trust LLMs, especially in safety-critical domains. Existing methods, which rely on verbalizing confidence to tell the reliability by inducing top-k responses and sampling-aggregating multiple responses, often fail, due to the lack of objective guidance of confidence. To address this, we propose CONfidence-Quality-ORDerpreserving alignment approach (CONQORD), leveraging reinforcement learning with a tailored dual-component reward function. This function encompasses quality reward and orderpreserving alignment reward functions. Specifically, the order-preserving reward incentivizes the model to verbalize greater confidence for responses of higher quality to align the order of confidence and quality. Experiments demonstrate that our CONQORD significantly improves the alignment performance between confidence levels and response accuracy, without causing the model to become over-cautious. Furthermore, the aligned confidence provided by CONQORD informs when to trust LLMs, and acts as a determinant for initiating the retrieval process of external knowledge. Aligning confidence with response quality ensures more transparent and reliable responses, providing better trustworthiness.

[Arxiv](https://arxiv.org/abs/2404.17287)