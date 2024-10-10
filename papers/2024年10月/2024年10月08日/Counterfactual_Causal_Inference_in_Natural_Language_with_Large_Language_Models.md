# 利用大型语言模型在自然语言中进行反事实因果推断

发布时间：2024年10月08日

`LLM应用` `人工智能`

> Counterfactual Causal Inference in Natural Language with Large Language Models

# 摘要

> 因果结构发现方法常用于已知因果变量的结构化数据，并通过统计测试评估因果关系。然而，从新闻文章等非结构化自然语言数据中恢复因果结构则因缺乏已知变量和反事实数据而充满挑战。尽管大型语言模型 (LLM) 在这方面展现了潜力，但仍存在局限。本研究探讨了 LLM 从文本构建因果图并进行反事实推理的能力。我们提出了一种端到端的自然语言因果结构发现与推理方法：首先，利用 LLM 从文本中提取因果变量并构建因果图；接着，整合多源数据以构建最全面的因果图；最后，在图中进行反事实推理。这种方法不仅减少了 LLM 的偏差，还更准确地反映了因果关系。我们通过实验揭示了 LLM 在反事实推理中的预测错误，并提出了改进方向。最终，我们在真实新闻文章上验证了该方法的有效性。

> Causal structure discovery methods are commonly applied to structured data where the causal variables are known and where statistical testing can be used to assess the causal relationships. By contrast, recovering a causal structure from unstructured natural language data such as news articles contains numerous challenges due to the absence of known variables or counterfactual data to estimate the causal links. Large Language Models (LLMs) have shown promising results in this direction but also exhibit limitations. This work investigates LLM's abilities to build causal graphs from text documents and perform counterfactual causal inference. We propose an end-to-end causal structure discovery and causal inference method from natural language: we first use an LLM to extract the instantiated causal variables from text data and build a causal graph. We merge causal graphs from multiple data sources to represent the most exhaustive set of causes possible. We then conduct counterfactual inference on the estimated graph. The causal graph conditioning allows reduction of LLM biases and better represents the causal estimands. We use our method to show that the limitations of LLMs in counterfactual causal reasoning come from prediction errors and propose directions to mitigate them. We demonstrate the applicability of our method on real-world news articles.

[Arxiv](https://arxiv.org/abs/2410.06392)