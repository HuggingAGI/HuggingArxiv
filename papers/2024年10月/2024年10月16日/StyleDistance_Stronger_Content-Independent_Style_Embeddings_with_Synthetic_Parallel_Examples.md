# StyleDistance：通过合成并行示例，实现更强大的内容无关风格嵌入

发布时间：2024年10月16日

`LLM应用` `文本处理`

> StyleDistance: Stronger Content-Independent Style Embeddings with Synthetic Parallel Examples

# 摘要

> 风格表示旨在将相似风格的文本紧密嵌入，不同风格的文本远远分开，无论内容如何。然而，常用的对比三元组可能在风格和内容上都有所不同，导致潜在的内容泄露。我们提出了 StyleDistance，一种新颖的方法，用于训练更强的内容无关风格嵌入。我们利用大型语言模型创建了一个具有控制风格变化的近似重述的合成数据集，并在 40 个不同风格特征上生成正负样本，以进行精确的对比学习。通过人类和自动评估，我们验证了合成数据和嵌入的质量。StyleDistance 增强了风格嵌入的内容独立性，使其在现实世界基准测试中表现优异，并在下游应用中超越了领先的风格表示。模型可在 https://huggingface.co/StyleDistance/styledistance 获取。

> Style representations aim to embed texts with similar writing styles closely and texts with different styles far apart, regardless of content. However, the contrastive triplets often used for training these representations may vary in both style and content, leading to potential content leakage in the representations. We introduce StyleDistance, a novel approach to training stronger content-independent style embeddings. We use a large language model to create a synthetic dataset of near-exact paraphrases with controlled style variations, and produce positive and negative examples across 40 distinct style features for precise contrastive learning. We assess the quality of our synthetic data and embeddings through human and automatic evaluations. StyleDistance enhances the content-independence of style embeddings, which generalize to real-world benchmarks and outperform leading style representations in downstream applications. Our model can be found at https://huggingface.co/StyleDistance/styledistance .

[Arxiv](https://arxiv.org/abs/2410.12757)