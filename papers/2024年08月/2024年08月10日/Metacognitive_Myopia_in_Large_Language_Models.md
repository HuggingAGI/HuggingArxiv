# 大型语言模型中的元认知盲点

发布时间：2024年08月10日

`LLM理论` `人工智能`

> Metacognitive Myopia in Large Language Models

# 摘要

> 大型语言模型（LLM）可能表现出强化文化刻板印象、模糊道德判断或放大多数群体正面评价的有害偏见。传统上，这些偏见被归咎于人类标注者和训练数据的选择，并通过强化学习或去偏见语料库等自下而上的方法来解决。然而，这些方法仅间接调整模型架构，未触及计算过程的根本原因。为此，我们提出“元认知近视”这一认知生态框架，它不仅能解释现有及新兴的LLM偏见，还为解决这些强大但脆弱工具的问题提供了新思路。该框架指出，元认知的监控与控制缺失导致LLM出现整合无效信息、易受冗余影响、忽视基础概率、基于频率决策及不当高阶统计推断等五种症状，进而影响人类的高风险日常决策。通过引入元认知调节机制，我们可精准针对这些偏见的根源进行修正。这一理论不仅揭示了人机交互中的缺陷，也引发了关于LLM在组织中不慎应用的伦理担忧。

> Large Language Models (LLMs) exhibit potentially harmful biases that reinforce culturally inherent stereotypes, cloud moral judgments, or amplify positive evaluations of majority groups. Previous explanations mainly attributed bias in LLMs to human annotators and the selection of training data. Consequently, they have typically been addressed with bottom-up approaches such as reinforcement learning or debiasing corpora. However, these methods only treat the effects of LLM biases by indirectly influencing the model architecture, but do not address the underlying causes in the computational process. Here, we propose metacognitive myopia as a cognitive-ecological framework that can account for a conglomerate of established and emerging LLM biases and provide a lever to address problems in powerful but vulnerable tools. Our theoretical framework posits that a lack of the two components of metacognition, monitoring and control, causes five symptoms of metacognitive myopia in LLMs: integration of invalid tokens and embeddings, susceptibility to redundant information, neglect of base rates in conditional computation, decision rules based on frequency, and inappropriate higher-order statistical inference for nested data structures. As a result, LLMs produce erroneous output that reaches into the daily high-stakes decisions of humans. By introducing metacognitive regulatory processes into LLMs, engineers and scientists can develop precise remedies for the underlying causes of these biases. Our theory sheds new light on flawed human-machine interactions and raises ethical concerns regarding the increasing, imprudent implementation of LLMs in organizational structures.

[Arxiv](https://arxiv.org/abs/2408.05568)