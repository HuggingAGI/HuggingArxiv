# 评估法律问答系统的实际应用能力

发布时间：2024年10月11日

`LLM应用` `人工智能`

> Measuring the Groundedness of Legal Question-Answering Systems

# 摘要

> 在法律问答等高风险领域，生成式AI的准确性和可信度至关重要。我们提出了一套全面的方法，通过评估AI生成答案的基于事实性，来显著提升其可靠性。实验中，我们采用了基于相似性的指标和自然语言推理模型，确保答案与上下文一致。同时，我们探索了不同的大语言模型提示策略，以更有效地检测无事实基础的答案。通过专门为法律查询设计的基于事实性分类语料库，我们验证了这些方法的有效性，发现最佳方法的宏F1分数达到了0.8。此外，我们还评估了这些方法的延迟，确保它们适用于实际应用。总之，本研究展示了通过多种检测方法提升法律领域生成式AI可信度的潜力。

> In high-stakes domains like legal question-answering, the accuracy and trustworthiness of generative AI systems are of paramount importance. This work presents a comprehensive benchmark of various methods to assess the groundedness of AI-generated responses, aiming to significantly enhance their reliability. Our experiments include similarity-based metrics and natural language inference models to evaluate whether responses are well-founded in the given contexts. We also explore different prompting strategies for large language models to improve the detection of ungrounded responses. We validated the effectiveness of these methods using a newly created grounding classification corpus, designed specifically for legal queries and corresponding responses from retrieval-augmented prompting, focusing on their alignment with source material. Our results indicate potential in groundedness classification of generated responses, with the best method achieving a macro-F1 score of 0.8. Additionally, we evaluated the methods in terms of their latency to determine their suitability for real-world applications, as this step typically follows the generation process. This capability is essential for processes that may trigger additional manual verification or automated response regeneration. In summary, this study demonstrates the potential of various detection methods to improve the trustworthiness of generative AI in legal settings.

[Arxiv](https://arxiv.org/abs/2410.08764)