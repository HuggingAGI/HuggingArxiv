# 因果表示学习结合生成式人工智能：探索文本作为治疗的应用

发布时间：2024年10月01日

`LLM应用` `人工智能` `数据分析`

> Causal Representation Learning with Generative Artificial Intelligence: Application to Texts as Treatments

# 摘要

> 本文展示了如何借助生成式人工智能，提升非结构化高维数据（如文本）的因果推断效果。我们提出利用大型语言模型（LLM）生成处理，并基于其内部表示进行因果效应评估。这种方法能有效区分特定情感和主题等感兴趣特征与潜在混杂因素。与传统方法不同，我们的方案无需从数据中学习因果表示，因此估计更精准高效。我们还确立了非参数识别平均处理效果的条件，设计了避免重叠假设冲突的策略，并利用双重机器学习推导了估计器的渐近特性。此外，通过工具变量法，我们将该方法扩展至处理特征依赖人类感知而非固定不变的场景。模拟实验采用开源LLM Llama3生成的文本数据，验证了我们的估计器在因果表示学习算法中的优越性。

> In this paper, we demonstrate how to enhance the validity of causal inference with unstructured high-dimensional treatments like texts, by leveraging the power of generative Artificial Intelligence. Specifically, we propose to use a deep generative model such as large language models (LLMs) to efficiently generate treatments and use their internal representation for subsequent causal effect estimation. We show that the knowledge of this true internal representation helps separate the treatment features of interest, such as specific sentiments and certain topics, from other possibly unknown confounding features. Unlike the existing methods, our proposed approach eliminates the need to learn causal representation from the data and hence produces more accurate and efficient estimates. We formally establish the conditions required for the nonparametric identification of the average treatment effect, propose an estimation strategy that avoids the violation of the overlap assumption, and derive the asymptotic properties of the proposed estimator through the application of double machine learning. Finally, using an instrumental variables approach, we extend the proposed methodology to the settings, in which the treatment feature is based on human perception rather than is assumed to be fixed given the treatment object. We conduct simulation studies using the generated text data with an open-source LLM, Llama3, to illustrate the advantages of our estimator over the state-of-the-art causal representation learning algorithms.

[Arxiv](https://arxiv.org/abs/2410.00903)