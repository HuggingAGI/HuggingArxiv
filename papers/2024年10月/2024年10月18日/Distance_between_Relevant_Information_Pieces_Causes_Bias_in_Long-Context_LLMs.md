# 长上下文 LLM 中，相关信息片段的距离会导致偏差。

发布时间：2024年10月18日

`LLM应用` `人工智能`

> Distance between Relevant Information Pieces Causes Bias in Long-Context LLMs

# 摘要

> 大型语言模型在处理长输入时，常因位置偏差而受限，尤其是“迷失在中间”现象。尽管现有研究多关注单一信息，但实际应用中常涉及多条相关信息。为此，我们推出了 LongPiBench 基准，专门评估多条信息的位置偏差。实验涵盖五款商业模型和六款开源模型，结果显示，虽然多数模型能应对“迷失在中间”问题，但信息间距仍存在显著偏差。这凸显了评估和减少位置偏差对提升 LLM 能力的重要性。

> Positional bias in large language models (LLMs) hinders their ability to effectively process long inputs. A prominent example is the "lost in the middle" phenomenon, where LLMs struggle to utilize relevant information situated in the middle of the input. While prior research primarily focuses on single pieces of relevant information, real-world applications often involve multiple relevant information pieces. To bridge this gap, we present LongPiBench, a benchmark designed to assess positional bias involving multiple pieces of relevant information. Thorough experiments are conducted with five commercial and six open-source models. These experiments reveal that while most current models are robust against the "lost in the middle" issue, there exist significant biases related to the spacing of relevant information pieces. These findings highlight the importance of evaluating and reducing positional biases to advance LLM's capabilities.

[Arxiv](https://arxiv.org/abs/2410.14641)