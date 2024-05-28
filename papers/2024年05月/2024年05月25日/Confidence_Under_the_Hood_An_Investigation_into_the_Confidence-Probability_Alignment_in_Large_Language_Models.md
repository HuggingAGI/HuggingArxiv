# 《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》

发布时间：2024年05月25日

`LLM理论

理由：这篇论文关注的是大型语言模型（LLMs）内部自信度的量化和评估，特别是探讨了模型内部通过令牌概率量化的自信度与模型在明确询问其确定性时所表达的自信度之间的对齐问题。这种研究属于对LLMs理论层面的探讨，因为它涉及到模型的内部机制和性能评估，而不是直接的应用或特定的Agent或RAG框架。因此，它更符合LLM理论分类。` `人工智能`

> Confidence Under the Hood: An Investigation into the Confidence-Probability Alignment in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的普及，理解它们如何自我评估生成答案的自信度变得至关重要，这直接关系到模型输出的可靠性。我们提出了“自信度-概率对齐”概念，旨在将LLM内部通过令牌概率量化的自信度与模型在明确询问其确定性时所表达的自信度相联系。通过多样化的数据集和提示策略，我们鼓励模型进行自我审视，以此探究模型内部自信度与表达自信度的一致性。这些策略包括采用结构化评估尺度来衡量自信度，提供答案选项以引导模型，以及探查模型对其不认可的输出的自信水平。特别地，在多个模型中，OpenAI的GPT-4表现出了最佳的自信度-概率对齐，平均斯皮尔曼相关系数达到0.42，覆盖了多种任务。我们的研究不仅助力于LLMs应用中的风险评估，也深化了我们对模型可信度的认识。

> As the use of Large Language Models (LLMs) becomes more widespread, understanding their self-evaluation of confidence in generated responses becomes increasingly important as it is integral to the reliability of the output of these models. We introduce the concept of Confidence-Probability Alignment, that connects an LLM's internal confidence, quantified by token probabilities, to the confidence conveyed in the model's response when explicitly asked about its certainty. Using various datasets and prompting techniques that encourage model introspection, we probe the alignment between models' internal and expressed confidence. These techniques encompass using structured evaluation scales to rate confidence, including answer options when prompting, and eliciting the model's confidence level for outputs it does not recognize as its own. Notably, among the models analyzed, OpenAI's GPT-4 showed the strongest confidence-probability alignment, with an average Spearman's $\hatρ$ of 0.42, across a wide range of tasks. Our work contributes to the ongoing efforts to facilitate risk assessment in the application of LLMs and to further our understanding of model trustworthiness.

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/Flowchart.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/Intro_Diagram.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/verbalized_certainty_graph.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/internal_confidence_graph.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/Appendix_diagram.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/verbalized_certainty_graph_bar_gpt3.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度解析》](../../../paper_images/2405.16282/internal_confidence_graph_gpt3.png)

[Arxiv](https://arxiv.org/abs/2405.16282)