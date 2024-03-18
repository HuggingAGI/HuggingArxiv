# [《寻找奇幻的语义世界：研究生成型LLM中各层对词汇语义的体现》](https://arxiv.org/abs/2403.01509)

发布时间：2024年03月03日

`LLM理论`

> Fantastic Semantics and Where to Find Them: Investigating Which Layers of Generative LLMs Reflect Lexical Semantics

> 大型语言模型在各类语言理解任务上成绩斐然，但对于下一代标记预测这一目标下的生成方法而言，像BERT同类结构那样深入探究模型随层数加深的语义演变尚未充分。本文聚焦于流行LLM——Llama2的词汇语义自底向上的演化过程，通过使用上下文化词识别任务探查其每一层末尾的隐藏状态。实验揭示：低层主要负责编码词汇语义，而高层因语义诱导能力相对较弱，更多承担预测功能，这一点与诸如掩码语言建模这样具有辨别性目标的模型形成对比——在后者中，高层往往能捕获更优的词汇语义。此外，结论还得到了一个现象的佐证：在提示策略中，对最后出现的无实际意义符号（如标点符号）所对应的隐藏状态性能呈单调增长趋势。

> Large language models have achieved remarkable success in general language understanding tasks. However, as a family of generative methods with the objective of next token prediction, the semantic evolution with the depth of these models are not fully explored, unlike their predecessors, such as BERT-like architectures. In this paper, we specifically investigate the bottom-up evolution of lexical semantics for a popular LLM, namely Llama2, by probing its hidden states at the end of each layer using a contextualized word identification task. Our experiments show that the representations in lower layers encode lexical semantics, while the higher layers, with weaker semantic induction, are responsible for prediction. This is in contrast to models with discriminative objectives, such as mask language modeling, where the higher layers obtain better lexical semantics. The conclusion is further supported by the monotonic increase in performance via the hidden states for the last meaningless symbols, such as punctuation, in the prompting strategy.

[Arxiv](https://arxiv.org/abs/2403.01509)