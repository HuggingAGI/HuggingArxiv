# 探索图像生成语言模型的设计奥秘

发布时间：2024年10月21日

`LLM应用` `计算机视觉` `图像生成`

> Elucidating the design space of language models for image generation

# 摘要

> 自回归语言模型在文本生成领域的成功，启发了计算机视觉领域采用大型语言模型进行图像生成。然而，由于文本与图像的本质差异，图像生成语言模型的设计空间仍待深入探索。我们发现，图像标记的随机性远超文本标记，这为基于标记预测的训练带来了挑战。尽管如此，自回归模型仍展现出从看似次优的优化问题中有效学习模式的能力。此外，所有模型虽都能掌握图像生成中的局部信息，但小型模型在捕捉全局上下文方面显得力不从心。相反，大型模型在这方面表现更佳，这解释了为何扩大模型规模能带来性能提升。通过广泛的对比实验，我们进一步揭示了视觉生成语言模型的设计空间，涵盖分词器选择、模型类型、可扩展性、词汇设计及采样策略。我们的研究首次剖析了语言模型在视觉生成中的优化行为，有望为其他领域的应用设计提供新思路。最终，我们提出的 ELM 模型在 ImageNet 256*256 基准测试中创下佳绩。代码已公开，详见 https://github.com/Pepperlll/LMforImageGeneration.git。

> The success of autoregressive (AR) language models in text generation has inspired the computer vision community to adopt Large Language Models (LLMs) for image generation. However, considering the essential differences between text and image modalities, the design space of language models for image generation remains underexplored. We observe that image tokens exhibit greater randomness compared to text tokens, which presents challenges when training with token prediction. Nevertheless, AR models demonstrate their potential by effectively learning patterns even from a seemingly suboptimal optimization problem. Our analysis also reveals that while all models successfully grasp the importance of local information in image generation, smaller models struggle to capture the global context. In contrast, larger models showcase improved capabilities in this area, helping to explain the performance gains achieved when scaling up model size. We further elucidate the design space of language models for vision generation, including tokenizer choice, model choice, model scalability, vocabulary design, and sampling strategy through extensive comparative experiments. Our work is the first to analyze the optimization behavior of language models in vision generation, and we believe it can inspire more effective designs when applying LMs to other domains. Finally, our elucidated language model for image generation, termed as ELM, achieves state-of-the-art performance on the ImageNet 256*256 benchmark. The code is available at https://github.com/Pepperlll/LMforImageGeneration.git.

[Arxiv](https://arxiv.org/abs/2410.16257)