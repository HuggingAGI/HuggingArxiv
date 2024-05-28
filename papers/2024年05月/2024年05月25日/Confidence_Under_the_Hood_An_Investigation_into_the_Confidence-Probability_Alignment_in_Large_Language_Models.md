# 《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》

发布时间：2024年05月25日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）内部自信度与模型表达自信度之间的关系，提出了“自信度-概率对齐”概念，并通过实验研究了这种对齐的程度。这一研究深入分析了模型的内部机制和性能，属于对LLMs理论层面的探讨，因此归类为LLM理论。` `人工智能`

> Confidence Under the Hood: An Investigation into the Confidence-Probability Alignment in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的普及，理解它们如何自我评估生成答案的自信度变得至关重要，因为这直接关系到模型输出的可靠性。我们提出了“自信度-概率对齐”概念，旨在将LLM内部通过令牌概率衡量的自信度与模型在被询问其确定性时所表达的自信度相联系。通过多样化的数据集和促进模型自我审视的提示策略，我们探索了模型内部自信度与表达自信度之间的匹配程度。这些策略包括采用结构化评估尺度来衡量自信度，提供答案选项以激发模型的自我评估，以及让模型对其不认可的输出表达自信水平。特别值得关注的是，在多个模型中，OpenAI的GPT-4在自信度-概率对齐方面表现最佳，平均斯皮尔曼相关系数达到0.42，覆盖了多种任务。我们的研究不仅助力于LLMs应用中的风险评估，也深化了我们对模型可信度的认识。

> As the use of Large Language Models (LLMs) becomes more widespread, understanding their self-evaluation of confidence in generated responses becomes increasingly important as it is integral to the reliability of the output of these models. We introduce the concept of Confidence-Probability Alignment, that connects an LLM's internal confidence, quantified by token probabilities, to the confidence conveyed in the model's response when explicitly asked about its certainty. Using various datasets and prompting techniques that encourage model introspection, we probe the alignment between models' internal and expressed confidence. These techniques encompass using structured evaluation scales to rate confidence, including answer options when prompting, and eliciting the model's confidence level for outputs it does not recognize as its own. Notably, among the models analyzed, OpenAI's GPT-4 showed the strongest confidence-probability alignment, with an average Spearman's $\hatρ$ of 0.42, across a wide range of tasks. Our work contributes to the ongoing efforts to facilitate risk assessment in the application of LLMs and to further our understanding of model trustworthiness.

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/Flowchart.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/Intro_Diagram.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/verbalized_certainty_graph.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/internal_confidence_graph.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/Appendix_diagram.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/verbalized_certainty_graph_bar_gpt3.png)

![《探秘信心之源：大型语言模型中信心与概率匹配度的深度剖析》](../../../paper_images/2405.16282/internal_confidence_graph_gpt3.png)

[Arxiv](https://arxiv.org/abs/2405.16282)