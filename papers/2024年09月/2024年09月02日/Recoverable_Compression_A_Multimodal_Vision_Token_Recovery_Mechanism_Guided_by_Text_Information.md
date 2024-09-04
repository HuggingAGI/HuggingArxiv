# 可恢复压缩机制：借助文本信息，实现多模态视觉令牌的精准恢复。

发布时间：2024年09月02日

`LLM应用` `计算机视觉` `人工智能`

> Recoverable Compression: A Multimodal Vision Token Recovery Mechanism Guided by Text Information

# 摘要

> 随着大规模语言建模技术的进步，结合视觉编码器和大型语言模型的大型多模态模型在多种视觉任务中表现出色。这些模型通过将视觉特征映射到语言模型中，并与文本一同作为下游任务的输入，从而影响模型的训练和推理速度。尽管针对视觉变换器的令牌剪枝已有深入研究，但对于大型多模态模型，仅依赖视觉信息进行剪枝可能导致重要信息丢失。为此，我们提出了一种无需训练的文本信息引导的动态视觉令牌恢复机制，该机制通过利用问题文本与视觉令牌的相似性，恢复具有重要文本信息的视觉令牌，同时合并其他次要令牌。实验结果显示，我们的方法在将视觉令牌压缩至原始数量的10%的同时，保持了与原方法相当的性能。我们的源代码将在接受后公开。

> With the advancement of large-scale language modeling techniques, large multimodal models combining visual encoders with large language models have demonstrated exceptional performance in various visual tasks. Most of the current large-scale multimodal models achieve this by mapping visual features obtained from the visual encoder into a large language model and using them as inputs alongside text for downstream tasks. Therefore, the number of visual tokens directly affects the training and inference speed of the model. There has been significant work on token pruning for visual transformers, but for large multimodal models, only relying on visual information for token pruning or compression may lead to significant loss of important information. On the other hand, the textual input in the form of a question may contain valuable information that can aid in answering the question, providing additional knowledge to the model. To address the potential oversimplification and excessive pruning that can occur with most purely visual token pruning methods, we propose a text information-guided dynamic visual token recovery mechanism that does not require training. This mechanism leverages the similarity between the question text and visual tokens to recover visually meaningful tokens with important text information while merging other less important tokens. Experimental results demonstrate that our proposed method achieves comparable performance to the original approach while compressing the visual tokens to an average of 10% of the original quantity. Our source code will be made publicly available following acceptance.

[Arxiv](https://arxiv.org/abs/2409.01179)