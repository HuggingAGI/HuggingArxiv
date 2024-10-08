# 揭示检索增强语言模型中参数记忆与非参数记忆的微妙互动

发布时间：2024年10月07日

`RAG` `人工智能`

> Deciphering the Interplay of Parametric and Non-parametric Memory in Retrieval-augmented Language Models

# 摘要

> 生成语言模型在处理专业知识时常常力不从心。检索增强生成（RAG）模型提供了一种解决方案，即在生成响应前先检索信息。本研究聚焦于 \textsc{Atlas} 方法，探讨其在已知知识与检索信息间的抉择。通过因果中介分析和实验，我们揭示了内部表示对信息处理的影响。研究发现，当模型需在参数化与非参数化信息间抉择时，更倾向于依赖上下文。此外，我们还深入分析了模型如何利用上下文信息，发现其内部运作机制包括判断上下文相关性及编码器输出表示的计算。

> Generative language models often struggle with specialized or less-discussed knowledge. A potential solution is found in Retrieval-Augmented Generation (RAG) models which act like retrieving information before generating responses. In this study, we explore how the \textsc{Atlas} approach, a RAG model, decides between what it already knows (parametric) and what it retrieves (non-parametric). We use causal mediation analysis and controlled experiments to examine how internal representations influence information processing. Our findings disentangle the effects of parametric knowledge and the retrieved context. They indicate that in cases where the model can choose between both types of information (parametric and non-parametric), it relies more on the context than the parametric knowledge. Furthermore, the analysis investigates the computations involved in \emph{how} the model uses the information from the context. We find that multiple mechanisms are active within the model and can be detected with mediation analysis: first, the decision of \emph{whether the context is relevant}, and second, how the encoder computes output representations to support copying when relevant.

[Arxiv](https://arxiv.org/abs/2410.05162)