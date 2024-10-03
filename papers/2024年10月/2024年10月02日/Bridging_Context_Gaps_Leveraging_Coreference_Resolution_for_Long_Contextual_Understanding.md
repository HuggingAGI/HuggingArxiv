# 跨越上下文鸿沟：借助共指消解，深化长文本理解

发布时间：2024年10月02日

`LLM应用` `问答系统`

> Bridging Context Gaps: Leveraging Coreference Resolution for Long Contextual Understanding

# 摘要

> 大型语言模型（LLM）在自然语言处理中表现出色，但在处理长篇上下文和有效问答时仍显不足。为解决这一问题，我们提出了长问题指代适应（LQCA）方法。LQCA 专注于长文本中的指代消解，通过四个步骤帮助模型更好地识别和管理引用，从而提升问答效果。实验结果显示，LQCA 在多个模型和数据集上均有显著提升，尤其是在 OpenAI-o1-mini 和 GPT-4o 上，证明了其有效性。

> Large language models (LLMs) have shown remarkable capabilities in natural language processing; however, they still face difficulties when tasked with understanding lengthy contexts and executing effective question answering. These challenges often arise due to the complexity and ambiguity present in longer texts. To enhance the performance of LLMs in such scenarios, we introduce the Long Question Coreference Adaptation (LQCA) method. This innovative framework focuses on coreference resolution tailored to long contexts, allowing the model to identify and manage references effectively. The LQCA method encompasses four key steps: resolving coreferences within sub-documents, computing the distances between mentions, defining a representative mention for coreference, and answering questions through mention replacement. By processing information systematically, the framework provides easier-to-handle partitions for LLMs, promoting better understanding. Experimental evaluations on a range of LLMs and datasets have yielded positive results, with a notable improvements on OpenAI-o1-mini and GPT-4o models, highlighting the effectiveness of leveraging coreference resolution to bridge context gaps in question answering.

[Arxiv](https://arxiv.org/abs/2410.01671)