# ReTok：通过替换分词器，提升大型语言模型中的表示效率

发布时间：2024年10月05日

`LLM理论` `人工智能`

> ReTok: Replacing Tokenizer to Enhance Representation Efficiency in Large Language Model

# 摘要

> Tokenizer 在 LLM 中至关重要，高压缩率的 tokenizer 能提升模型效率。然而，tokenizer 并非万能，输入输出长度的增加会推高训练和推理成本。因此，如何在低成本下提升模型效率，同时保持性能，成为关键。我们提出一种方法，通过替换 LLM 的 tokenizer 来优化模型。具体来说，我们用原始模型参数替换输入输出层，并固定其他参数进行训练。实验结果显示，这种方法不仅能保持模型性能，还能大幅提升长文本的解码速度。

> Tokenizer is an essential component for large language models (LLMs), and a tokenizer with a high compression rate can improve the model's representation and processing efficiency. However, the tokenizer cannot ensure high compression rate in all scenarios, and an increase in the average input and output lengths will increases the training and inference costs of the model. Therefore, it is crucial to find ways to improve the model's efficiency with minimal cost while maintaining the model's performance. In this work, we propose a method to improve model representation and processing efficiency by replacing the tokenizers of LLMs. We propose replacing and reinitializing the parameters of the model's input and output layers with the parameters of the original model, and training these parameters while keeping other parameters fixed. We conducted experiments on different LLMs, and the results show that our method can maintain the performance of the model after replacing the tokenizer, while significantly improving the decoding speed for long texts.

[Arxiv](https://arxiv.org/abs/2410.04335)